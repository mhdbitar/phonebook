<template>
	<nav class="navbar" role="navigation" aria-label="main navigation">
	  <div class="navbar-brand">
	  	<router-link to="/home" class="navbar-item">
	  		<img src="https://bulma.io/images/bulma-logo.png" alt='Mohammad' width="112" height="28">		    	
	    	</router-link>

	<div class="navbar-menu is-active">
		<router-link class="navbar-item" to="/home">Home</router-link>
    		<router-link class="navbar-item" to="/about">About</router-link>		
	</div>
	    
	    <button class="button navbar-burger">
	      <span></span>
	      <span></span>
	      <span></span>
	    </button>
	  </div>
	</nav>
</template>
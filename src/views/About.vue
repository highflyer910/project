<template>
  <div class="about main-content">
  	<div class="left-content">
  		<h1>About me</h1>
  		<p class="subtxt">I design, code and teach a bunch of people to do the same.</p>

  		<button><router-link to="/portfolio/one">Look at my work</router-link></button>
  	</div>
  	<div class="right-content">
  		<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
  		tempor incididunt ut labore et dolore magna aliqua.</p>
  		<p>Ut enim ad minim veniam,
  		quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
  		consequat.</p>
  	</div>
  </div>
</template>

<style lang="scss" scoped>
	.left-content{
		background-color: #ffe476;
	}

	.right-content{
		background-color: #fff;
		padding: 50px;
		margin-top: 80px;
		display: block;
	}

	button{
		font-size: 1.5em;
		margin-top: 100px;
	}

	.subtxtx{
		font-size: 1.5em;
		margin-top: 30px;
	}
</style>

<template>
    <div class="home main-content">
  	<div class="left-content slideUp">
      <router-link to="/portfolio/one"><img src="../assets/arrow-up.svg" class="arrow arrow-up"></router-link>

  		<h1>MOBILE UI</h1>

  		<p class="subtxt">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
  		tempor incididunt.</p>
  		<p class="subtxt">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
  		tempor incididunt.</p>

      <router-link to="/portfolio/three"><img src="../assets/arrow-down.svg" class="arrow arrow-down"></router-link>
  	</div>

  	<div class="right-content img2">
  	</div>
  </div>
</template>

<script>

export default {
  name: 'two'
}
</script>

<style lang="scss" scoped>
  $page_color: #48B886;

  h1{
    color: $page_color !important;
  }

	.img2{
		background: url(../assets/phone.jpg);
    background-size: cover;
    background-position: 50%;

    img{
      width: 50%;
    }
	}

</style>

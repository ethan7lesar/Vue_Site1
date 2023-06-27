<template>
  <div class="hero">
    <div class="p-5 text-end main-text">
      <div class="p-5">
        <h1 class="p-2">MetaDevices</h1>
        <p class="p-2">Don't be submissive and breedable. Be dominant and buy our stuff.</p>
        <a href="" class="shop btn">Shop Now!</a>
      </div>
    </div>
</div>
</template>

<script>
export default {
  name: 'HomeComp',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.hero{
  align-items: center;
  justify-content: center;
  background-image: url(https://i.postimg.cc/wMqDp27j/pink-laptop-hero-bg.jpg);
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  height: 500px;
}
.main-text{
  margin: auto;
  padding: auto;
}



</style>

<template>
  <div class="home main-content">
    <div class="left-content">
      <h1>20 YRS DESIGN</h1>

      <p class="subtxt">Al has been...</p>
      <p class="subtxt">He has worked with...</p>
    </div>

      <div class="right-content img1">
        <button><router-link to="/portfolio/one">Browse Work</router-link></button>
      </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>

<style scoped>

  .img1 {
    background: url('../assets/home.jpg');
  }

</style>
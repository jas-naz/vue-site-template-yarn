<template>
  <div class="one main-content">
    <div class="left-content slideUp">
      <h1>CRYPTO LOGO</h1>

      <p class="subtxt">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      <p class="subtxt">Quidem vero dicta tempore maxime itaque ullam! Eum, facere repellat? Vitae illo accusamus aperiam fugiat. Atque voluptatum tempora totam vero quisquam. Nihil?</p>
    
      <router-link to="/portfolio/two"><img src="../assets/arrow-down.svg" class="arrow arrow-down"></router-link>
    </div>

      <div class="right-content img2">
        <img src="../assets/logo.svg" alt="">
      </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'one',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss" scoped>

  $page_color: #625B7E;

  h1 {
    color: $page_color !important;
  }

  .img2 {
    background: $page_color;

    img {
      width: 50%;
    }
  }

</style>
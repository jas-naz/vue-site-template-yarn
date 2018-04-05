<template>
  <div class="three main-content">
    <div class="left-content slideUp">
      <router-link to="/portfolio/two"><img src="../assets/arrow-up.svg" class="arrow arrow-up"></router-link>
      
      <h1>PRINT</h1>

      <p class="subtxt">Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
      <p class="subtxt">Quidem vero dicta tempore maxime itaque ullam! Eum, facere repellat? Vitae illo accusamus aperiam fugiat. Atque voluptatum tempora totam vero quisquam. Nihil?</p>
    
      <!-- <router-link to="/portfolio/two"><img src="../assets/arrow-down.svg" class="arrow arrow-down"></router-link> -->
    </div>

      <div class="right-content img2">
      </div>
  </div>
</template>

<script>

export default {
  name: 'three'
}
</script>

<style lang="scss" scoped>

  $page_color: #5487a8;

  h1 {
    color: $page_color !important;
  }

  .img2 {
    background: url('../assets/card.jpg');
    background-size: cover;
    background-position: 50%;

    img {
      width: 50%;
    }
  }

</style>
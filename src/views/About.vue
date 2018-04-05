<template>
  <div class="about main-content">
    <div class="left-content">
      <h1>About me</h1>
      <p class="subtxt">I design and teach a bunch of other people...</p>

      <button><router-link to="/portfolio/one">Look at my work</router-link></button>
    </div>
    <div class="right-content">
      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Optio, sit impedit voluptatem, ipsam praesentium tempore repudiandae vitae sapiente porro itaque quia sunt aliquam? Mollitia, laborum.</p>
      <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Optio, sit impedit voluptatem, ipsam praesentium tempore repudiandae vitae sapiente porro itaque quia sunt aliquam? Mollitia, laborum.</p>
    </div>
  </div>
</template>

<style lang="scss" scoped>

  .left-content {
    background-color: #ffe476;
  }
  
  .right-content {
    background: #fff;
    padding: 50px;
    margin-top: 80px;
    display: block;

  }

  button {
    font-size: 1.5em;
    margin-top: 30px;
  }
</style>

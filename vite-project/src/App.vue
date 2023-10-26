<script setup>
import HelloWorld from './components/HelloWorld.vue';
import Navigation from './components/Navigation.vue';
</script>

<template>
  <Navigation/>
  <h2>Welcome to our Amazing Website</h2>
  <div class="imageHolder">
    <img src="../public/holographic_image.webp">
  </div>
</template>

<style scoped>
  h2 {
    padding: 5px;
    color: #f1f1f1;
    text-align: center;
  }

  .imageHolder {
    display: flex;
    width: 300px;
    height: 300px;
    margin: 20px auto;
  }

  img {
    transform: scale(100%);
    border-radius: 50%;
    box-shadow: 0 10px 20px white,
                0 -10px 10px purple;
  }
</style>


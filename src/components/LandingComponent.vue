<script setup>

import imagePath from "@/assets/7153683.jpg"

</script>

<template>
<div class="hero min-h-screen" :style="{ backgroundImage: `url(${imagePath})` }">
  <div class="hero-overlay bg-opacity-60"></div>
  <div class="hero-content text-center text-neutral-content">
    <div class="max-w-md">
      <h1 class="mb-5 text-5xl font-bold">JACQUELINE PORRAL</h1>
      <p class="mb-5">a passionate leader and a aspiring backend developer</p>
      <button class="btn btn-primary">Get Started</button>
    </div>
  </div>
</div>

</template>

<style scoped>

</style>

<script>


export default {
  data(){
   return {
      backimg : "@/assets/7153683.jpg",
     
   }
  }
}
</script>
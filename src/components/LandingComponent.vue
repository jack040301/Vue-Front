<script setup>
import imagePath from "@/assets/7153683.jpg";

import Header from "./Header.vue";
import Footer from "./Footer.vue";
</script>

<template>
  <div :style="{ backgroundImage: `url(${imagePath})` }">
    <Header class="bg-opacity-20"> </Header>
    <div class="hero min-h-screen">
      <div class="hero-overlay bg-opacity-0"></div>
      <div class="hero-content text-center text-neutral-content">
        <div class="flex flex-col w-full">
          <div class="grid place-items-center">
            <p class="text-6xl">JACQUELINE PORRAL</p>
          </div>
          <div
            class="divider divider-vertical before:bg-yellow-500 after:bg-yellow-500"
          ></div>
          <div class="grid place-items-center">
            <p class="text-2xl">
              AN ASPIRING BACKEND DEVELOPER AND PASSIONATE LEADER
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped></style>

<script>
export default {
  components: {},
  data() {
    return {
      backimg: "@/assets/7153683.jpg",
    };
  },
};
</script>

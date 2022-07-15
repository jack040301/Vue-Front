<script setup>
import TheWelcome from "@/components/Header.vue";
import HelloWorld from "../components/LandingComponent.vue";
import WelcomeItem from "../components/WelcomeItem.vue";
import Footer from "../components/Footer.vue";
import SideItem from "../components/SideItem.vue";
</script>

<template>
  <main>
    <TheWelcome />
  </main>

  <div>
    <HelloWorld />
  </div>

  <div class="flex flex-col w-full lg:flex-row">
    <div>
      <WelcomeItem />
    </div>
    <div class="divider"></div>
    <div>
      <WelcomeItem />
    </div>
  </div>

  <div>
    <Footer> </Footer>
  </div>
</template>

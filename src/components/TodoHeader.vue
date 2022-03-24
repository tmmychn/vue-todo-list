<script setup>
import {ref} from 'vue'
import $ from 'jquery'

const toggleDarkMode = () => {
  $(".dark-mode-toggle").find('img').toggleClass("hidden");
  $(".app").toggleClass("dark-theme");
};
</script>

<template>
  <header>
    <div class="logo">
      <h1 class="text-white">TODO</h1>
    </div>
    <button
      @click="toggleDarkMode()"
      class="dark-mode-toggle">
      <img src="../assets/icon-moon.svg" alt="moon icon" />
      <img src="../assets/icon-sun.svg" alt="sun icon" class="hidden" />
    </button>
  </header>
</template>

<style>

</style>

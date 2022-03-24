<script setup>
import TodoHeader from "./components/TodoHeader.vue";
</script>

<template>
  <div className="app">
      <div className="bg-img" />
      <div className="container">
        <TodoHeader />
        <TodoComponent />
      </div>
  </div>
</template>

<style>
@import "./assets/main.css";
</style>

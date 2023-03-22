<script setup>
import { defineAsyncComponent } from "vue";
const Header = defineAsyncComponent(() => import("remote/Header"));
</script>

<template>
  <div class="container">
      <Header />
      <div>Name: LOCAL</div>
      <div>Framework: Vue 3</div>
      <div>:Vite</div>
  </div>
</template>
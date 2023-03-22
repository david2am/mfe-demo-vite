<script setup>
import { defineAsyncComponent } from "vue";
const Header = defineAsyncComponent(() => import("remote/Header"));
</script>

<template>
  <div class="container">
      <Header />
      <div>Name: LOCAL</div>
      <div>Framework: vue2</div>
      <div>Language: JavaScript</div>
      <div>CSS: Empty CSS</div>
  </div>
</template>
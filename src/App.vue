<template>
  <d iv>测 试</d>
  <div>
    <span> {{ a }}</span>
  </div>
</template>

<script setup lang="ts">
import { ref } from "vue";

let a = ref(3);
</script>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>

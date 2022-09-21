<script setup>
</script>

<template>
  <div>
    <img src="/beer.svg" class="logo" alt="Beer" />
  </div>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  filter: drop-shadow(0 0 2em transparent);
  transition: all 400ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
</style>

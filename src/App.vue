<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
</script>

<template>
  <div class="container">
    <div class="container_left"></div>
    <div class="container_right"></div>
  </div>
</template>

<style scoped>
.container {
  width: 100%;
  height: 100vh;
  display: flex;
  flex-direction: row;
}

.container_left {
  width: 73px;
  height: 100vh;
  background-color: white;
}

.container_right {
  flex: 1;
  height: 100vh;
  background-color: whitesmoke;
}
</style>

<script setup lang="ts">
import Sidebar from '../components/Sidebar.vue'
</script>

<template>
  <div class="wrapper">
    <!-- <h1>Tasky</h1>

    <nav class="nav">
      <RouterLink to="/">Home</RouterLink>
      <RouterLink to="/about">About</RouterLink>
    </nav> -->
    <Sidebar />
  </div>
</template>

<style scoped>
.wrapper {
  /* background-color: rgb(119, 119, 169); */
  display: flex;
  align-items: center;
  gap: 15px;
  height: 100vh;
}

.nav {
  display: flex;
  gap: 20px;
}
</style>

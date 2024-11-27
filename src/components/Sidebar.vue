<script lang="ts" setup></script>
<template>
  <div class="wrapper-sidebar">
    <div class="header">
      <h4>Carlos</h4>
    </div>
    <div class="navegacao">
      <a href="#" class="nav-button">Hoje</a>
      <a href="#" class="nav-button">Em breve</a>
      <a href="#" class="nav-button">Sem data</a>
      <a href="#" class="nav-button">Projetos</a>
    </div>
    <div class="footer"></div>
  </div>
</template>

<style scoped>
.wrapper-sidebar {
  max-width: 320px;
  width: 90%;
  height: 100svh;
  background-color: var(--primary-color);
  color: white;

  @media (max-width: 768px) {
    width: 56px;
  }
}

.navegacao {
  display: flex;
  flex-direction: column;
  gap: 5px;
}

.nav-button {
  /* background-color: tomato; */
  height: 35px;
  display: flex;
  align-items: center;
  text-decoration: none;
  padding: 5px;
  color: aliceblue;
}
.nav-button:hover {
  background-color: black;
}
</style>

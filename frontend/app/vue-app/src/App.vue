<script setup></script>

<template>
  <header>
    <h1 class="title">今日のToDo</h1>
    <img
      alt="App logo"
      class="logo"
      src="./assets/todo-logo.svg"
      width="35"
      height="35"
    />
  </header>
  <RouterView />
</template>

<style scoped>
.logo {
  display: block;
}

header {
  background-color: hsla(160, 100%, 37%, 1);
  color: white;
  padding: 1rem;
  display: flex;
  justify-content: flex-start;
  align-items: center;
  flex-direction: row;
}

.title {
  margin: 0;
  padding: 0.5rem 1rem 0.5rem 2rem;
}
</style>

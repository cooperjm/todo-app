<script setup>
import TodoApp from './components/TodoApp.vue';
import TodoList from './components/TodoList.vue';
</script>

<template>
  <TodoApp />
</template>

<style>
#app {
  background-color: #597d9a;
  display: flex;
  justify-content: center;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  min-height: 100vh;
}
body {
  margin: 0;
}
</style>

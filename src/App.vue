<template>
  <div id="app">
    <AddTodo />
    <filiterTodo />
    <todos />
  </div>
</template>

<script>
import store from './store';
import AddTodo from './components/AddTodo.vue';
import FiliterTodo from './components/FilterTodo.vue';
import Todos from './components/Todos.vue';
export default {
  name: 'app',
  store,
  components: {
    AddTodo,
    FiliterTodo,
    Todos

  }
}
</script>

<style>
body {
  background: #cccc;
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
  margin-top: 60px;
  width: 1100px;
  margin: 60px auto;
}
h3 {
  padding: 10px;
  margin: 0;
}
</style>

<template>
  <div id="app">
    <todo/>
  </div>
</template>

<script>
import todo from './components/todo.vue'
import store from './store/index.js'


export default {
  name: 'app',
  components: {
    todo
  },
  store
}

</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

<template>
  <div id="app">
    <Paginator/>
  </div>
</template>

<script>
import Paginator from './components/Paginator'

export default {
  name: 'app',
  components: {
    Paginator
  }
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

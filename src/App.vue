<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <componentMain/>
  </div>
</template>

<script>
import componentMain from './components/componentMain.vue'

export default {
  name: 'App',
  components: {
    componentMain,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

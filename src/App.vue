<template>
  <div id="app">
    <Title/>
    <img alt="Labirinto" src="./assets/Cubo-labirinto.jpg">
  </div>
</template>

<script>
import Title from './components/Title.vue';

export default {
  name: 'App',
  components: {
    Title
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2e3133;
  margin-top: 40px;
}
</style>

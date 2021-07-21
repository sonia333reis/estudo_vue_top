<template>
  <div id="app">
  <create-button> </create-button>
  </div>
</template>

<script>
import CreateButton from './components/CreateButton.vue';

export default {
  name: 'App',
  components: {
    CreateButton
  }
}
</script>

<style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>

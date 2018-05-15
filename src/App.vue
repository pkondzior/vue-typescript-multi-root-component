<template>
  <div id="app">
    <img src="./assets/logo.png">
    <MultiRoot/>
  </div>
</template>

<script lang="ts">
import Vue from 'vue';
import MultiRoot from './components/MultiRoot.vue';

export default Vue.extend({
  name: 'app',
  components: {
    MultiRoot
  }
});
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

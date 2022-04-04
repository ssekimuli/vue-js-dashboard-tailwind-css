<template>
  <div class="flex flex-row h-screen p-0 bg-blue-300 columns-12">
    <dashboard/>
  </div>
</template>

<script>

import dashboard from './components/Main-Dashboard.vue';
import './assets/tailwind.css';

export default {
  name: 'App',
  components: {
    dashboard
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #55718d;
}
</style>

<template>
  <Menu />
  <Main />
</template>

<script>
import Main from './components/Main.vue';
import Menu from './components/Menu.vue';
import './style.css';

export default {
  components: {
    Main,
    Menu
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background: var(--background);
  height: 100vh;
}
</style>

<template>
  <MenuVuetify/>
  <router-view></router-view>
</template>

<script>
import MenuVuetify from './components/MenuVuetify.vue';

export default {
  name: 'App',
  components: {
    MenuVuetify
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
  /* margin-top: 60px; */
}
</style>

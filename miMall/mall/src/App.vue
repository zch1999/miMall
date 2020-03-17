<template>
  <div id="app">
    <nav-header></nav-header>
    <router-view></router-view>
    <bav-footer></bav-footer>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
  },
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

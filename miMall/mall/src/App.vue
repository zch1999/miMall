<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
import storage from './storage'
export default {
  name: 'App',
  components: {
  },
  mounted(){
    // storage.setItem('a',1)
    // storage.setItem('abc',{a:1},'user')
    storage.clear('a')
  }
}
</script>

<style>
@import './assets/scss/reset.scss'
</style>

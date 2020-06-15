<template>
  <div id="app">
    <a href="/">
      <img class="logo" alt="Begrato logo" width="50" src="./assets/logo.jpg">
    </a>
    <AppHeader msg="Welcome to Your Vue.js App"/>
    <div class="ui container">
      <router-view></router-view>
    </div>  
  </div>
</template>

<script>
import AppHeader from './components/AppHeader'

export default {
  name: 'App',
  components: {
    AppHeader
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
.logo {
  float: left;
  align-items: flex-start;
  margin-left: 1%;
  margin-right: 1%;
}
</style>

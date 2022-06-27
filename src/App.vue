<template>
  <HeaderNav/>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <FooterBg/>
</template>

<script>
import HeaderNav from './components/HeaderNav.vue'
import HelloWorld from './components/HelloWorld.vue'
import FooterBg from './components/FooterBg.vue'

export default {
  name: 'App',
  components: {
    HeaderNav,
    HelloWorld,
    FooterBg
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #3ec030;
  margin-top: 60px;
  background-color: #500954;
}
</style>

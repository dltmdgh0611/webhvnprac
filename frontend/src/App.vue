<template>
  <MainNavbar></MainNavbar>
  <hvn-test></hvn-test>
</template>

<script>
import MainNavbar from './components/MainNavbar.vue'
import HvnTest from './components/HvnTest.vue'
export default {
  name: 'App',
  components: {
    MainNavbar,
    HvnTest
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

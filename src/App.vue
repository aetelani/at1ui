<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <p>nice</p>
    <HelloWorld msg="So Nice."/>
    <TopMenu msg="Nice."/>
    <LeftMenu msg="Nice."/>
  </div>
</template>

<script>
import Vue from 'vue'

import Navbar from 'bootstrap-vue/es/components/navbar'
Vue.use(Navbar)

import HelloWorld from './components/HelloWorld.vue'
import LeftMenu from './components/LeftMenu.vue'



export default {
  name: 'app',
  components: {
    LeftMenu,
    HelloWorld,
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #fc3e50;
  margin-top: 60px;
}
</style>

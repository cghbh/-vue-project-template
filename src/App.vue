<template>
  <div id="app">
    <img src="./assets/logo.png">
    <div>
      <el-button type="danger">el-button</el-button>
      <el-button style="margin-left: 20px" type="primary">el-button</el-button>
    </div>
    <HelloWorld msg="Welcome to Your Vue.js + Element + Typescript App"/>
  </div>
</template>

<script lang="ts">
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
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

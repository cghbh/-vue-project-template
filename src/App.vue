<template>
  <div id="app">
    <img src="./assets/logo.png">
    <div>
      <van-button type="primary">Button</van-button>
      <van-button style="margin-left: 20px" type="warning">Button</van-button>
    </div>
    <HelloWorld msg="Welcome to Your Vue.js + Vant + Javascript App" />
  </div>
</template>

<script>
import HelloWorld from '@/components/HelloWorld.vue'
export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

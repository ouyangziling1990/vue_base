<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <HelloWorld msg="ziling come on"/>
    <a href="">vue-router</a> <a href="">vuex</a> <a href="">axious</a>
    <ComeOn msg="stady hungry, stady young"></ComeOn>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import ComeOn from './components/ComeOn.vue'
export default {
  name: 'app',
  components: {
    HelloWorld,
    ComeOn
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
a{
  margin: 5px;
  cursor: pointer;
  text-decoration: none;
}
</style>

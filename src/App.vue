<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Title/>
    <Img/>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Title from './components/Title.vue';
import Img from '@/components/Image.vue'

export default {
  name: 'App',
  components: {
    //HelloWorld
    Title,
    Img
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

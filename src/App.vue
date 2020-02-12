<template>
  <div id="app">
    <div> header</div>
    <HelloWorld msg="Vue.js aula da thais" oi="olá"/>
    <Quadrado :n="3"/>
    <Cubo :n="3"/>
    
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Quadrado from './components/Quadrado.vue'
import Cubo from './components/Cubo.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    Quadrado,
    Cubo
  },data(){
    return { n : 4}
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

<template>
  <div class="container" id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>

    <div class="row">
      <div class="col">
      <Hello1 />
      </div>

      <div class="col">
      <Hello1 />
      </div>

      <div class="col">
      <Hello1 />
      </div>
    </div>

<br>
    <div class="row">
      <div class="col">
      <Hello1 />
      </div>

      <div class="col">
      <Hello1 />
      </div>

      <div class="col">
      <Hello1 />
      </div>

      
    </div>  
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Hello1 from './components/Hello1.vue'


export default {
  name: 'App',
  components: {
    HelloWorld,
    Hello1
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

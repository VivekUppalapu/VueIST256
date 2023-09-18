<template>
  <HelloWorld msg="Welcome to Your Vue.js App"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
.wrap{
    width: 400px;
    border: 2.5px solid black;
    background-color: red;
  }
  .image{
    width: 400px;
    
  }
  .header{
     text-align: center;
  }
  .header h3{
    font-size: 40px;
    color: blue;
  }
  .descrip
  {
    font-size: 16px;
    font-weight: bold;
    color: white;
  }
  .allbtns button
  {
    font-size: 15px;
    background-color: white;
    color: teal;
  }
  .Detail
  {
    font-size: 17px;
    color: purple;
    background-color: white;
  }
  
  
</style>

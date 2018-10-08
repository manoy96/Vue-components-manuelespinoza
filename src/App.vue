<template>
  <div id="app">
    <my-header></my-header>
    <div id="serve">
      <my-servers></my-servers>
      <my-details></my-details>
    </div>
    <my-footer></my-footer>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
import ServerDetails from './components/ServerDetails.vue'
import Servers from './components/Servers.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    'my-header': Header,
    'my-footer': Footer, 
    'my-details': ServerDetails,
    'my-servers': Servers
  }, 
  
}
</script>

<style>
body{background-color: #fdfdfd;}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;

}
#serve{
  display: flex;
  flex-direction: row;
  border: 1px #000 solid;
  margin: 1rem auto;
  padding: 1rem 0;
}
</style>

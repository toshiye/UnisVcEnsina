<template>
  <div id="app">
    <index/>
    <SideBar/>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import Index from './components/main/Index.vue'
import SideBar from './components/SideBar/SideBar.vue'

export default {
  name: 'App',
  components: {
    //HelloWorld
    Index,
    SideBar
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

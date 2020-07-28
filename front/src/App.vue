<template>
  <div id="app">
    <Header/>
    <index/>
    <SideBar/>
  </div>
</template>

<script>
import Index from './components/main/Index.vue'
import SideBar from './components/SideBar/SideBar.vue'
import Header from './components/header/Header.vue'

export default {
  name: 'App',
  components: {
    Index,
    SideBar,
    Header
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

  /* #sideBar{
    position: absolute;
    top: 0%;
    left: 0%;
  } */
</style>

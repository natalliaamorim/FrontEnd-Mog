<template>
  <div id="app">
    <nav-bar cor = "depp-purple lighten-1" logo ="Logo Estilizado" url="home"></nav-bar>
    
    <router-view/>
  </div>
</template>

<script>
import NavBar from './components/layouts/NavBar.vue';


export default {
  name: 'App' ,
  components:{
    NavBar,
   
  }
}
</script>

<style>

</style>

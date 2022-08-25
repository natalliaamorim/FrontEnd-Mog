<template>
  <nav :class = "cor ||'blue'">
    <div class="nav-wrapper container">
      <a :href="url ||'#'" class="brand-logo">{{logo || 'Site VueJs'}}</a>
      
    </div>
  </nav>
</template>

<script>
export default {
  name: 'NavBar',
  props: ['logo' , 'url' , 'cor'],
  data () {
    return {
    //   msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
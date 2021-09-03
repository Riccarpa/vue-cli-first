<template>
  <div id="app">
    
    
    <hello/>
    <jumbo/>
  </div>
  
</template>

<script>



import hello from './components/hello.vue'
import jumbo from './components/jumbo.vue'
export default {
  name: 'App',
  components: {
    hello,
    jumbo
  }
}
</script>

<style lang="scss">
#app{
  text-align: center;
}
</style>

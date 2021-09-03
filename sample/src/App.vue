<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <h1>HelloWorld</h1>
    <Ciao/>
  
  </div>
  
</template>

<script>



import Ciao from './components/hello.vue'

export default {
  name: 'App',
  components: {
    Ciao,
  }
}
</script>

<style lang="scss">

</style>

<template>
  <div id="app">
    <!-- <HelloWorld/> -->
    <Header/>
    <Footer/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'


export default {
  name: 'App',
  components: {
    // HelloWorld,
    Header,
    Footer
  }
}
</script>

<style>
</style>

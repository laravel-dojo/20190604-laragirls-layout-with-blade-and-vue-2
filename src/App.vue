<template>
  <div id="app">
    <Navigation/>
    <Home/>
    <Footer/>
  </div>
</template>

<script>
import Navigation from './components/Navigation.vue'
import Footer from './components/Footer.vue'
import Home from './components/Home.vue'

export default {
  name: 'app',
  components: {
    Navigation,
    Footer,
    Home
  }
}
</script>

<style>

</style>

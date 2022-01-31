<template>
  <div id="app">
    <Appheader />
    <Home />
    <About />
    <Product />
    <Contact />
  </div>
</template>

<script>
import Appheader from './components/Appheader.vue'
import Home from './components/Home.vue'
import About from './components/About.vue'
import Product from './components/Product.vue'

export default {
  name: 'App',
  components: {
    Appheader,
    Home,
    About,
    Product,
  },
}
</script>

<style></style>

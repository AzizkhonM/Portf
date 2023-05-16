<script setup>
  import Navbar from '../components/Universal/Navbar.vue';
  import First from "../components/Home/First.vue"
  import Second from '../components/Home/Second.vue';
  import Third from '../components/Home/Third.vue';
  import Footer from '../components/Universal/Footer.vue';
</script>

<template>
  <header>
    <Navbar />
  </header>
  
  <div>
    <First />
    <Second />
    <Third />
  </div>

  <footer>
    <Footer />
  </footer>
</template>

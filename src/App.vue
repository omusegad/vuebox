<script setup>
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'
import Navbar from './components/Navbar.vue'



</script>

<template>
  <header>
    <Navbar/>
  </header>

  <main>
    <div class="container">
      <div class="row">
        <Main />
      </div>
    </div>
  </main>
  <div>
    <Footer/>
  </div>

</template>

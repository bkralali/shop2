<script setup>
import TheWelcome from '../components/TheWelcome.vue'
import Navbar from '../components/navbar.vue';
import Dashbord from '../components/dashbord.vue';
import Footer from '../components/footer.vue';
 
  
</script>

<template>
   <Navbar class="index"/>
   <Dashbord/>
   <Footer/>
</template>

<style scoped>
 .index{
  z-index: 9999;
 }
</style>

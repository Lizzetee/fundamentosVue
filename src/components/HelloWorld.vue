<script setup>

import Card from './Card.vue';
import Nav from './nav.vue';
import Carrusel from './Carrusel.vue';
import Footer from './Footer.vue';
import Spinners from './Spinners.vue';
import Canvas from './Canvas.vue';
import Responsive from './Responsive.vue';

</script>

<template>
  <div class="container">

    <h1 class="text-center">XpediTEC</h1>
    <!-- INICIO DEL RPIMER ROW -->
    
<div class="row row-cols-1 row-cols-md-2 g-4">
  <div class="col"></div>

</div>
<!-- CIERRE DEL PRIMER ROW -->
<!-- INICIO DEL  ROW 2 -->
<Nav/>
<Carrusel/>
<Card/>
<Spinners/>
<Canvas/>
<Responsive/>
<Footer/>

 <!-- CIERRE DEL ROW 2 -->
  <!--  -->
  
 <!--  -->


  </div>

</template>


<style scoped>

</style>
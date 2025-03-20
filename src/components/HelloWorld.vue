<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
<h1> Hola Mundo </h1>


 <button class="bnt"> Hola soy un botón </button>

 <br>  </br> <br> </br>

 <img 
        class="imagenes"
        src="https://i.pinimg.com/736x/09/fe/6f/09fe6fb4700b309422326d6a8e2f0c44.jpg"
         alt="holaaaaaa">
<p class="parrafo"> 
Practicaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa 1
 </p>
</template>


<style scoped>
h1{
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  font-size: 45 px;
  color: red;
}
.parrafo{
  text-align: center;
  color: rgb(247, 232, 238);
}
.read-the-docs {
  color: #888;
}
.bnt{
  border-radius: 15px;
  background-color: #ffff;
  color: black;
}
.imagenes{
    width: 350px;
    height: 350px;
    border-radius: 100%;
}
</style>
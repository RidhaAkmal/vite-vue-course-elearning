<script setup>
import Atas from './template/Header.vue'
import Tengah from './home/Main.vue'
import Bawah from './template/Footer.vue'
</script>

<template>
  <header>
    <Atas/>
  </header>
    
  <main>
    <Tengah/>
  </main>

  <footer>
    <Bawah/>
  </footer>
</template>

<style>


main{
  text-align: center;
}

body {
  font-family: sans-serif;
  color: #40c98d;
  background-color: #27394a;
  padding: 5%;
 }
 
 .card {
   background: #f9f9f9;
   width: 250px;
   height: 100%;
   padding: 25px;
   display: inline-block;
   vertical-align: top;
   margin: 10px;
   border-radius: 45px;
   color: #27394a;
 }
 
 img {
   height: 150px;
 }
 
 button {
   background: #27394a;
   color: #f9f9f9;
   padding: 10px 20px;
   border: none;
   cursor: pointer;
 }

</style>
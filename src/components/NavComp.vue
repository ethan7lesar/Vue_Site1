<template>
   <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>| 
    <router-link to="/products"> Products</router-link>|
    <router-link to="/contact">Contact</router-link>
   </nav>
</template>
<script>
 export default {
   
 }
</script>

<style>
nav {
    margin: 0;
    padding: 30px;
    background-color: black;
  }
  
  nav a {
    font-weight: bold;
    color: white;
  }
  
  nav a.router-link-exact-active {
    color: #42b983;
  }
</style>
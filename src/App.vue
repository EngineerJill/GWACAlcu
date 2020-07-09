<template>
  <div id="app">
    <div class="nav-bar">
      <h3 class="logo">GWA Calculator</h3>
    </div>
    <router-view />
  </div>
</template>

<script>

export default {
  name: 'App',
   
   }
</script>

<style>
     * {
        margin: 0;
        padding: 0;
        font-family: Arial, Helvetica, sans-serif;
    }
    .nav-bar {
        height: 50px;
        width: 100%;
        background-color: #07689F;
        position: relative;
    }
    
    .logo {
        position: absolute;
        top: 20%;
        font-family: 'Times New Roman', Times, serif;
        color: white;
        font-size: 1.5rem;
        left: 3%;
    }

</style>

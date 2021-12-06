<template>
 <div class="hello">
   
   <h1>{{ msg }}</h1>
   <br>
   <button class="btn btn-primary">
     Hola Bootstrap
   </button>
   <br>
   <div class="alert alert-warning" role="alert">
     Ya puedes agregar componentes 
     Bootstrap a Vue/Cli!
   </div>
 </div>
</template>

<script>
import Nabvar from './components/Navbar.vue'

export default {
  name: 'App',
  components: {
    Nabvar
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

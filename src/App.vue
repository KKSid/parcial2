<template>
  <div class="app">
  <login></login>
  <Ussuarios></Ussuarios>
  </div>
</template>

<script>
import login from './components/login.vue'
import Ussuarios from './components/Ussuarios.vue'
export default{
  name: 'app',
  components:{
    login,
    Ussuarios
  }
}
</script>
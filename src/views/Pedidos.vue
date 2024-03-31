<template>
  <div class="main-container">
    <h1>Gerenciar Pedidos: </h1>
    <Dashboard/>
  </div>
</template>

<script>
import Dashboard from '../components/Dashboard'
export default {
  name: 'Pedidos',
  data() {
    return {
      pedidos: []
    }
  },
  components: {
    Dashboard
  },

}
</script>

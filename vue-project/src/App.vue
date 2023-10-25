<template>
  <h1>site do DG🐶😒👌</h1>
  <cardComponent name="douglas" descricao="paiva" />
  <cardComponent name="julia" descricao="silva" />
</template> 

<script>
// import Zap from './components/Zap';
import cardComponent from './components/cardComponent.vue';
export default {
  name: 'App',
  components: {
    // Zap,
    cardComponent
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

<template>
  <div id="app">
    <InfoCard v-for="n in 10000" :key="n"/>
  </div>
</template>

<script>
import InfoCard from './components/InfoCard.vue'

export default {
  name: 'app',
  components: {
    InfoCard
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

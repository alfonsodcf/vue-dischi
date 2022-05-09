<template>
  <div id="app">
   <app-header/>
   <main>
     <app-grid/>
   </main>
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue';
import AppGrid from './components/AppGrid.vue'

export default {
  name: 'App',
  components: {
    AppHeader,
    AppGrid
  }
}
</script>

<style lang="scss">
@import "./assets/generals.scss";
#app {
  
}
</style>

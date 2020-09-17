<template>
  <div id="app">
    <FeedTheCat />
  </div>
</template>

<script>
import FeedTheCat from './components/FeedTheCat/Main.vue'

export default {
  name: 'App',
  components: {
    FeedTheCat
  }
}
</script>

<style>

@font-face{
  font-family: 'Exo20';
  src: url('./assets/fonts/Exo20-Thin.ttf');
}
#app {
  
}
</style>

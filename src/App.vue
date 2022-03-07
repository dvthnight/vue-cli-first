<template>
  <div id="app">
    <MyTitle />
    <JumboHero />
  </div>
</template>

<script>
import MyTitle from './components/MyTitle.vue'
import JumboHero from "./components/JumboHero.vue"

export default {
  name: 'App',
  components: {
    MyTitle,
    JumboHero
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

// Ho risolto problema legato a Title sostituendo il nome con MyTitle

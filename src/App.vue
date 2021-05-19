<template>
  <div id="app">
    <titulo-comp />

    <main>
      <h2>como estas?</h2>
    </main>

    <footer>
      <h3>bien</h3>
    </footer>
  </div>
</template>

<script>
import TituloComp from './components/TituloComp.vue'

export default {
  name: 'App',
  components: {
    TituloComp
  }
}
</script>

<style lang="scss">

</style>

<template>
  <Topo />
  <main>
    <Meio />
    <Historia />
  </main>
  <RodaPe />
</template>

<script>
import Topo from './components/TopoHeader.vue'
import Meio from './components/MeioMain.vue'
import Historia from './components/HistoriaMain.vue'
import RodaPe from './components/PeFooter.vue'

import './style/global.css'
import './assets/style.css'

export default {
  name: 'App',
  components: {
    Topo,
    Meio,
    Historia,
    RodaPe
  }
}
</script>

<style>

</style>

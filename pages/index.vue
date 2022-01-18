<template>
  <main-hero />
</template>

<script>
/* eslint-disable vue/no-multiple-template-root */
import Alpine from 'alpinejs'
import MainHero from '../components/MainHero.vue'

window.Alpine = Alpine
Alpine.start()
export default {
  name: 'IndexPage',
  components: { MainHero }
}
</script>

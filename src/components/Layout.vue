<script setup>
import { ref } from 'vue'

import Header from './Header.vue'
import Main from './Main.vue'
import Footer from './Footer.vue'


defineProps({
  // msg: String,
})

// const count = ref(0)
</script>

<template>
  <div class="layout">
    <Header />
    <Main />
    <Footer />
  </div>
  

</template>

<style scoped>

</style>

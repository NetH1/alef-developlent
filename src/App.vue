<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Header from './components/Header.vue'

</script>

<template>
  <div>
    <header>
      <Header/>
    </header>
  </div>
  <RouterView />
</template>



<script setup>
import { RouterLink, RouterView } from 'vue-router'
import  { router} from 'vue'
</script>

<template>
  <header>
    <RouterLink to="/guider">Utpost</RouterLink>
  </header>
  <main>
    <RouterView />
  </main>
</template>

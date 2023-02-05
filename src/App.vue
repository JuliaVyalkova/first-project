<script setup>
import TheHeader from '@/components/TheHeader.vue'
import TheFooter from '@/components/TheFooter.vue'
</script>

<template>
  <TheHeader />
  <main class="main">
    <RouterView />
  </main>
  <TheFooter />
</template>

<style>

#app {
  display: flex;
  min-height: 100vh;
  flex-direction: column;
}

.main {
  flex: 1;
}

</style>

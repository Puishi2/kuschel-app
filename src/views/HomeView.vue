<script setup lang="ts">

function playSound() {
  const sound = (new Audio(require('@/assets/ring.mp3')).play())
}

</script>

<template>
  <div class="flex items-center justify-center min-h-screen">
    <button @click="playSound" class="bg-red-400 text-white h-32 w-52 border-none text-3xl rounded-2xl hover:bg-red-600 transition">Kuscheln</button>
  </div>
</template>

<style scoped>

</style>
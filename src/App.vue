<template>
  <main class="flex flex-col">
    js/tailwindcss/pinia/vue3/vueUse/Prumvue/daisyui
  </main>
</template>
<script setup>
import { useMouse } from '@vueuse/core'
const mouse = useMouse()
console.log(mouse.x.value)
</script>
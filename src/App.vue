<template>
  <main class="flex flex-col">
    js/tailwindcss/pinia/vue3/vueUse/Prumvue/daisyui
    <Helloworld />
  </main>
</template>
<script setup>
import { useMouse } from '@vueuse/core'
import Helloworld from './components/Helloworld.vue';
const mouse = useMouse()
console.log(mouse.x.value)
</script>
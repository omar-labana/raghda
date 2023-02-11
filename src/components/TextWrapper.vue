<script setup>
import TextFill from "./TextFill.vue";
import TextOutline from "./TextOutline.vue";
import LoveFill from "./LoveFill.vue";
import LoveOutline from "./LoveOutline.vue";
</script>

<template>
  <main
    id="text"
    class="whitespace-nowrap text-[5vw] absolute h-screen w-screen flex flex-col justify-between -left-[100%] uppercase tracking-wide leading-none select-none"
  >
    <span v-for="i in 10" :key="i">
      <TextFill />
      <TextOutline />
      <LoveFill />
      <LoveOutline />
    </span>
  </main>
</template>

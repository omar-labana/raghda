<script setup>
/* eslint-disable */
import { onMounted } from "vue";
import TextWrapper from "./TextWrapper.vue";

onMounted(() => {
  gsap.to("#text > span > .px", 3, {
    x: "-1000",
    ease: Expo.easeInOut,
    delay: 0.5,
    stagger: 0.1,
  });

  gsap.to("#text > span > .xp", 3, {
    x: "-1000",
    ease: Expo.easeInOut,
    delay: 0.5,
    stagger: 0.1,
  });

  gsap.to("#text", 3, {
    y: -200,
    scale: 1.5,
    rotate: -90,
    ease: Expo.easeInOut,
    delay: 2.5,
  });

  gsap.to("#text > span > p", 3.5, {
    x: "-3500",
    ease: Expo.easeInOut,
    delay: 3.5,
    stagger: 0.05,
  });

  gsap.to("#overlay", 2, {
    bottom: "-110%",
    ease: Expo.easeInOut,
    delay: 6,
  });
});
/* eslint-enable */
</script>

<template>
  <main id="overlay" class="overflow-hidden">
    <TextWrapper />
  </main>
</template>

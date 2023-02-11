<script setup>
import imgUrl from "@assets/raghda.jpg";
import AnimatedFlower from "./AnimatedFlower.vue";
</script>
<template>
  <div class="max-w-7xl mx-auto px-4 md:px-8 xl:px-0 min-h-screen">
    <header class="flex items-center justify-between">
      <div class="flex items-center -translate-x-10">
        <AnimatedFlower />

        <span class="text-4xl font-light text-[#f6c177] uppercase"
          >raghda<span class="text-[#eb6f92] font-black">.</span></span
        >
      </div>
      <div class="flex items-center gap-4">
        <span class="">
          <svg
            class="h-7 w-7 text-[#ebbcba]"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
          >
            <path
              d="M23 3a10.9 10.9 0 0 1-3.14 1.53 4.48 4.48 0 0 0-7.86 3v1A10.66 10.66 0 0 1 3 4s-4 9 5 13a11.64 11.64 0 0 1-7 2c9 5 20 0 20-11.5a4.5 4.5 0 0 0-.08-.83A7.72 7.72 0 0 0 23 3z"
            />
          </svg>
        </span>

        <span>
          <svg
            class="h-7 w-7 text-[#ebbcba]"
            viewBox="0 0 24 24"
            fill="none"
            stroke="currentColor"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
          >
            <rect x="2" y="2" width="20" height="20" rx="5" ry="5" />
            <path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z" />
            <line x1="17.5" y1="6.5" x2="17.51" y2="6.5" />
          </svg>
        </span>
      </div>
    </header>

    <main class="grid grid-cols-12 my-10 gap-1">
      <div class="col-span-12 lg:col-span-4 aspect-[640/800] relative">
        <span class="overflow-hidden relative w-full h-full">
          <div
            class="w-full h-full bg-center bg-cover grayscale hover:grayscale-0 hover:scale-110 transition-all duration-500"
            :style="`background-image: url(${imgUrl})`"
          ></div>
        </span>
      </div>

      <div class="col-span-12 lg:col-span-7 text-justify lg:px-10">
        <div class="text-xl">
          Have you ever
          <span class="underline decoration-wavy decoration-[#ebbcba]"
            >wondered</span
          >
          what it would be like to have a
          <span class="underline decoration-wavy decoration-[#eb6f92]"
            >TV presenter</span
          >
          that could make even the most boring news segments
          <span class="underline decoration-wavy decoration-blue-900"
            >entertaining</span
          >? Someone who could take the
          <span class="underline decoration-wavy decoration-[#31748f]"
            >mundane news</span
          >
          and turn it into something
          <span class="underline decoration-wavy decoration-[#c4a7e7]"
            >magical</span
          >, <span class="font-black italic text-[#ea9a97]">ALL</span> while
          keeping you informed and on the edge of your seat. Well, look no
          further! <span class="text-[#eb6f92] font-bold">Raghda</span> is the
          <span>queen</span> of all hosts, the ruler of the roost, the master of
          the mic...the one and only
          <span class="underline decoration-wavy decoration-[#eb6f92]"
            >show host</span
          >
          who can make you laugh, and learn. Moreover,
          <span class="text-[#eb6f92] font-bold">Raghda</span> prefers
          <span class="underline decoration-wavy decoration-[#f6c177]"
            >chicken thighs.</span
          >
          (also if you are on a PC hover over the image,
          <span class="text-[#eb6f92] font-bold">she (◕‿◕✿)</span> pops up
          smiling)
        </div>
      </div>
    </main>
  </div>
</template>

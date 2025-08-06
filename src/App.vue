<script setup lang="ts">
import { Icon } from '@iconify/vue'
</script>

<template>
  <body class="flex flex-col justify-center items-center md:h-screen text-white p-4">
    <div class="text-8xl text-center">Jake Green</div>
    <div class="text-3xl text-center">Frontend Developer</div>
    <div class="my-6 flex justify-center gap-5">
      <a
        href="https://github.com/jakeg96"
        target="_blank"
        class="flex items-center text-blue-400 hover:text-blue-300 text-2xl"
        ><Icon icon="simple-icons:github" class="size-8 mr-2" />Github</a
      >
      <a
        href="/jakegreen2025.pdf#toolbar=0"
        target="_blank"
        class="flex items-center text-blue-400 hover:text-blue-300 text-2xl"
        ><Icon icon="qlementine-icons:resume-16" class="size-8 mr-2" />Resume</a
      >
    </div>
    <div class="text-5xl my-4">Projects</div>
    <div class="flex flex-col justify-center gap-4">
      <div
        class="flex flex-col items-center justify-center rounded-2xl bg-zinc-700 hover:bg-zinc-600 p-5 border border-zinc-400 max-w-[500px]"
      >
        <div class="font-bold text-3xl">SkyTrack</div>
        <a
          href="https://skytrack.jakegreen.dev"
          target="_blank"
          class="text-blue-400 hover:text-blue-300"
          >skytrack.jakegreen.dev</a
        >

        <div>Stack</div>
        <div class="flex items-center gap-2">
          <Icon icon="simple-icons:vuedotjs" class="size-9" />
          <Icon icon="simple-icons:typescript" class="size-9" />
          <Icon icon="simple-icons:tailwindcss" class="size-9" />
        </div>
        <div class="mt-2">Tools</div>
        <div class="flex items-center gap-2">
          <Icon icon="simple-icons:vite" class="size-7" />
          <Icon icon="simple-icons:git" class="size-7" />
          <Icon icon="simple-icons:github" class="size-7" />
          <Icon icon="simple-icons:vercel" class="size-7" />
        </div>
        <div class="flex text-wrap text-center mt-2">
          A RESTful flight tracker built with Vue, TypeScript, and Tailwind CSS. Uses Axios for API
          calls, Pinia for state management, and displays real-time AviationStack data in a clean
          UI. Hosted on Vercel.
        </div>
        <a
          href="https://github.com/jakeg96/skytrack"
          target="_blank"
          class="text-blue-400 hover:text-blue-300"
          >github.com/jakeg96/skytrack</a
        >
      </div>

      <div
        class="flex flex-col items-center rounded-2xl bg-zinc-700 hover:bg-zinc-600 p-5 border border-zinc-400 max-w-[500px]"
      >
        <div class="font-bold text-3xl">PC</div>
        <a href="https://pc.jakegreen.dev" target="_blank" class="text-blue-400 hover:text-blue-300"
          >pc.jakegreen.dev</a
        >

        <div>Stack</div>
        <div class="flex items-center gap-2">
          <Icon icon="simple-icons:vuedotjs" class="size-9" />
          <Icon icon="simple-icons:typescript" class="size-9" />
          <Icon icon="simple-icons:tailwindcss" class="size-9" />
        </div>
        <div class="mt-2">Tools</div>
        <div class="flex items-center gap-2">
          <Icon icon="simple-icons:vite" class="size-7" />
          <Icon icon="simple-icons:git" class="size-7" />
          <Icon icon="simple-icons:github" class="size-7" />
          <Icon icon="simple-icons:vercel" class="size-7" />
        </div>
        <div class="flex text-wrap text-center mt-2">
          A personal project loosely based on the Apple Lisa PC.
        </div>
        <a
          href="https://github.com/jakeg96/pc"
          target="_blank"
          class="text-blue-400 hover:text-blue-300"
          >github.com/jakeg96/pc</a
        >
      </div>
    </div>
  </body>
</template>

<template>
  <div class="space-y-6">
    <NuxtImg
      src="/avatar.jpeg"
      alt="Andre Wijaya"
      class="ring-2 border ring-gray-200 border-gray-300 dark:ring-white/10 dark:border-gray-800 hover:ring-4 transition-all duration-300 bg-gray-200 dark:bg-gray-900 rounded-full h-12 w-12 sm:h-16 sm:w-16"
      sizes="48px sm:64px"
      placeholder
      format="webp"
    />
    <h1
      class="text-xl font-bold tracking-tight text-gray-800 dark:text-gray-100"
    >
      Hello!
    </h1>
    <div>
      <p class="text-gray-900 dark:text-gray-400">
        I'm Andre Wijaya, I work as a mobile developer from Jakarta, Indonesia.
        I specialize in building mobile applications, web applications and sites
        using:
      </p>
      <ul
        class="text-gray-900 dark:text-gray-400 text-sm grid grid-cols-2 list-disc px-4"
      >
        <div>
          <li>Flutter</li>
          <li>Vue</li>
          <li>React</li>
          <li>React Native</li>
        </div>
        <div>
          <li>NodeJs</li>
          <li>Golang</li>
          <li>Laravel</li>
          <li>CodeIgniter</li>
        </div>
      </ul>
    </div>

    <p class="text-gray-900 dark:text-gray-400">
      By day, I'm a Front End Engineer at
      <a href="https://sahamrakyat.com" target="_blank" class="underline"
        >Saham Rakyat</a
      >, and by night (and weekends), I'm busy tinkering with some random tool
      or app that I am building.
    </p>
  </div>
</template>

<script setup>
useSeoMeta({
  title: "Andre Wijaya",
  description:
    "I'm Andre, your friendly neighborhood software engineer from Jakarta, Indonesia. I specialize in building mobile applications, web applications and sites using Vue, React, and Flutter.",
});
</script>

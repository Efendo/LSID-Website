<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <nav class="bg-white drop-shadow-md flex">
    <img class="w-16 h-32 lg:w-32 lg:h-32 my-auto lg:m-4" src="./assets/lsid.svg" />
    <div class=" grid grid-cols-8  gap-2 lg:gap-0">
    <RouterLink class="text-center my-auto p-9 mr-8 lg:mr-0 text-[0.8rem] lg:text-[1rem] font-bold active:bg-gray-300 lg:hover:bg-gray-200" to="/">Home</RouterLink>
    <RouterLink class="text-center my-auto text-[0.8rem] mx-4 lg:mx-0 p-9 lg:text-[1rem] font-bold active:bg-gray-300 lg:hover:bg-gray-200" to="/about">About</RouterLink>
  </div>
  </nav>
  <RouterView />
</template>
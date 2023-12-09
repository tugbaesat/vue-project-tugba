<script setup>
import { RouterLink, RouterView } from "vue-router";
</script>

<template>
  <header
    class="bg-white border-gray-200 dark:bg-gray-900 flex justify-between px-6"
  >
    <div class="flex items-center p-4">
      <img
        alt="Vue logo"
        class="flex items-center space-x-3 rtl:space-x-reverse w-1/3"
        src="@/assets/logo.png"
        width="125"
        height="125"
      />
    </div>

    <div class="">
      <ul class="font-medium flex p-4 gap-4 mt-4 bg-white dark:bg-gray-900">
        <li
          class="hover:bg-transparent border-0 hover:text-blue-700 p-0 text-gray-900 dark:text-white dark:hover:text-blue-500 dark:hover:bg-transparent"
        >
          <RouterLink to="/" class="">Home</RouterLink>
        </li>
        <li
          class="hover:bg-transparent border-0 hover:text-blue-700 p-0 text-gray-900 dark:text-white dark:hover:text-blue-500 dark:hover:bg-transparent"
        >
          <RouterLink to="/about">About</RouterLink>
        </li>
      </ul>
    </div>
  </header>
  <RouterView />
</template>

<script setup>
import GeneralContent from "../components/GeneralContent.vue";
import SectionOne from "../components/SectionOne.vue";
import SectionTwo from "../components/SectionTwo.vue";
</script>

<template>
  <main class="bg-white dark:bg-gray-900" >
    <GeneralContent />
    <section class="flex flex-col items-center text-center md:justify-evenly md:flex-row">
      <SectionOne />
      <SectionTwo />
    </section>
  </main>
</template>


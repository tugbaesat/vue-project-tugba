<script setup>
import GeneralContent from "../components/GeneralContent.vue";
import SectionOne from "../components/SectionOne.vue";
import SectionTwo from "../components/SectionTwo.vue";
</script>

<template>
  <main class="bg-white dark:bg-gray-900" >
    <GeneralContent />
    <section class="flex justify-center text-center md:justify-evenly">
      <SectionOne />
      <SectionTwo />
    </section>
  </main>
</template>


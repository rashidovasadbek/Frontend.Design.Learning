<template>
  <div class="mt-[160px] grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-5 xl:grid-cols-5 gap-y-10 gap-x-4 place-items-center">

    <location-card v-for="location in locationsCount"/>
  </div>
</template>
<script setup lang="ts">
import LocationCard from "@/modules/locations/companents/LocationCard.vue";

const locationsCount = 30;
</script>
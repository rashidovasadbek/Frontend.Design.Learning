<template>

  <div class="fixed w-full top-0 pt-2 mt-20 z-10 bg-white  flex items-center justify-center gap-4 content-padding">

        <!-- Location previous pagination -->
        <div class="md-3">
          <button class="border border-borderSecondary h-8 w-8 flex items-center justify-center rounded-full shadow-md">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32" aria-hidden="true" role="presentation" focusable="false"
                 style="display: block; fill: none; height: 12px; width: 12px; stroke: currentcolor; stroke-width: 5.33333; overflow: visible;">
              <path fill="none" d="M20 28 8.7 16.7a1 1 0 0 1 0-1.4L20 4"></path>
            </svg>
          </button>
        </div>

        <!-- Locations categories -->
        <div class="flex gap-6 md:gap-12 overflow-x-scroll no-scrollbar">

          <div class="h-[80px] select-common group min-w-[50px] flex flex-col justify-center items-center relative">
            <img class="h-[24px] w-[24px] mb-2 select-logo-img  select-transition"
                 src="https://a0.muscache.com/pictures/1b6a8b70-a3b6-48b5-88e1-2243d9172c06.jpg"
                 alt="Location selection icon">
            <h5 class="text-xs font-medium select-text select-transition">Castles</h5>
            <div class="mt-[10px] w-4/5 h-[2px] select-item select-transition"></div>
          </div>

          <div class="h-[80px] select-common group min-w-[50px] flex flex-col justify-center items-center relative">
            <img class="h-[24px] w-[24px] mb-2 select-logo-img  select-transition"
                 src="https://a0.muscache.com/pictures/4221e293-4770-4ea8-a4fa-9972158d4004.jpg"
                 alt="Location selection icon">
            <h5 class="text-xs font-medium select-text select-transition">Caves</h5>
            <div class="mt-[10px] w-4/5 h-[2px] select-item select-transition"></div>
          </div>

          <div class="h-[80px] select-common group min-w-[50px] flex flex-col justify-center items-center relative">
            <img class="h-[24px] w-[24px] mb-2 select-logo-img  select-transition"
                 src="https://a0.muscache.com/pictures/ee9e2a40-ffac-4db9-9080-b351efc3cfc4.jpg"
                 alt="Location selection icon">
            <h5 class="text-xs font-medium  select-text select-transition">Tropical</h5>
            <div class="mt-[10px] w-4/5 h-[2px] select-item select-transition"></div>
          </div>

          <div class="h-[80px] select-common group min-w-[50px] flex flex-col justify-center items-center relative">
            <img class="h-[24px] w-[24px] mb-2 select-logo-img  select-transition"
                 src="https://a0.muscache.com/pictures/4221e293-4770-4ea8-a4fa-9972158d4004.jpg"
                 alt="Location selection icon">
            <h5 class="text-xs font-medium  select-text select-transition">Amazing pools</h5>
            <div class="mt-[10px] w-4/5  h-[2px] select-item select-transition"></div>
          </div>

          <div class="h-[80px] select-common group min-w-[50px] flex flex-col justify-center items-center relative">
            <img class="h-[24px] w-[24px] mb-2 select-logo-img select-transition"
                 src="https://a0.muscache.com/pictures/957f8022-dfd7-426c-99fd-77ed792f6d7a.jpg"
                 alt="Location selection icon">
            <h5 class="text-xs font-medium  select-text select-transition">Surfing</h5>
            <div class="mt-[10px] w-4/5  h-[2px] select-item select-transition"></div>
          </div>

          <div class="h-[80px] select-common group min-w-[50px] flex flex-col justify-center items-center relative">
            <img class="h-[24px] w-[24px] mb-2 select-logo-img  select-transition"
                 src="https://a0.muscache.com/pictures/3271df99-f071-4ecf-9128-eb2d2b1f50f0.jpg"
                 alt="Location selection icon">
            <h5 class="text-xs font-medium  select-text select-transition">Tiny homes</h5>
            <div class="mt-[10px] w-4/5 h-[2px] select-item select-transition"></div>
          </div>

          <div class="h-[80px] select-common group min-w-[50px] flex flex-col justify-center items-center relative">
            <img class="h-[24px] w-[24px] mb-2 select-logo-img  select-transition"
                 src="https://a0.muscache.com/pictures/48b55f09-f51c-4ff5-b2c6-7f6bd4d1e049.jpg"
                 alt="Location selection icon">
            <h5 class="text-xs font-medium  select-text select-transition">Minsus</h5>
            <div class="mt-[10px] w-4/5 h-[2px] select-item select-transition"></div>
          </div>

          <div class="h-[80px] select-common group min-w-[50px] flex flex-col justify-center items-center relative">
            <img class="h-[24px] w-[24px] mb-2 select-logo-img  select-transition"
                 src="https://a0.muscache.com/pictures/d721318f-4752-417d-b4fa-77da3cbc3269.jpg"
                 alt="Location selection icon">
            <h5 class="text-xs font-medium select-text select-transition">Towers</h5>
            <div class="mt-[10px] w-4/5 h-[2px] select-item select-transition"></div>
          </div>

          <div class="h-[80px] select-common group min-w-[50px] flex flex-col justify-center items-center relative">
            <img class="h-[24px] w-[24px] mb-2 select-logo-img  select-transition"
                 src="https://a0.muscache.com/pictures/251c0635-cc91-4ef7-bb13-1084d5229446.jpg"
                 alt="Location selection icon">
            <h5 class="text-xs font-medium  select-text select-transition">Casas Practiculares</h5>
            <div class="mt-[10px] w-4/5 h-[2px] select-item select-transition"></div>
          </div>

          <div class="h-[80px] select-common group min-w-[50px] flex flex-col justify-center items-center relative">
            <img class="h-[24px] w-[24px] mb-2 select-logo-img  select-transition"
                 src="https://a0.muscache.com/pictures/31c1d523-cc46-45b3-957a-da76c30c85f9.jpg"
                 alt="Location selection icon">
            <h5 class="text-xs font-medium  select-text select-transition">Compers</h5>
            <div class="mt-[10px] w-4/5 h-[2px] select-item select-transition"></div>
          </div>

          <div class="h-[80px] select-common group min-w-[50px] flex flex-col justify-center items-center relative">
            <img class="h-[24px] w-[24px] mb-2 select-logo-img  select-transition"
                 src="https://a0.muscache.com/pictures/8e507f16-4943-4be9-b707-59bd38d56309.jpg"
                 alt="Location selection icon">
            <h5 class="text-xs font-medium  select-text select-transition">Islands</h5>
            <div class="mt-[10px] w-4/5 h-[2px] select-item select-transition"></div>
          </div>

          <div class="h-[80px] select-common group min-w-[50px] flex flex-col justify-center items-center relative">
            <img class="h-[24px] w-[24px] mb-2 select-logo-img  select-transition"
                 src="https://a0.muscache.com/pictures/8b44f770-7156-4c7b-b4d3-d92549c8652f.jpg"
                 alt="Location selection icon">
            <h5 class="text-xs font-medium select-text select-transition">Arctic</h5>
            <div class="mt-[10px] w-4/5 h-[2px] select-item select-transition"></div>
          </div>

          <div class="h-[80px] select-common group min-w-[50px] flex flex-col justify-center items-center relative">
            <img class="h-[24px] w-[24px] mb-2 select-logo-img select-transition"
                 src="https://a0.muscache.com/pictures/c5a4f6fc-c92c-4ae8-87dd-57f1ff1b89a6.jpg"
                 alt="Location selection icon">
            <h5 class="text-xs font-medium  select-text select-transition">OMG!</h5>
            <div class="mt-[10px] w-4/5 h-[2px] select-item select-transition"></div>
          </div>

        </div>

        <!-- Location next pagination -->
        <div class="md-3">
          <button class="border border-borderSecondary h-8 w-8 flex items-center justify-center rounded-full shadow-md">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32" aria-hidden="true" role="presentation " focusable="false"
                 style="display: block; fill: none; height: 12px; width: 12px; stroke: currentcolor; stroke-width: 5.33333; overflow: visible;">
              <path
                  fill="none" d="m12 4 11.3 11.3a1 1 0 0 1 0 1.4L12 28"></path>
            </svg>
          </button>
        </div>

        <!-- Filters actions -->
        <div class="w-[500px] hidden lg:flex items-center justify-center pb-3">

          <!-- Locations filter -->
          <button class="ml-3 flex group h-12 w-auto px-4 border border-borderSecondary justify-center items-center rounded-lg gap-3">
            <svg class="text-textSecondary select-text" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 32 32" aria-hidden="true"
                 role="presentation"
                 focusable="false"
                 style="display: block; fill: none; height: 16px; width: 16px; stroke: currentcolor; stroke-width: 4; overflow: visible;">
              <path fill="none"
                    d="M7 16H3m26 0H15M29 6h-4m-8 0H3m26 20h-4M7 16a4 4 0 1 0 8 0 4 4 0 0 0-8 0zM17 6a4 4 0 1 0 8 0 4 4 0 0 0-8 0zm0 20a4 4 0 1 0 8 0 4 4 0 0 0-8 0zm0 0H3"></path>
            </svg>
            <span>Filters</span>
          </button>

          <button class="ml-3 flex group h-12 w-auto px-4 border border-borderSecondary justify-center items-center rounded-lg gap-3">
            <span class="text-xs font-medium whitespace-nowrap">Display total before taxes</span>
          </button>

        </div>

  </div>

</template>
<script setup lang="ts">
</script>
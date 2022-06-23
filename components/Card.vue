<template>
  <div
    class=" text-violet-500 w-[344px] sm:w-[400px] md:w-[344px] xl:w-[300px] box  mt-5 rounded animate-pulse"
  >
    <div class="p-1">
      <img
        src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg"
        class="w-full"
      />
    </div>
    <div class="px-1 py-2 ">
      <div>Lorem ipsum color</div>
      <div></div>
    </div>
  </div>
</template>

<script setup></script>

<style scoped>
.box {
  animation: bcani 2s cubic-bezier(0.4, 0, 0.6, 1) infinite;
}

@keyframes bcani {
  0% {
    border: 1px solid rgb(0, 164, 134);
  }
  25 % {
    border: 1px solid rgb(8, 163, 70);
  }
  50% {
    border: 1px solid rgb(108, 3, 108);
  }
  75% {
    border: 1px solid rgb(194, 6, 122);
  }
  100% {
    border: 1px solid rgb(0, 164, 134);
  }
}
</style>

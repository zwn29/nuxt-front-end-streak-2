<template>
  <div
    class="fixed  w-full bl-blur select-none  flex justify-between text-violet-500  box "
  >
    <div class=" mx-10 my-5  px-3 rounded">
      <span class="cursor-pointer">Home</span>
    </div>
    <div class="flex">
      <div class="mx-10 my-5"><span class="cursor-pointer">About</span></div>
      <div class="mx-10 my-5"><span class="cursor-pointer">login</span></div>
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
    border-bottom: 1px solid rgb(0, 164, 134);
  }
  25 % {
    border-bottom: 1px solid rgb(8, 163, 70);
  }
  50% {
    border-bottom: 1px solid rgb(108, 3, 108);
  }
  75% {
    border-bottom: 1px solid rgb(194, 6, 122);
  }
  100% {
    border-bottom: 1px solid rgb(0, 164, 134);
  }
}

.bl-blur {
  -moz-background-filter: blur(10px) !important;
  -webkit-backdrop-filter: blur(10px) !important;
  backdrop-filter: blur(10px);
  background: rgba(0, 0, 0, 0.2);
}
</style>

<template>
  <div
    class="grid pt-14  sm:grid-cols-1 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 w-full place-items-center"
  >
    <div v-for="n in 9">
      <Card />
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>

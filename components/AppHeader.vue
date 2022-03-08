<template>
  <header class="h-30 py-4 lg:py-8 text-center">
    <h1 class="text-4xl md:text-6xl lg:text-8xl">This is a Generic Header</h1>
    <img v-if="image" :src="image" alt="This will be an image" />
  </header>
</template>
<script setup></script>

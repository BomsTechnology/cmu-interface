<script setup>
const props = defineProps({
  title: String
})
</script>

<template>
<div class="w-full bg-gray-100 p-8 text-center">
    <h1 class="text-4xl font-extralight">{{ title}}</h1>
</div>
</template>
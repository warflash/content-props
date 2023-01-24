<template>
  <NuxtLink>
    <span v-html="props.text"> </span>
  </NuxtLink>
</template>

<script setup>
const props = defineProps({
  text: String,
});
</script>

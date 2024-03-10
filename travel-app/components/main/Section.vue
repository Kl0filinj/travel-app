<script setup lang="ts">
const { gap } = defineProps({
  gap: {
    type: Number,
    required: false,
    default: 10,
  },
});
</script>

<template>
  <section :class="`mb-${gap}`">
    <slot></slot>
  </section>
</template>

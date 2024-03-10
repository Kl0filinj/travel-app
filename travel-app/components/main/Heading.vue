<script setup lang="ts">
const { size } = defineProps({
  size: {
    type: Number,
    required: true,
  },
});
</script>

<template>
  <p :class="`text-${size}xl font-bold`">
    <slot></slot>
  </p>
</template>

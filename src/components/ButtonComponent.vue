<template>
  <q-btn :color="color" :label="label" :size="size" :no-caps="noCaps" />
</template>

<script setup lang="ts">
defineProps<{
  color: string;
  label: string;
  size: string;
  noCaps: boolean;
}>();
</script>

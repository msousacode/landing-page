<template>
  <q-expansion-item expand-separator :label="label" class="text-body1 text-bold">
    <q-card>
      <q-card-section class="text-body1">
        Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quidem, eius reprehenderit eos
        corrupti commodi magni quaerat ex numquam, dolorum officiis modi facere maiores architecto
        suscipit iste eveniet doloribus ullam aliquid.
      </q-card-section>
    </q-card>
  </q-expansion-item>
</template>
<script setup lang="ts">
defineProps<{
  label: string;
}>();
</script>

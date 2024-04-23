<script lang="ts" setup>
defineOptions({
  name: 'BaseCard',
});
</script>

<template>
  <template>
    <UCard>
      <template #header>
        Card header
      </template>

      Card body

      <template #footer>
        Card footer
      </template>
    </UCard>
  </template>
</template>

<script lang="ts" setup>
defineProps({
  icon: {
    type: String,
    default: '',
  },
})
</script>

<template>
  <div>
    <h2 class="fancy-header">
      <ContentSlot :use="$slots.default" unwrap="p" />
    </h2>
  </div>
</template>

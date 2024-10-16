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
    <h3>
      <ContentSlot name="title" />
    </h3>
    <span>
      <ContenSlot name="description" />
    </span>
  </div>
</template>

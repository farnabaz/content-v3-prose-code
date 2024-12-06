<script setup lang="ts">
const route = useRoute()
const { data} = await useAsyncData('content', () => {
  return queryCollection('content').path(route.path).first()
})
</script>

<template>
  <main class="prose prose-invert">
    <ContentRenderer v-if="data" :value="data" />
  </main>
</template>

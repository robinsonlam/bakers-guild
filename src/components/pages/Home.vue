<script setup lang="ts">
import { ref, onMounted } from 'vue'
import { useRoute } from 'vue-router'

// `mounted` is a lifecycle hook which we will explain later
onMounted(() => {
  const route = useRoute();
  console.log(route.params.id);
  console.log("Hmm")
})
</script>

<template>
  <div>
    <p>This is the home page</p>
  </div>
</template>
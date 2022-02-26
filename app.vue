<template>
  <div>
    <h1>Oh yeah!</h1>
  </div>
</template>
<script setup>
import { ref, onMounted } from "vue";

const title = ref("");

onMounted(() => {
  title.value = "Updated!";
});
</script>

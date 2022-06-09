<script setup>
defineProps({
  image: String,
});
</script>

<template>
  <a><img :src="image" /></a>
</template>

<style scoped>
a {
  color: #42b983;
}
</style>

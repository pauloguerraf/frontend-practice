<script setup>
import Logo from "./Logo.vue";
import logoImage from "../assets/logo.svg";

defineProps({
  items: [Object],
});
</script>

<template>
  <div class="flex">
    <Logo :image="logoImage" />
    <ul class="flex gap-2 list-none text-xl">
      <li v-for:item="item in items">
        <a :href="item.href">{{ item.text }}</a>
      </li>
    </ul>
  </div>
</template>

<style></style>

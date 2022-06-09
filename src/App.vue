<script setup>
import PrimaryNavigation from "./components/PrimaryNavigation.vue";

const items = [
  {
    text: "Home",
    href: "/",
  },
  {
    text: "About",
    href: "/",
  },
  {
    text: "Contact",
    href: "/",
  },
];
</script>

<template>
  <PrimaryNavigation :items="items" />
</template>

<style></style>

<script setup lang="ts">
import { useDark, usePreferredDark } from "@vueuse/core";

const isPrefferedDark = usePreferredDark();

useDark({
  attribute: "theme",
  initialValue: isPrefferedDark ? "dark" : "light",
});
</script>

<template></template>

<style scoped></style>

<script setup lang="ts">
import { RouterView } from "vue-router";
</script>

<template>
  <img src="@/assets/bg-image.png" alt="" id="background-image" />
  <RouterView />
</template>

<style>
@import "@/assets/base.css";
#background-image {
}
</style>

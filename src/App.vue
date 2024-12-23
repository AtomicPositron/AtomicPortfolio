<script setup>
import {RouterView, RouterLink} from "vue-router";
</script>

<template>
  <div class="flex gap-60 flex-row">
  <div class="nav">
    <RouterLink to="/">Home</RouterLink>
  </div>
  <RouterView />
  </div>
</template>

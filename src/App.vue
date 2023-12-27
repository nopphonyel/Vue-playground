<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import AsideLayout from './layouts/AsideLayout.vue'
</script>

<template>
  <AsideLayout>
    <RouterView />
  </AsideLayout>
</template>
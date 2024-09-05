<script setup lang="ts">
import { useId } from "vue";
import { ConfigProvider } from "radix-vue";
</script>

<template>
  <ConfigProvider :use-id="useId">
    <NuxtRouteAnnouncer />
    <LayoutDarkModeToggle />
  </ConfigProvider>
</template>

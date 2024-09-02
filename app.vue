<script setup lang="ts">
import { ConfigProvider } from "radix-vue";

const useId = () => useId;
</script>

<template>
  <ConfigProvider :use-id="useId">
    <div>
      <NuxtRouteAnnouncer />
      <LayoutDarkModeToggle />
    </div>
  </ConfigProvider>
</template>

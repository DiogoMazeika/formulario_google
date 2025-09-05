<script setup lang="ts">
import { RouterLink } from "vue-router";

const emit = defineEmits<{
  teste: [id: number];
}>();
// @click="$emit('teste', '/')"
</script>

<template>
  <div class="flex py-4 px-2 mb-8 bg-white rounded-md shadow-2xl">
    <RouterLink
      class="mx-3 px-2 py-2 cursor-pointer rounded-md hover:bg-slate-700 hover:text-white active:p-1 active:mx-4 active:my-1 active:bg-slate-900 active:text-white"
      to="/"
    >
      Início
    </RouterLink>
    <RouterLink
      class="mx-3 px-2 py-2 cursor-pointer rounded-md hover:bg-slate-700 hover:text-white active:p-1 active:mx-4 active:my-1 active:bg-slate-900 active:text-white"
      to="/lista"
    >
      Lista
    </RouterLink>
    <RouterLink
      class="ml-auto mr-3 px-2 py-2 cursor-pointer rounded-md hover:bg-slate-700 hover:text-white active:p-1 active:mr-4 active:my-1 active:bg-slate-900 active:text-white"
      to="/about"
    >
      Sobre
    </RouterLink>
  </div>
</template>

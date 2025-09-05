<script setup lang="ts">
import { RouterView } from "vue-router";
import NavBar from "./components/NavBar.vue";

// const teste = (id: number) => (count.value = id);
// console.log(`asdasd ${count.value}`);
</script>

<template>
  <div class="w-full">
    <NavBar @teste="teste" />
    <div>{{ count }}</div>
    <RouterView />
  </div>
  <!-- <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" /> -->

  <!-- <div class="wrapper">
      <HelloWorld msg="You did it!" />

      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about" class="font-bold">About</RouterLink>
        <RouterLink to="/lista">Lista</RouterLink>
      </nav>
    </div>
  </header> -->

  <!-- <RouterView /> -->
</template>

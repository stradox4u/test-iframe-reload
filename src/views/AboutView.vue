<script setup>
import AppLayout from "./AppLayout.vue";
</script>

<template>
  <app-layout>
    <template #bodySlot>
      <h2>I'm an about page!</h2>
    </template>
  </app-layout>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>

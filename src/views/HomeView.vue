<script setup>
import AppLayout from './AppLayout.vue';
</script>

<template>
  <main>
    <app-layout>
      <template #bodySlot>
        <h2>This is the home view!</h2>
      </template>
    </app-layout>
  </main>
</template>

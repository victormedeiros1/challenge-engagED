<script setup lang="ts"></script>

<template>
  <q-layout>
    <q-page-container class="container">
      <q-page class="full-width">
        <RouterView />
      </q-page>
    </q-page-container>
  </q-layout>
</template>

<style lang="scss" scoped>
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  max-width: 71.25rem;
  margin: 0 auto;
  padding: 1.25rem;
}
</style>

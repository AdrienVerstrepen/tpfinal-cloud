<script setup lang="ts">
  const buildId = import.meta.env.VITE_BUILD_ID ?? 'local'
  const today = new Date().toLocaleDateString('fr-FR')
</script>
<template>
  <header>
    <p>Nom : Adrien Verstrepen</p>
    <p>Date : {{ today }}</p>
    <p>Build : {{ buildId }}</p>
  </header>
</template>
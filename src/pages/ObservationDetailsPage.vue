<template>
  <q-page class="q-pa-md">
    <h1 class="text-h5">Detalji opažanja</h1>
    <p>Ovdje će biti prikaz pojedinog opažanja.</p>
    <div>
      Ova stranica prikazuje pojedino opažanje. Možete birati koje opažanje želite da se prikaže.
    </div>
    <p>ID opažanja: {{ route.params.id }}</p>
  </q-page>
</template>

<script setup>
import { useRoute } from 'vue-router';
const route = useRoute();
</script>


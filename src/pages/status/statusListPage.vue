<script setup lang="ts">
import { DefaultTemplate } from '@/template'
const ItensDaTabela = [
  {
    name: 'Teste 1',
    species: 'Loxodonta africana',
    diet: 'Herbivore',
    habitat: 'Savanna, Forests'
  },
  {
    name: 'Teste 2',
    species: 'Loxodonta africana',
    diet: 'Herbivore',
    habitat: 'Savanna, Forests'
  },
  {
    name: 'Teste 3',
    species: 'Loxodonta africana',
    diet: 'Herbivore',
    habitat: 'Savanna, Forests'
  }
]
</script>

<!-- encapsular codigo -->
<template>
  <default-template>
    <v-data-table :items="ItensDaTabela"></v-data-table>
  </default-template>
</template>

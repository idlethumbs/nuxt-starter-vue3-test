<template>
  <div class="p-4 space-y-6">
    <div>Homepage</div>
    <Badge label="" />
    <HomeCard />
  </div>
</template>

<script setup lang="ts">
// AFTER you have completed the tasks in Badge.vue:
// 1. Create a PokeList component that:
// a) shows a card style item for each pokemon, define types for props.
// b) use a layout of your choice that displays all the information for each pokemon
// c) The pokemon `types` should use the badges and badge colours we have defined.

const pokemon = [
  {
    name: 'Squirtle',
    types: ['water'],
    id: '0007',
  },
  {
    name: 'Rattata',
    types: ['normal'],
    id: '0019',
  },
  {
    name: 'Charmeleon',
    types: ['fire'],
    id: '0005',
  },
  {
    name: 'Blastoise',
    types: ['water'],
    id: '0009',
  },
];
</script>

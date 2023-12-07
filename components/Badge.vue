<template>
  <span
    class="
      bg-gray-50
      ring-gray-500/10
      text-gray-600
      inline-flex
      items-center
      rounded-full
      px-2
      py-1
      text-xs
      font-medium
      ring-1 ring-inset
      mx-2
    "
  >
    label
  </span>
</template>

<script setup lang="ts">
import { ref } from 'vue';

interface PillProps {
  label: string;
}

const props = withDefaults(defineProps<PillProps>(), {
  label: undefined,
});
</script>

<!-- 
1. Make label customisable.
2. Add an optional color prop, accept 'gray', 'red', 'blue' values and default to 'gray'
3. Utilise the color prop such that:
A) All badges use the base classes: 
'inline-flex items-center rounded-full px-2 py-1 text-xs font-medium ring-1 ring-inset mx-2'
B) 
- 'gray' badges use the classes: 'bg-gray-50 ring-gray-500/10 text-gray-600'
- 'red' = 'bg-red-50 ring-red-500/10 text-red-600'
- 'blue' = 'bg-blue-50 ring-blue-500/10 text-blue-700'
C) add all three colour variants of the badge to the page.
-->

<template>
  <child-component v-slot="slotProps">
    Now we can use the data from the child component here: {{ slotProps.example }}
  </child-component>
</template>

<script setup>
import ChildComponent from './components/ChildComponent.vue'
</script>

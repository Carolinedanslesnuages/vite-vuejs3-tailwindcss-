<template>
  
  <h1 class="text-gray-500  text-3xl  font-bold  ">{{ msg }}</h1>

</template>
<script setup>
import { defineProps } from 'vue'

defineProps({
  msg: String
})

</script>
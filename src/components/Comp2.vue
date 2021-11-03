<script setup lang="ts">
import { ref } from 'vue'

defineProps({
  msg: String, show: Boolean
})

</script>

<template>
  <h1 v-if="show">{{ msg }}</h1>
</template>

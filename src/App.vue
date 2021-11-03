<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import Comp1 from './components/Comp1.vue'
import Comp2 from './components/Comp2.vue'
</script>

<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <Comp1 msg="ts泛型定义Props显示了" show />
  <Comp2 msg="js定义Props显示了" show />
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

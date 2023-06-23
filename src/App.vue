<script setup lang="ts">
// No problem for axios
import axios from 'axios'
// > Cannot find module 'highcharts' or its corresponding type declarations. ts(2307)
import highcharts from 'highcharts'

console.log(axios)
// To exclude the following TypeScript Error
// > 'highcharts' is declared but its value is never read. ts(6133)
console.log(highcharts)
</script>

<template>
  <div></div>
</template>

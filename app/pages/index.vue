<template>
  <div>
    <h1>Hello World wow</h1>
    <v-btn>Submit</v-btn>
  </div>
</template>

<script lang="ts" setup>
//@ts-nocheck
definePageMeta({
  middleware: 'auth'
})

</script>

<style>

</style>
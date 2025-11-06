<template>
  <div style="color: #000; font-size: 16px">
    <h1>test</h1>
  </div>
</template>

<script setup lang="ts">
const name: string = 'testDemo'
const creatTime = new Date().toISOString()
// name = 123
console.log(name, creatTime)
</script>

<style scoped>
div {
  color: #000;
}

h1 {
  font-weight: bold;
  font-size: 20px;
  display: flex;
  display: inline-block;
  color: #000;
  width: 100%;
  width: 200px;
}
</style>

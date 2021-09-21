<script setup>
defineProps({
  msg: String
})

</script>

<template>
  <h1>{{ msg }}</h1>
  <button type="button" @click="$emit('logout')">Logout</button>
</template>

<style scoped>
a {
  color: #42b983;
}
</style>

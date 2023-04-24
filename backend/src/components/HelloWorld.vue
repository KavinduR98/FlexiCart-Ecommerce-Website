<script setup>
import { ref} from 'vue'
import store from '../store';

const test = computed(() => store.state.test)

</script>

<template>
  <h1>Hi Kavindu Ushan</h1>
  <h2>{{test}}</h2>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>

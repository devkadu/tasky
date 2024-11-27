<script lang="ts" setup>
import type { Input } from '@/types/inputTypes'

// Define as props usando `defineProps` com a tipagem importada
const props = defineProps<Input>()
</script>

<template>
  <div class="input-wrapper">
    <!-- Usa a prop `placeholder` no input -->
    <input :type="props.type" :placeholder="props.placeholder" />
  </div>
</template>

<style scoped>
.input-wrapper {
  width: 400px;
  height: 48px;
  border: 1px solid lightgray;
  border-radius: 4px;
  display: flex;
  justify-content: center;
}

input {
  width: 90%;
  padding: 8px;
  border: none;
  outline: none;
}
</style>

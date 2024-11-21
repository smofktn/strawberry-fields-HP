<script setup lang="ts"></script>
<template>
  <div class="spin-container">
    <slot name="spin"></slot>
  </div>
</template>
<style scoped>
.spin-container {
  animation: spin 2s linear infinite;
}
@keyframes spin {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}
</style>

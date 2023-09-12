<script setup lang="ts"></script>

<template>
  <button class="button" type="button">
    <slot></slot>
  </button>
</template>

<style scoped>
.button {
  cursor: pointer;
  background-color: #555555;
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  border-radius: 6px;
}

.button:hover {
  background-color: #444444;
}
</style>

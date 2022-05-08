<script setup>
const color = useColor() // Same as useState('color')
</script>

<template>
  <div>
    Color: {{ color }}
    <button @click="color='blue'">
      Blue
    </button>
  </div>
</template>
<template>
  <svg 
    :class="`icon--${size}`"
    class="icon fill-current"
    viewBox="0 0 16 16"
  >
    <g><path d="M10.707,5.293A1,1,0,0,0,9.293,6.707L11.586,9H6A3,3,0,0,1,6,3h7a1,1,0,0,0,0-2H6A5,5,0,0,0,6,11h5.586L9.293,13.293a1,1,0,1,0,1.414,1.414l4-4a1,1,0,0,0,0-1.414Z"></path></g>
  </svg>
</template>

<script setup>
const props = defineProps({
  size: {
    type: String,
    default: 'sm'
  }
})
</script>

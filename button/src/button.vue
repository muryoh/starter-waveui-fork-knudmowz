<template>
  <w-button :bg-color="color" color="white">Button</w-button>
</template>

<script>
  export default {
    props: {
      color: { type: String, default: 'green' }
    }
  }
</script>
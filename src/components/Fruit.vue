<template>
  <li>{{ name }}</li>
</template>

<script>
export default {
  props: {
    name: {
      type: String,
      dafault: ''
    }
  }
}
</script>

<style lang="scss">
  h1 {
    color: red !important;
  }
</style>

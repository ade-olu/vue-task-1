<template>
  <div class="my-name">
    <h1>{{ name }}</h1>
  </div>
</template>

<script>
export default {
  name: 'MyName',
  props: {
    name: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>

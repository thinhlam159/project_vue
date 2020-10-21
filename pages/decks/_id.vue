<template>
  <h1>Your deck {{ $route.params.id }} is actives</h1>
</template>

<script>
  export default {
    name: "_id",
    validate(context) {
      // console.log(context);
      return /^[0-9]{9,12}$/.test(context.params.id)
    }
  }
</script>

<style scoped>

</style>

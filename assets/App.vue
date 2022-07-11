<template>
  <div>
    <h2>Welcome to Notes App</h2>
  </div>
</template>

<script>
export default {
  data() {
    return {
      count: 1
    }
  },
  mounted() {
    console.log(this.count)
    this.count = 2
  }
}
</script>

<style>

</style>
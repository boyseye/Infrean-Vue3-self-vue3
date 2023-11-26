<template>
  <div></div>
</template>

<script>
export default {
  data() {
    return {
      counter: 0
    }
  },

  methods: {
    increment() {
      this.counter++
    }
  },

  mounted() {
    console.log('mounted')
  }
}
</script>

<style lang="scss" scoped></style>

<template>
  <button @click="helloWorld">Greet</button>
</template>

<script>
export default {
  data() {
    return {
      greet: 'Hello World!'
    }
  },
  methods: {
    helloWorld() {
      alert(this.greet)
      console.log(this.greet)
    }
  }
}
</script>

<style>

</style>
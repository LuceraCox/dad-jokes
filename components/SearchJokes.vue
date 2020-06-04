<template>
  <form @submit.prevent="OnSubmit">
    <input v-model="text" type="text" placeholder="Search Jokes..." />
    <input type="submit" value="Search Jokes" />
  </form>
</template>

<script>
export default {
  name: 'SearchJokes',
  data() {
    return {
      text: ''
    }
  },
  methods: {
    OnSubmit() {
      this.$emit('search-text', this.text)
      this.text = ''
    }
  }
}
</script>

<style></style>

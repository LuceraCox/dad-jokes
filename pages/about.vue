<template>
  <div>
    <h1>About Dad Jokes</h1><br>
    <p>This app displays the best kind of jokes - corny dad jokes.<br><br> It was built using Nuxt JS, a higher
      level framework for Vue.JS. This was my first time setting up a nuxt project, including the file structure and
      routing for my different pages and identifying the necessary data fields.I utilized axios calls and
      jquery functions to get and return information for an existing dad jokes api. I also added a search functionality,
      allowing a user to look for a joke containing specific words.</p>
  </div>
</template>
<script>
  export default {
    head() {
      return {
        title: 'About The App',
        meta: [
          {
            hid: 'description',
            name: 'description',
            content: 'Best place for corny dad jokes'
          }
        ]
      }
    }
  }
</script>

<style></style>

<template>
  <div>
    this is about page.
    {{ title }}
  </div>
</template>

<script>
export default {

  middleware: 'test',
  asyncData () {
    return {
      title: 'About'
    }
  },

  head () {
    return {
      title: 'about',
      script: [
        {
          src: '/about.js'
        }
      ]
    }
  }
}
</script>

<style>

</style>

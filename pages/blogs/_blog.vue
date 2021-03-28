<template>
  <div>
    <h1>this blog page.</h1>
    <h2>{{ slug.blog }}</h2>
  </div>
</template>

<script>
export default {

  validate ({ params }) {
    return /^\d+$/.test(params.blog)
  },

  data () {
    return {
      slug: this.$route.params
    }
  }
  // created () {
  //   /* eslint-disable no-console */
  //   console.log(this.$route.params)
  // }
}
</script>

<style>

</style>

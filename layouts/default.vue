<template>
  <div>
    <v-toolbar>
      <v-toolbar-side-icon />
      <v-toolbar-title>Title</v-toolbar-title>
      <v-spacer />
      <v-toolbar-items class="hidden-sm-and-down">
        <v-btn flat>
          <nuxt-link to="/">
            Home
          </nuxt-link>
        </v-btn>
        <v-btn flat>
          <nuxt-link to="/about">
            About
          </nuxt-link>
        </v-btn>
        <v-btn flat>
          <nuxt-link to="/inspire">
            Inspire
          </nuxt-link>
        </v-btn>
      </v-toolbar-items>
    </v-toolbar>
    <nuxt />
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>

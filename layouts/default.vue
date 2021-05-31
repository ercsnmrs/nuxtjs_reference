<template>
  <v-app>
    <v-card color="grey lighten-4" flat tile>
      <v-toolbar dense>
        <v-app-bar-nav-icon></v-app-bar-nav-icon>

        <v-toolbar-title>Learning Nuxt</v-toolbar-title>

        <v-spacer></v-spacer>

        <v-btn text><nuxt-link to="/"> Home </nuxt-link></v-btn>

        <v-btn text> <nuxt-link to="/about"> About </nuxt-link></v-btn>

        <v-btn text> <nuxt-link to="/inspire"> Inspire </nuxt-link></v-btn>
      </v-toolbar>
    </v-card>

    <nuxt />
  </v-app>
</template>

<script>
export default {
  data() {
    return {}
  },
}
</script>

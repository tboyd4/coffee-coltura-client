<template>
  <v-app dark>
    <v-app-bar fixed app>
      <v-toolbar-title>Coffee Coltura</v-toolbar-title>
    </v-app-bar>
    <v-main>
      <nuxt />
    </v-main>

    <v-footer absolute app>
      <span>&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>
export default {}
</script>

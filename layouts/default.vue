<template>
  <v-app dark>
    <v-app-bar fixed app>
      <v-toolbar-title>
        <v-btn to="/">Coffee Coltura</v-btn>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn outlined class="app-bar-button" color="primary" to="/brewguides"
        >Brew Guides</v-btn
      >
      <v-btn outlined class="app-bar-button" color="primary" to="/beans"
        >Beans</v-btn
      >
      <v-btn outlined class="app-bar-button" color="primary" to="/journal"
        >Coffee Journal</v-btn
      >
      <v-btn outlined class="app-bar-button" color="primary" to="/settings"
        >Settings</v-btn
      >
    </v-app-bar>
    <v-main>
      <div class="my-10"></div>
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

<style lang="scss" scoped>
span {
  text-align: center;
  margin: 0px auto;
}
.app-bar-button {
  margin: 0px 5px;
}
</style>

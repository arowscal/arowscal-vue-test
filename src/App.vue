<template>
  <v-app>
    <v-navigation-drawer app v-model="drawer" clipped></v-navigation-drawer>
    <v-app-bar app clipped-left>
      <v-app-bar-nav-icon @click.stop="drawer = !drawer"></v-app-bar-nav-icon>
      <v-spacer></v-spacer>
      <v-btn class="ma-2 justify-end" to="/">Home</v-btn>
      <v-btn class="ma-2 justify-end" to="/about">About</v-btn>
    </v-app-bar>
    <v-content>
      <v-container fluid>
        <router-view></router-view>
      </v-container>
    </v-content>
    <v-footer app></v-footer>
  </v-app>
</template>

<script>
export default {
  name: "App",
  data: () => ({
    drawer: null
  })
};
</script>

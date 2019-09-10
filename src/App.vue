<template>
  <v-app>
  <v-navigation-drawer app>
  </v-navigation-drawer>
  <v-app-bar app>
    <v-btn class="ma-2" to="/">Home</v-btn>
    <v-btn class="ma-2" to="/about">About</v-btn>
  </v-app-bar>
  <v-content>
    <v-container fluid>
      <router-view></router-view>
    </v-container>
  </v-content>
  <v-footer app> 
  </v-footer>
</v-app>
</template>

<script>
import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
  data: () => ({
    
  }),
};
</script>

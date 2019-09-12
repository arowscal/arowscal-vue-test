<template>
  <v-container>
    <v-layout justify-center text-center wrap>
      <v-flex xs12>
        <h1 class="display-4">Welcome</h1>
      </v-flex>
      <v-flex xs3 mr-3>
        <v-card>
          <v-card-title primary-title>Log In</v-card-title>
          <v-card-text>I'm card text</v-card-text>
          <v-card-actions>
            <v-btn icon>
              <v-icon>mdi-heart</v-icon>
            </v-btn>
            <v-btn text>Click</v-btn>
            <v-btn outlined>Click</v-btn>
          </v-card-actions>
        </v-card>
      </v-flex>
      <v-flex xs3 ml-3>
        <v-card>
          <v-card-title primary-title>Sign Up</v-card-title>
          <v-card-text>I'm card text</v-card-text>
          <v-card-actions>
            <v-btn icon>
              <v-icon>mdi-heart</v-icon>
            </v-btn>
            <v-btn text>Click</v-btn>
            <v-btn outlined>Click</v-btn>
          </v-card-actions>
        </v-card>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
export default {
  data: () => ({})
};
</script>

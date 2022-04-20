<template>
  <v-container fill-height>
    <v-row align-content="center" justify="center">
      <v-col>
        <v-card>
          <v-title>Test</v-title>
          <v-card-content> Random card content </v-card-content>
          <v-card-actions class="justify-center">
            <router-link to="/" style="text-decoration: none; color: inherit">
              <v-btn text color="orange">Home</v-btn>
            </router-link>
          </v-card-actions>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  name: 'About',
};
</script>

<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
      Project 01
    </v-app-bar>

    <v-main>
      <MainComponent />
    </v-main>
  </v-app>
</template>

<script>
import MainComponent from './components/MainComponent';

export default {
  name: 'App',

  components: {
    MainComponent,
  },

  data: () => ({
    //
  }),
};
</script>

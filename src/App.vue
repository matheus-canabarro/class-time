<template>
  <v-app>
    <v-app-bar
      app
      light
    >
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-logo-light.png"
          transition="scale-transition"
          width="40"
        />

        <v-img
          alt="Vuetify Name"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="100"
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-name-light.png"
          width="100"
        />
      </div>

      <v-spacer></v-spacer>

      <v-btn
        to="/teste"
        text
      >
        <span class="mr-2">Teste</span>
        <v-icon>mdi-open-in-new</v-icon>
      </v-btn>

      <v-btn
        to="/home"
        text
      >
        <span class="mr-2">Home</span>
        <v-icon>mdi-open-in-new</v-icon>
      </v-btn>
    </v-app-bar>

    <v-main>
      <router-view></router-view>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  components: {
  },

  data: () => ({
    //
  })
}
</script>

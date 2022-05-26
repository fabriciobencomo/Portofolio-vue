<template>
  <v-app :style="{background: $vuetify.theme.themes.dark.background}">
    <NavBarComponent />
  </v-app>
</template>

<script>
  import NavBarComponent from '../components/NavBarComponent'

  export default {
    name: 'HomeView',

    components: {
    NavBarComponent,
    },
  }
</script>

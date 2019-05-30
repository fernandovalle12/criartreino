<template>
  <v-app>
    <v-toolbar
      style="background-color: #993399"
      :clipped-left="clipped"
      fixed
      app
    >
      <v-btn icon dark>
        <v-icon>keyboard_arrow_left</v-icon>
      </v-btn>
      <v-toolbar-title class="white--text">Criar Treino</v-toolbar-title>
    </v-toolbar>
    <v-content>
      <v-container>
        <nuxt />
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
export default {}
</script>

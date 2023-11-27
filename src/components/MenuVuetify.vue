<template>
    <v-card
      color="grey-lighten-4"
      flat
      rounded="0"
    >
      <v-toolbar density="compact">
        <v-app-bar-nav-icon></v-app-bar-nav-icon>
  
        <v-toolbar-title>Title</v-toolbar-title>
  
        <v-spacer></v-spacer>

        <v-btn to="/login" variant="outlined" color="pink-darken-4" text="Login"></v-btn>
      </v-toolbar>
    </v-card>
  </template>

<script>
export default {
  name: "MenuVuetify",
};
</script>

<style></style>
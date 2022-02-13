<template>
  <v-app>
    <v-toolbar
      app
      color="primary"
      class="white--text"
    >
      <v-toolbar-side-icon class="white--text"/>
      <v-toolbar-title>Title</v-toolbar-title>
    </v-toolbar>

    <v-content>
      <v-container>
      <nuxt/>
      </v-container>
    </v-content>

    <v-footer
      app
    >
      <span>Footer</span>
    </v-footer>
  </v-app>
</template>


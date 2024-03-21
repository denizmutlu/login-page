<template>
  <v-app theme="dark">
    <v-app-bar title="Application bar"></v-app-bar>
    <v-main class="d-flex align-center justify-center">
      Main Content
    </v-main>
    <v-footer app>
      {{ new Date().getFullYear() }}
    </v-footer>
  </v-app>
</template>

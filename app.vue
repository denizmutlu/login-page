<template>
  <v-app theme="dark">
    <v-app-bar title="Application bar" class="text-center" />
    <v-main class="d-flex align-center justify-center">
      Main Content
    </v-main>
    <v-footer app class="d-flex justify-center">
      {{ new Date().getFullYear() }}
    </v-footer>
  </v-app>
</template>

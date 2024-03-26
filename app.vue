<template>
  <v-app theme="dark">
    <v-app-bar :title="title" class="text-center" />
    <v-main class="d-flex justify-center align-center">
      <v-row class="ma-0">
        <v-col cols"auto" class="text-h4">
          {{ signin }}
        </v-col>
        <v-col cols"12" class="pa-0" />
        <v-col>
          <v-text-field rounded variant="solo-inverted"  />
        </v-col>
      </v-row>
    </v-main>
    <v-footer app class="d-flex justify-center">
      {{ new Date().getFullYear() }}
    </v-footer>
  </v-app>
</template>
<script setup>
  const language = {
    en: {
      title: 'My Title',
      signin: 'Sign in'
    }
  }
</script>

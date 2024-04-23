<template>
  <v-app theme="dark">
    <v-app-bar :title="en.txt.title" class="text-center" />
    <v-main class="d-flex justify-center align-center">
      <v-row class="ma-0">
        <v-col cols="auto" class="text-h4">{{ en.txt.signin }}</v-col>
        <v-col cols="12" class="pa-0" />
        <v-col cols="8">
          <v-row>
            <v-col cols="12">
              <v-text-field rounded variant="solo-inverted"  />
            </v-col>
            <v-col>
              <v-btn v-text="en.btn.usepass" />
            </v-col>
            <v-col>
              <v-btn v-text="en.btn.sendlink" />
            </v-col>
          </v-row>
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
      btn: {
        sendlink: 'Send me a link',
        usepass: 'Use password'
      },
      txt: {
        title: 'My Title',
        signin: 'Sign in'
      },
      fld: {
        email: ''
      }
    }
  }
</script>

<script setup lang="ts">
import AppSidebar from './components/AppSidebar.vue'
</script>

<template>
  <v-app>
    <header>
      <v-app-bar>
        <v-app-bar-title> strawberry fields </v-app-bar-title>
      </v-app-bar>
    </header>
    <body>
      <v-main>
        <sidebar>
          <AppSidebar />
        </sidebar>
        <v-container>
          <router-view></router-view>
        </v-container>
      </v-main>
      <!-- /homeの時 -->
      <!-- /notificationの時 -->
      <!-- /contact -->
      <!-- /obog -->
    </body>
  </v-app>
</template>

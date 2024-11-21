<script setup lang="ts">
import AppSidebar from './components/AppSidebar.vue'
import CommonSpinner from './components/Common/CommonSpinner.vue'
</script>

<template>
  <v-app>
    <header>
      <v-app-bar>
        <v-app-bar-title> strawberry fields </v-app-bar-title>
      </v-app-bar>
    </header>
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
  </v-app>
</template>
<style scoped></style>

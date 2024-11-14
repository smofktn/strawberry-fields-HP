<script setup lang="ts"></script>
<template>
  <v-navigation-drawer>
    <v-list>
      <v-list-item title="Home" to="/" :link="true">
        <!-- <router-link to="/"></router-link> -->
      </v-list-item>
      <v-list-item title="about" to="/about" :link="true">
        <!-- <router-link to="/about"></router-link> -->
      </v-list-item>
    </v-list>
  </v-navigation-drawer>
</template>

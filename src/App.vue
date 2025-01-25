<template>
  <v-app>
    <home-menu/>
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script lang="ts">
import HomeMenu from './components/HomeMenu.vue'
export default {
  name: "app",
  components: {HomeMenu}
}
</script>

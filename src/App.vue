<template>
  <v-app>
    <nav-bar />
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
import NavBar from '@/components/NavBar/NavBar.vue'

export default {
  components: {
    NavBar
  }
}
</script>

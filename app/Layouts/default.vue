<template>
  <v-app id="inspire">
    <v-navigation-drawer 
        color="surface-variant" 
        v-model="drawer">
            <v-list>
                <v-list-item
                prepend-icon="mdi-view-dashboard"
                title="Home"
                value="home"
            ></v-list-item>
            <v-list-item
                prepend-icon="mdi-information-variant"
                title="About"
                value="home"
            ></v-list-item>
            </v-list>
    </v-navigation-drawer>

    <v-app-bar>
        <v-app-bar-nav-icon 
            @click="drawer = !drawer"
        ></v-app-bar-nav-icon>

        <v-app-bar-title>
            "Student Portal"
        </v-app-bar-title>
    </v-app-bar>

    <v-main>
      <NuxtPage />
    </v-main>
  </v-app>
</template>

<script setup>
  import { ref } from 'vue'

  const drawer = ref(null)
</script>

<script>
  export default {
    data: () => ({ drawer: null }),
  }
</script>
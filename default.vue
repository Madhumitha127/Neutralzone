<template>
  <v-app>
    <v-app-bar color="black" app>
    <v-app-bar-nav-icon color="white"> </v-app-bar-nav-icon>
     <h4 class="text-h6" style="color:white">Neutral Zone </h4>
     <v-spacer></v-spacer>
     <v-btn text plain style="color:white">About</v-btn>
     <v-btn text plain style="color:white" to = '/loginpage'>Login</v-btn>
     <v-btn text plain style="color:white" to ='/signup'>Signup</v-btn>
   </v-app-bar>
        <v-main>
            <Nuxt/>
        </v-main>
        <v-footer
    color="black"
    padless
  >
    <v-row
      justify="center"
      no-gutters
    >
      <v-btn
        v-for="link in links"
        :key="link"
        color="white"
        text
        rounded
        class="my-2"
      >
        {{ link }}
      </v-btn>
      <v-col
        class="black text-center white--text"
        cols="12"
      >
        {{ new Date().getFullYear() }} — <strong>Vuetify</strong>
      </v-col>
    </v-row>
  </v-footer>
    </v-app>
</template>
<script>
  export default {
    data: () => ({
      links: [
        'Home',
        'About Us',
        'Team',
        'Services',
        'Blog',
        'Contact Us',
      ],
    }),
  }
</script>
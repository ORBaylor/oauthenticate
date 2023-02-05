<template>
  <v-app>
    <v-main>
      <router-view/>
      {{ clientId }}
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //Setting the client id from the .env file
   // process.env is how you get to vars in .env files
    //nclientId: process.env.VUE_APP_AUTH0_CONFIG_CLIENTID
  }),
}
</script>

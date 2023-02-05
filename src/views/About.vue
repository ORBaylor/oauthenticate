<template>
 
 <div>
  <v-app-bar :elevation="2" rounded class="d-flex justify-space-between">
         <!-- Using to="/about" on the btn tell Vuetify to link to the -->
         <!-- routing component -->
       <v-btn to="/" variant="outlined" class="mr-2">Home</v-btn>
       <v-btn to="/about" variant="outlined" class="mr-2">About</v-btn>
       <v-btn to="/contact" variant="outlined" class="mr-2">Contact</v-btn>
       <v-btn to="/members" variant="outlined" class="mr-2">Members</v-btn>
     
     </v-app-bar>
     <h1>This is an about page</h1>
   
 </div>
 </template>
 
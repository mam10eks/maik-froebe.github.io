<template>
  <v-app-bar>
    <v-app-bar-title>
      <router-link to="/" style="text-decoration: none; color: inherit; outline: 0;">
        <h2>Maik Fr&ouml;be</h2>
      </router-link>
    </v-app-bar-title>
    <template v-slot:prepend>
      <v-menu>
        <template v-slot:activator="{ props }">
          <v-app-bar-nav-icon v-bind="props"/>
        </template>

        <v-list>
          <v-list-item title="Posts"/>
          <v-list-item title="Publications"/>
          <v-list-item title="Projects"/>
          <v-list-item title="Contact"/>
        </v-list>
      </v-menu>
    </template>
  </v-app-bar>
</template>
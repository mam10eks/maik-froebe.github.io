<template>
  <v-app-bar style="background-color: #323232; color: white;">
    <v-container style="max-width: 1110px;">
      <v-row>
        <v-col>
          <router-link to="/">
            <img src="/favicon.png" alt="Maik Fr&ouml;be" style="height: 2.667em">
          </router-link>
        </v-col>

        <v-col class="text-right">
          <v-menu>
            <template v-slot:activator="{ props }">
              <v-btn v-bind="props">
                <v-icon>mdi-menu</v-icon>
              </v-btn>
            </template>
            
          </v-menu>
        </v-col>
      </v-row>

    </v-container>
  </v-app-bar>
</template>
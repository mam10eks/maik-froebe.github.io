<template>
<v-container class="text-center">
  <v-img class="mx-auto" height="300px" max-width="100%" width="300px" src="@/assets/logo.png"/>
  <section>
    <h1 class="text-h3 text-sm-h3 py-4 mt-10">
      Maik Fr&ouml;be
    </h1>
    <p class="mx-auto py-4 tira-explanation">
      PhD-Student in the <a href="https://webis.de" target="_blank">webis.de</a> group interested in IR and NLP.
    </p>
    <v-row class="d-flex justify-center py-4">
      <v-col cols="auto">
        <v-btn color="primary" href="https://www.fmi.uni-jena.de/4653/maik-froebe" target="blank" min-width="228" rel="noopener noreferrer" size="x-large" variant="flat">
          <v-icon icon="mdi-briefcase-outline" size="large" start/>
          Work
        </v-btn>
      </v-col>
      <v-col cols="auto text-primary">
        <v-btn href="https://webis.de/publications.html?q=maik+fr%C3%B6be" target="blank" min-width="228" rel="noopener noreferrer" size="x-large" variant="outlined">
          <v-icon icon="mdi-book-open-blank-variant-outline" size="large" start/>
          Publications
        </v-btn>
      </v-col>
      <v-col cols="auto">
        <v-btn class="home-button" href="https://github.com/mam10eks" target="blank" min-width="228" rel="noopener noreferrer" size="x-large" variant="flat">
          <v-icon icon="mdi-github" size="large" start/>
          GitHub
        </v-btn>
      </v-col>
    </v-row>
  </section>
</v-container>
</template>
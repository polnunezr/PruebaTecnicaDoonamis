<template>
  <div>
    <v-container v-for="n in 4" :key="n" class="bg-surface-variant mb-6 mt-10">
      <v-row align="center" no-gutters style="height: 150px">
        <v-col v-for="n in 3" :key="n">
          <v-sheet class="pa-2 ma-2"> .align-center </v-sheet>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

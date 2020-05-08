<template>
  <div id="app">
    <v-app>
      <v-content>
        <v-container fluid>
          <router-view />
        </v-container>
      </v-content>
    </v-app>
  </div>
</template>

<style lang="scss">
.container {
  padding: 0 !important;
}

body {
  margin: 0;
  padding: 0;
}
</style>

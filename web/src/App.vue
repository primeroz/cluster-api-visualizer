<template>
  <v-app id="app">
    <v-main id="main">
      <router-view />
    </v-main>
  </v-app>
</template>

<style>
html,
body {
  height: 100%;
  width: 100%;
  padding: 0;
  margin: 0;
  background-color: #f8f3f2;
}

#app {
  font-family: Roboto;
  /* text-align: center; */
  height: 100%;
}

#main {
  height: 100%;
  background-color: #f8f3f2;
}
</style>
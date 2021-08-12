<template>
  <div id="app">
    <v-container fluid>
      <v-app-bar
          color="deep-green"
          dense
          dark
      >
        <v-spacer/>
        <v-btn outlined class="ml-3">Главная</v-btn>
        <v-btn outlined class="ml-3">Фотографии</v-btn>
      </v-app-bar>
    </v-container>
  </div>
</template>

<script>


export default {
  name: 'App',
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

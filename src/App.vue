<template>
  <div id="app">   
    <md-toolbar>
        <img src="./assets/logo.png">
      <h1 class="md-title">Fempire Vue.js</h1>
    </md-toolbar>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'app',
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
.md-toolbar img{
  height: 45px;
  margin-right: 15px;
}
</style>

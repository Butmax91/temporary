<template>
  <div id="app">
    <div id="nav">
      <h3 class="col-1 bg-primary">sdf</h3>
    </div>
    <router-view/>s
  </div>
</template>

<style lang="scss">
@import '../node_modules/bootstrap/scss/bootstrap';
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;
    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>

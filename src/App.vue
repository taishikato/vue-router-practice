<template>
  <div id="app">
    <img src="./assets/logo.png">
    <div class="">
      <ul>
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/firstroute/takato">FirstRoute</router-link></li>
        <li><router-link to="/firstroute/takato/child">FirstRouteChild</router-link></li>
      </ul>
    </div>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>

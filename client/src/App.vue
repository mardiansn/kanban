<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style>
body {
  background-image: url('./assets/background.png');
  font-size: 80%;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #253647;
}

</style>

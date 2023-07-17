<template>
  <div id="app">
    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/pera">Pera</router-link>
    </nav>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: Georgia, serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #c2370d;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #c5e2ff;
}

nav a.router-link-exact-active {
  color: #250000;
}
</style>

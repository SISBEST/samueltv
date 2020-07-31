<template>
  <div id="app">
    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/schedule">Schedule &amp; Shows</router-link> |
      <router-link to="/news">News</router-link> |
      <router-link to="/about">About</router-link>
    </nav>
    <router-view/>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Courier+Prime:wght@700&display=swap');

#app {
  font-family: 'Courier Prime', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #00a1de;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #00a1de;
}

nav a.router-link-exact-active {
  color: #f9461c;
}
</style>

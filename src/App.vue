<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/mult">Mult</router-link>
  </div>
  <router-view />
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Lato&display=swap");
#app {
  font-family: "Lato", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: var(--font-clr);
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: var(--font-clr);
  text-decoration: none;
}

#nav a.router-link-exact-active {
  color: var(--primary-clr);
  text-decoration: underline;
}
</style>

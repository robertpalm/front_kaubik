<template>
  <nav>
    <router-link to="/">Home</router-link> |
  </nav>
  <router-view/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: crimson;
}

nav a.router-link-exact-active {
  color: deepskyblue;
}

.btn-dark {
  background-color: #2c3e50 !important;
  border-color: #2c3e50 !important;
}

.btn-outline-dark {
  background-color: #ffffff !important;
  border-color: #2c3e50 !important;

}

.btn-dark:hover {
  background-color: #415164 !important;
  border-color: #415164 !important;
}

.btn-outline-dark:hover {
  background-color: #2c3e50 !important;
  border-color: #2c3e50 !important;
}

</style>

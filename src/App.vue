<template>
  <div id="app">
    <div id="nav">
      <b-navbar toggleable="lg" type="dark" variant="dark">
        <b-navbar-brand to="/">
          Legend Arena
        </b-navbar-brand>
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <b-nav-item to="/">
              Home
            </b-nav-item>
            <b-nav-item to="/about">
              About
            </b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
    <router-view />
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  border-bottom-color: #ce3304;
  border-bottom-width: 2px;
  border-bottom-style: solid;

  a {
    font-weight: bold;
    color: #ce3304;

    &.router-link-exact-active {
      color: #ff0000;
    }
  }
}
</style>

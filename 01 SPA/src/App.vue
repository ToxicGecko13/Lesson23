<template>
  <div id="app">
    <header>
      <h1>A Single Page App</h1>
      <div id="nav">
        <router-link to="/">Home Page</router-link>
        <p><br></p>
        <router-link to="/user">User Page</router-link>
      </div>
    </header>


    <footer>
      <em>(c) 2019 copyright <a href="https://mhintegrity.com">MHIntegrity</a></em>
    </footer>
    <router-view/>
  </div>
</template>


<style scoped>
  * {
    box-sizing: border-box;
    border: 0;
    padding: 0;
    margin: 0;
  }
  h1 {
    font-size: 30px;
    padding-bottom: 8px;
  }
  header {
    position: sticky;
    top: 0px;
    background-color: lightsteelblue;
    padding: 16px;
  }
  header nav {
    list-style-type: none;
  }
  header nav {
    margin: 6px;
  }
  footer {
    position: fixed;
    bottom: 0%;
    background-color: lightsteelblue;
    padding: 8px;
    width: 100%;
  }
</style>

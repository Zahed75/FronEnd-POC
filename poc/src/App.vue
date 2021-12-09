<template>
  <div id="nav">
    <!-- <router-link to="/">Login</router-link> |
    <router-link to="/signup">Signup</router-link> -->

  </div>
    <router-view/>
      
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@100;200;300;400;500;600;700;800;900&display=swap');
*{
  font-family: 'Montserrat', sans-serif;
}
#app {

  
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 70px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>

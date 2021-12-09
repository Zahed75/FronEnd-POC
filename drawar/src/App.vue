<template>
<div>
  <Sidebar/>
  <!-- <div id="nav">

    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div> -->
  <router-view />
</div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@100;200;300;400;500;600;700;800;900&display=swap');



#app {
  font-family: 'Montserrat', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

}

</style>


<script>

import Sidebar from "@/components/sidebar/Sidebar"

export default {

  components:{
    Sidebar
    }
}
</script>
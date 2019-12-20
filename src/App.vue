<template>
  <div id="app">
    <br>
    <br>
    
    <a href="https://www.stemformatics.org"><img alt="Vue logo" src="https://jacks-centos7.sfo2.digitaloceanspaces.com/Screen%20Shot%202019-12-19%20at%203.33.20%20pm.png"></a>&nbsp;&nbsp;&nbsp;&nbsp;
    <a href="https://www.stemformatics.org"><img alt="Vue logo" src="https://jacks-centos7.sfo2.digitaloceanspaces.com/CSCS%20logo.png" style="height:10%; width: 10%;"></a>
    <Info msg="Stemformatics/GSoC - 2020"/>

    <div id="nav">
      <router-link to="/">About</router-link> |
      <router-link to="/projects">Projects</router-link> | 
      <router-link to="/contact">Get in touch</router-link> 
      
    </div>
    <router-view/>

    <br>
    <a href="https://gitter.im/stemformatics/Lobby"><img alt="Vue logo" src="https://jacks-centos7.sfo2.digitaloceanspaces.com/Screen%20Shot%202019-12-19%20at%202.41.51%20pm.png"></a>
    <br>
    <br>
    <br>

  </div>
</template>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #a64dff;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #a64dff;
}

#nav a.router-link-exact-active {
  color: #ff8c1a;
}
</style>

<template>
<div class="beat">
  <!-- <h1>Soulful verifications</h1>
  <p>a place to come relax (placeholder)</p> -->
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>  
  </nav>
  
  <!-- <div class="videos">
    <div class="top-row">
   <button>video1</button>
   <button>video2</button>
   <button>video3</button>
   <div class="bottom-row">
    <button>video4</button>
    <button>video5</button>
    <button>video6</button>
   </div> -->
   </div>
  <!-- </div> -->
  <router-view/>
<!-- </div> -->
</template>

<style>
html { 
  background: url(assets/sunset-sunflowers.jpg) no-repeat center center fixed; 
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
  /* sets nav bar to bottom */
  position: fixed;
  bottom: 0;
  width: 100%;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}

</style>

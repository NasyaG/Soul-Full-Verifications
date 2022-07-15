<template>
  <div class="beats">
    <!-- <div class="video-box"> -->

    
    <h1>Soul-Full Verifications</h1>
    <p>
      Where you can come to relax (placeholder)
      <!-- <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>. -->
    </p>
    <div class="videos"> 
      <div class="top-row">
       <button>vid1</button>
       <button>vid2</button>
       <button>vid3</button>
      </div>
      <div class="bottom-row">
        <button>vid4</button>
        <button>vid5</button>
        <button>vid6</button>
        
      </div>
     
    <!-- </div> -->
    </div>
    <!-- <h3>Installed CLI Plugins</h3>
    <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
    </ul>
    <h3>Essential Links</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
    </ul>
    <h3>Ecosystem</h3>
    <ul>
      <li><a href="https://router.vuejs.org" target="_blank" rel="noopener">vue-router</a></li>
      <li><a href="https://vuex.vuejs.org" target="_blank" rel="noopener">vuex</a></li>
      <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools" target="_blank" rel="noopener">vue-devtools</a></li>
      <li><a href="https://vue-loader.vuejs.org" target="_blank" rel="noopener">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank" rel="noopener">awesome-vue</a></li>
    </ul> -->
    <div>
    <footer>~Created by Nasya Gay 2022~</footer>
    </div>
  </div>
</template>

<script>
export default {
  name: 'BinuralBeats',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
html, body{
  margin: 0px;
  height: 100%;

}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.beats{
   width: 100%;
   height: 100%;
   position: absolute;
   border: 1px #42b983 solid;
   
 
}

/* .video-box{
    border: 1px #42b983 solid;
    height: 100%;
    position: relative;
    display: grid;
} */

.videos{
 /* display: inline-block; */
 
  background-color: hsla(291, 45%, 5%, .5);
  
  border: 1px solid black;
  width: 70%;
  height: 60%;
 
 display: flex;
 flex-direction: column;


   
  /* box-sizing: border-box;
  -moz-box-align: center;
  max-inline-size: 700px;
  max-block-size: 100%;
   */
 
} 
.top-row{
  display: flex;
 justify-content: space-around;
 align-items: stretch;
 flex-grow: 1;
 padding: 50px;
}
.bottom-row{
   display: flex;
  justify-content: space-around;
  align-items: stretch;
   padding: 50px;
}
footer{

}
</style>

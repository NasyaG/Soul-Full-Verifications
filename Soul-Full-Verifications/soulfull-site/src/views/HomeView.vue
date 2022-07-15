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
      <div class="middle-row">
        <button>vid4</button>
        <button>vid5</button>
        <button>vid6</button> 
      </div>
      <div class="bottom-row">
        <button>vid7</button>
        <button>vid8</button>
        <button>vid9</button>
      </div>
     
    </div>
    </div>
</template>

<script>
export default {
 name: 'HomePage'

}
</script>

<style>

html, body{
    margin: 0px;
    height: 100%;
}
.beats{
   /* width: 100%; */
   height: 100vh;
   /* position: absolute; */
   border: 1px #42b983 solid;
   
}
.videos{
 /* display: inline-block; */
  margin:auto;
  background-color: hsla(291, 45%, 5%, .5);
  
  border: 1px solid black;
  width: 70%;
  height: 60%;
}
</style>
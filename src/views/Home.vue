<template>
  <div class="home">
    <img src="../components/ffixv.png" data-src="done" alt="" style="opacity: 1;">
    <HelloWorld msg="F E P O - G I G A"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
<style>
@font-face {
  font-family: "Text";
  src: url("../assets/Text.otf");
}
#app {
  

  /* font-family: Avenir, Helvetica, Arial, sans-serif; */
  /* -webkit-font-smoothing: antialiased; */
  /* -moz-osx-font-smoothing: grayscale; */
  text-align: center;
  color: #ec54a0;
  /* margin-top: -px; */
  background-image: url("../assets/FEPO.png");
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
  background-position: center center;
  height: auto;
  width: auto;
  background-color: #cf2c2c;
  
  
  font-weight: normal;
  text-shadow: 0.088rem 0.088rem 0.125rem #000000;
  font-family: 'Text', sans-serif;
  font-smooth: auto;

  

}
#logo.png {
    width: 11.5rem;
    transition: transform 0.25s ease, z-index 0.25s ease;
}
@font-face {
  font-family: "Christmas Dream";
  src: url("../assets/Christmas\ Dream.ttf");
}


/* main {
  background: rgb(0, 0, 0);
  background-size: cover ; */
/* } */
h3 {
    display: block;
    font-size: 2.5em;
    margin-block-start: 1em;
    margin-block-end: 1em;  
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    font-weight: 100;
    text-shadow: 0.088rem 0.088rem 0.125rem #000000;
    color: #e2b00b;
    font-family: "Christmas dream";
}
body, html {
  height: 100%;
  margin:0;
}
#loader {
  position: absolute;
  left: 50%;
  top: 50%;
  z-index: 1;
  width: 120px;
  height: 120px;
  margin: -76px 0 0 -76px;
  border: 16px solid #f3f3f3;
  border-radius: 50%;
  border-top: 16px solid #3498db;
  -webkit-animation: spin 2s linear infinite;
  animation: spin 2s linear infinite;
}
</style>

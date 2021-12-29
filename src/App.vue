<template>
  <div id="app" >
    <img src="./assets/logo.png" data-src="done" alt="" style="opacity: 1;">
    <HelloWorld msg="Free company Dango"/>
    
  </div>
</template>


<script>

import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
var countDownDate = new Date("Dec 31 2021 24:00:00").getTime();

// Update the count down every 1 second
var x = setInterval(function() {

  // Get today's date and time
  var now = new Date().getTime();

  // Find the distance between now and the count down date
  var distance = countDownDate - now;

  // Time calculations for days, hours, minutes and seconds
  var days = Math.floor(distance / (1000 * 60 * 60 * 24));
  var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  var seconds = Math.floor((distance % (1000 * 60)) / 1000);

  // Display the result in the element with id="demo"
  document.getElementById("demo").innerHTML = days + "d " + hours + "h "
  + minutes + "m " + seconds + "s ";

  // If the count down is finished, write some text
  if (distance < 0) {
    clearInterval(x);
    document.getElementById("demo").innerHTML = "EXPIRED";
  }
}, 1000);
</script>

<style>
@font-face {
  font-family: "Christmas Dream";
  src: url("./assets/Christmas\ Dream.ttf");
}
.animate-bottom {
  position: relative;
  -webkit-animation-name: animatebottom;
  -webkit-animation-duration: 1s;
  animation-name: animatebottom;
  animation-duration: 1s
}

@-webkit-keyframes animatebottom {
  from { bottom:-100px; opacity:0 } 
  to { bottom:0px; opacity:1 }
}

@keyframes animatebottom { 
  from{ bottom:-100px; opacity:0 } 
  to{ bottom:0; opacity:1 }
}

#app {




  /* font-family: Avenir, Helvetica, Arial, sans-serif; */
  /* -webkit-font-smoothing: antialiased; */
  /* -moz-osx-font-smoothing: grayscale; */
  text-align: center;
  color: #ff0000;
  /* margin-top: -px; */
  background-image: url("./assets/Dango.png");
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-size: cover;
  background-position: center center;
  height: auto;
  width: auto;
  background-color: #cf2c2c;
  
  
  font-weight: 100;
  text-shadow: 0.088rem 0.088rem 0.125rem #000000;
  font-family: 'Montserrat', sans-serif;
  font-smooth: auto;

  

}
#logo.png {
    width: 11.5rem;
    transition: transform 0.25s ease, z-index 0.25s ease;
}
@font-face {
  font-family: "Christmas Dream";
  src: url("./assets/Christmas\ Dream.ttf");
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

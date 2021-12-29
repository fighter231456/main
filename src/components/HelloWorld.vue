<template>
<div id="wrapper">
  <div id="main">
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2></h2>
    <h3  id="demo"></h3>
    <!-- <p>
      For a guide and recipes on how to configure / customize this project,<br>
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
    </p> -->
    <!-- <h3>Installed CLI Plugins</h3> -->
    <!-- <ul>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel" target="_blank" rel="noopener">babel</a></li>
      <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint" target="_blank" rel="noopener">eslint</a></li>
    </ul> -->
    <footer id="footer">
      <div id="container16" class="container default">
        <div class="wrapper">
          <div class="inner">
            <hr id="divider01">
            <hr id="divider08">
            <p id="text02">Dango FC
            </p>
            <p id="text05">
              <span>This is website for Free Company Dango User.
                </span><br> <span>We are Thai free company. Thais are more welcome to join na kub
                  </span><br> <span>Good luck and have fun
                    </span>
                    </p>
                    <hr id="divider03">
                    <!-- <hr id="divider03">
                    </div>
                    </div>
                    </div>
                    <div id="container08" class="container default full screen">
                      <div class="wrapper"><div class="inner">
                        <ul id="icons01" class="icons">
                          <li>
                            <a class="n01" href="https://twitter.com/DayDreamerFFXIV">
                            <svg><use xlink:href="#icon-905">
                              </use></svg><span class="label">Twitter
                                </span></a><svg><use xlink:href="#icon-a0a"></use></svg></li><li>
                                  <a class="n02" href="https://discord.gg/4RZVN8xHfb">
                                  <svg><use xlink:href="#icon-93f"></use></svg><span class="label">Discord
                                    </span></a><svg><use xlink:href="#icon-a0a"></use></svg></li><li>
                                      <a class="n03" href="https://na.finalfantasyxiv.com/lodestone/community_finder/f4a2ec0a675e928f0a10409504a8a13a414dece9/">
                                      <svg><use xlink:href="#icon-b3b"></use></svg><span class="label">Final Fantasy XIV
                                        </span></a><svg><use xlink:href="#icon-a0a"></use></svg></li></ul></div></div></div></footer> -->
                        </div></div></div></footer>
                       
  
<div id="columns01" class="container columns">
  <div class="wrapper"><div class="inner"><div>
    
       <div class="zoom"> <a href="" class="frame"><img src="../assets/Dango.png" width="100%" alt=""></a></div>
        
          
        
        </div></div></div></div>

        <hr id="divider03"> 
 <h4>Contract</h4>
 
    <ul>
      <li><a href="https://discord.gg/7WARXsgW" target="_blank" rel="noopener"><img border="0" alt="W3Schools" src="./discord.png" width="25" height="25"></a></li>
      <!-- <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li> -->
      <!-- <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li> -->
      <li><a href="https://twitter.com/_FEPO_" target="_blank" rel="noopener"><img border="0" alt="W3Schools" src="./twitter.png" width="25" height="25"></a></li>
      <!-- <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li> -->
    </ul>
    <hr id="divider03"> 
    <h4>FreeCompany Click Here</h4>

    <ul>
      <li><a href="https://na.finalfantasyxiv.com/lodestone/freecompany/9236601360760305191/" target="_blank" rel="noopener"><img border="0" alt="W3Schools" src="./ffixv.png" width="150" height="size"></a></li>
    </ul
    ><hr id="divider03">
    <span>Credit By : FEPO<ul><li><a href="/about" class="router-link-exact-active router-link-active" aria-current="page"><img border="0" alt="W3Schools" src="./link.png" width="20" height="20"></a></li>

    </ul></span>
    </div></div></div>
  
    
</template>
<script>
// Set the date we're counting down to
// var countDownDate = new Date("Dec 31 2021 24:00:00").getTime();

// // Update the count down every 1 second
// var x = setInterval(function() {

//   // Get today's date and time
//   var now = new Date().getTime();

//   // Find the distance between now and the count down date
//   var distance = countDownDate - now;

//   // Time calculations for days, hours, minutes and seconds
//   var days = Math.floor(distance / (1000 * 60 * 60 * 24));
//   var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
//   var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
//   var seconds = Math.floor((distance % (1000 * 60)) / 1000);

//   // Display the result in the element with id="demo"
//   document.getElementById("demo").innerHTML = days + "d " + hours + "h "
//   + minutes + "m " + seconds + "s ";

//   // If the count down is finished, write some text
//   if (distance < 0) {
//     clearInterval(x);
//     document.getElementById("demo").innerHTML = "EXPIRED";
//   }
// }, 1000);
</script>
<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
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
  color: #0b07fc;
}
h1 {
    display: block;
    font-size: 4em;
    margin-block-start: 0em;
    margin-block-end: 0em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    font-weight: 50;
}
#text02 {
    text-transform: uppercase;
    color: #f0a504;
    font-family: 'Raleway', sans-serif;
    letter-spacing: 0.35rem;
    width: calc(100% + 0.35rem);
    font-size: 1em;
    line-height: -1.25;
    font-weight: 700;
    text-shadow: 0.088rem 0.088rem 0.125rem #000000;
}
time {
  color: #0b07fc;
}
#text05 {
    text-transform: uppercase;
    color: #ffffff;
    font-family: 'Raleway', sans-serif;
    letter-spacing: 0.35rem;
    width: calc(100% + 0.35rem);
    font-size: 0.75em;
    line-height: -1em;
    font-weight: 100;
    text-shadow: 0.088rem 0.088rem 0.125rem #000000;
}
/* body{
  background: #004D40;
  text-align:center;
  padding: 50px 0;
}
h2{
    font-size:26px;
    color: rgb(7, 6, 6);
  }
.timer {
  font-size: 20px;
  color: rgb(255, 0, 0);
  text-align:center;
  margin-top: 50px;
} */
p {
  text-align: center;
  font-size: 60px;
  margin-top: 0px;
}
h4{
  color: #a1df2e;
}
a[data-v-469af010] {
    color: #f5f5ff;
}
#main {
    display: flex;
    position: relative;
    max-width: 100%;
    z-index: 1;
    align-items: center;
    justify-content: center;
    flex-grow: 0;
    flex-shrink: 0;
    text-align: center;
    background-color: rgba(44,42,54,0.8);
    box-shadow: 0rem 3rem 3.125rem 0rem rgb(44 42 54 / 45%);
    border-radius: 0.5rem 0.5rem 0.5rem 0.5rem;
    transition: opacity 1.25s ease 0s,transform 1.25s ease 0s;
    width: 40rem;
}
#wrapper {
    -webkit-overflow-scrolling: touch;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    min-height: var(--viewport-height);
    position: relative;
    z-index: 2;
    overflow: hidden;
    padding: 3.5rem 3.5rem 3.5rem 3.5rem;
}
p[data-v-469af010] {
    text-align: center;
    font-size: 30px;
    margin-top: -7px;
}
p[data-v-469af010][data-v-469af010] {
    text-align: center;
    color: rgb(238, 22, 123);
    font-size: 22px;
    margin-top: -5px;
}
#text05[data-v-469af010] {
    text-transform: uppercase;
    color: #ffffff;
    font-family: 'Raleway', sans-serif;
    letter-spacing: 0.1rem;
    width: calc(100% + 0.35rem);
    font-size: 0.75em;
    line-height: -1em;
    font-weight: 100;
    text-shadow: 0.088rem 0.088rem 0.125rem #000000;
}
.image {
  width: 100%;
  height: auto;
}
.overlay {
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  /* background-color: #008CBA; */
  overflow: hidden;
  width: 100%;
  height: 100%;
  transform: scale(0);
  transition: .3s ease;
}
.container {
  position: relative;
  width: 100%;
}
.container:hover .overlay {
  transform: scale(1);
}
.text {
  color: white;
  font-size: 20px;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
}
.overlay[data-v-469af010] {
    position: absolute;
    bottom: -16px;
    left: -250px;
    right: 0;
    overflow: hidden;
    width: 104%;
    height: 100%;
    transform: scale(0);
    transition: .3s ease;
}
.zoom {
  padding: 0;
  background-color: green;
  transition: transform 1s;
  width: 200px;
  height: 110px;
  margin: 0 auto;
}
.zoom:hover {
  -ms-transform: scale(5); /* IE 9 */
  -webkit-transform: scale(5); /* Safari 3-8 */
  transform: scale(5);
}
#text05[data-v-053b413c] {
    text-transform: uppercase;
    color: #fff;
    font-family: Raleway,sans-serif;
    letter-spacing: .25rem;
    width: calc(100% + .35rem);
    font-size: .75em;
    line-height: -1em;
    font-weight: 100;
    text-shadow: 0.088rem 0.088rem 0.125rem #000;
}
a[data-v-053b413c] {
    color: #ffffff;
}

</style>
<style>
#app {
  

  /* font-family: Avenir, Helvetica, Arial, sans-serif; */
  /* -webkit-font-smoothing: antialiased; */
  /* -moz-osx-font-smoothing: grayscale; */
  text-align: center;
  color: #ff0000;
  /* margin-top: -px; */
  background-image: url("../assets/Dango.png");
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

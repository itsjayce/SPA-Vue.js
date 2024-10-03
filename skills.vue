<template>
    <div id="skills">
      <h1>{{ msg }}</h1>
      <div class="container fluid text-center">
  <div class="row">
    <div class="col html">
      <img src="./assets/html.png" height="5%" width="65%">
    </div>
    <div class="col">
     <img src="./assets/css.png"  >
    </div>
  </div>
  <div class="row">
    <div class="col">
      <img src="./assets/js.png" >
    </div>
    <div class="col">
     <img src="./assets/node.png" >
    </div>
    <div class="col">
    <img src="./assets/mongodb.png">
    </div>
  </div>
</div>
<div id="space"></div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'skills',
    data () {
      return {
        msg: "Skills"
      }
    }
  }
  </script>
  
  <style>
  #skills {
    font-family: 'Poppins', sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #0D1717;
    background-color: #f1f1f1;

  }
  
 h1 {
  padding :3% ;
 }

p {
    
    font-size: 20px;
    padding-bottom: 2%;
  }
img {
  max-width: 45%;
  max-height: 45%;
 }

.html {
  max-height: 45%;
  max-width: 46%;
}
#space {
  padding:2%
}
  </style>
  
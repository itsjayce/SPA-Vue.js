<template>
    <div id="education">
        <h1>{{ educMsg }}</h1>
        <div class="container text-center">
        <div class="row">
            <div class="col">
            <img src="./assets/hfa.png">
            <p>Holy Family Academy </p>
            <p>Elementary to Senior High School</p>
            </div>
            <div class="col">
            <img src="./assets/hau.png">
            <p>Holy Angel University</p>
            <p>College</p>
            </div>
        </div>
</div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'profile',
    data () {
      return {
        educMsg: "Education"
      }
    }
  }
  </script>
  
  <style>
  #profile {
    font-family: 'Poppins', sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    color: #ffffff;
    background-color: #06080c;
    display:flex;
  }
  
  h3{
    text-align: center;
  }
  
  
  .col {
    align-self: center;
  }
  p {
    font-size: 18px;
    padding: 0;
    margin: 0;
  }
  </style>
  
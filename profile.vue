<template>
  <div id="profile">
    <div class="container fluid text-center">
    <div class="row align-items-start">
      <div class="col">
      <img src="./assets/myimg.png" >  
      </div>
      <div class="col">
        <p>{{welcomeMsg}}</p>
        <h3> An aspiring web developer student from WD-301, exploring the exciting world of web development. Eager to expand my skills in front and back-end technologies.</h3>
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
      welcomeMsg: "Hi, I'm Christine Jasline Natividad"
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
  padding-bottom: 2%;
}
</style>

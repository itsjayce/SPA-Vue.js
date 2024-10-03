<template>
    <div id="app">
        <h1> {{ msg }}</h1>
        <profile></profile>
        <skills></skills>
        <education></education>
    </div>
</template>
<script>
import Profile from './components/profile';
import Skills from './components/skills';
import Education from './components/education'

export default {
    name: 'app',
    components: {
        Profile,
        Skills,
        Education
    },

        
    data() {
        return {
            msg: 'Welcome to my Profile Page'
        }
    }
}
 
</script>
<style scoped>
#app {
    font-family: 'Poppins', sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #ffff;
    padding-top: 2%;
    background-color: #06080c;
}


</style>
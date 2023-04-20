<template>
  <NavBar />
  <router-view/>
</template>

<script>
import NavBar from './components/NavBar.vue';

export default{
  name:"App",
  components:{
    NavBar
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Merriweather:wght@300&display=swap');

#app {
font-family: 'Merriweather', serif;
min-height: 100vh;
background-image: url(https://i.postimg.cc/4dWXMDQ1/pexels-thirdman-5060557.jpg);
background-position: center;
background-repeat: no-repeat;
background-size: cover;
background-attachment: fixed;
}
</style>

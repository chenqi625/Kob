<template>
  <NavBar />
</template>

<script>


import NavBar from './components/NavBar.vue'
import "bootstrap/dist/css/bootstrap.min.css"
import "bootstrap/dist/js/bootstrap"


export default{
  components:{
    NavBar
  }

}
</script>

<style>
  body{
    background-image: url("./assets/yoyo鹿鸣.png");
    background-size: cover;
  }

</style>

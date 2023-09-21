<script>
  import AppTitle from './components/AppTitle.vue'

  export default{
    components: {
    AppTitle
    },

    data(){
      return{
        msg: 'hello vite'
      }
    }
  }
</script>

<template>
  <h1>{{msg}}</h1>

  <AppTitle></AppTitle>
</template>

<style>
  h1{
    background-color: blueviolet;
  }
</style>

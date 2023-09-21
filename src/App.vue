<script>
  import AppTitle from './components/AppTitle.vue'
  import AppHero from './components/AppHero.vue'

  export default{
    components: {
    AppTitle,
    AppHero
    },

    data(){
      return{
        msg: 'hello vite'
      }
    }
  }
</script>

<template>
  <h1 class="bg-success">{{msg}}</h1>

  <AppTitle class="mb-5"></AppTitle>

  <AppHero></AppHero>
</template>

<style>
</style>

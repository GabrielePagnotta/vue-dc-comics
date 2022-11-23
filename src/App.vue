<template>
  <div id="app">
    <!-- header -->
    <HeaderOne />
    <!-- main -->
    <MainOne />
    <!-- footer -->
    <FooterOne />
    <FooterTwo />
    
  </div>
</template>

<script>
import HeaderOne from './components/header/HeaderOne.vue'
import MainOne from './components/main/MainOne.vue'
import FooterOne from './components/footer/FooterOne.vue'
import FooterTwo from "./components/footer/FooterTwo.vue";




export default {
  name: 'App',
  components: {
   HeaderOne,
   MainOne,
   FooterOne,
   FooterTwo,
    
  }
}
</script>

<style lang="scss">
*{
  list-style: none;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  
}
</style>

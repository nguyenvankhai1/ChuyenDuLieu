<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <!-- <hienThi/> -->
    <!-- <VongDoi/>
    <baiTapProperties postTitle='GIÁ TRỊ'></baiTapProperties> -->
    <ComCha></ComCha>


  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'

// import hienThi from './components/hienThi'

// import VongDoi from './components/VongDoi'

// import baiTapProperties from'./components/baiTapProperties'

import ComCha from './components/ComCha'

export default {
  name: 'app',
  data(){
      return{
        value : 'Giá Trị'
      }
  },

  components: {
    // HelloWorld
    // hienThi
    // VongDoi,
    // baiTapProperties
    ComCha
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

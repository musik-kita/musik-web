<template>
  <div class="home content">
    <!-- <img alt="Vue logo" src="../../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <banner-component/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import BannerComponent from './component/Banner'

export default {
  name: 'Home',
  components: {
    // HelloWorld
    BannerComponent
  }
}
</script>

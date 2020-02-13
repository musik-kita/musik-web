<template>
  <div id="app">
    <navbar-component  class="content"/>
    <router-view/>
    <footer-component/>
  </div>
</template>

<script>
import NavbarComponent from '@/components/navbar/NavbarComponent'
import FooterComponent from '@/components/footer/Footer'

export default {
  components: {
    NavbarComponent,
    FooterComponent
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
/* .content {
  margin-top: 120px;
} */
</style>

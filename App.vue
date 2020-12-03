<template>
  <div id="app">
    <!-- 导航栏 -->
    <nav-bar></nav-bar>
    <div class="nav-bar-white"></div>
    <router-view></router-view>

  </div>
</template>

<script>
import NavBar from 'components/nav/NavBar.vue'
export default {
  name: 'App',
  components: {
    NavBar
  },
  created () {

  }
}
</script>
<style>
@import "~styles/base.css";
.nav-bar-white {
  height: 30px;
}
</style>

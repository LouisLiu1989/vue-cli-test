<template>
  <div id="app">
    <Navbar></Navbar>  
    <router-view></router-view>
  </div>
</template>

<script>
import Navbar from './components/partials/Navbar'
export default {
  name: 'app',
  components: {
    Navbar
  }
}
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap";
$border-width: 2px;
$card-border-width: 2px;

.router-link-active {
  color: $brand-primary !important;
}
</style>

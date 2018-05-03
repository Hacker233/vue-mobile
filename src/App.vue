<template>
  <div id="app">
    <headerv></headerv>
    <router-view/>
    <footerv></footerv>
  </div>
</template>

<script>
import headerv from './components/headerv'
import footerv from './components/footerv'

export default {
  name: 'App',
  components:{
    headerv,
    footerv
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
}
</style>

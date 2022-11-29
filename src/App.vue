<template>
  <headerTop/>
  <MenuTop/>
  <router-view/>
  <footerTop/>
</template>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

nav {
  padding: 30px;
}

nav a {
  font-weight: bold;
  color: #2c3e50;
}

nav a.router-link-exact-active {
  color: #42b983;
}
</style>


<script>
import MenuTop from "@/components/templates/MenuTop";
import headerTop from "@/components/templates/headerTop";
import footerTop from "@/components/templates/footerTop";
export default{
  components:{
    MenuTop,
    headerTop,
    footerTop
  }
}
</script>
<template>
  <div>
    <Header></Header>
    <div class="main-content">
      <SideNav></SideNav>
      <router-view />
    </div>
  </div>
</template>

<script>

import Header from "@/components/Header";
import SideNav from "@/components/SideNav";
export default {
  components:{
    Header,
    SideNav
  },
  mounted(){
    require('../assets/js/main')
  }
}
</script>

<style>

</style>
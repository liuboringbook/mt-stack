<template>
  <el-row class="m-header" :gutter="0">
       <el-col :span="5">
         <geo />
       </el-col>
       <el-col :span="9">
         <user/>
       </el-col>
       <el-col :span="10">
         <nav-bar></nav-bar>
       </el-col>
  </el-row>
</template>

<script>
import Geo from './geo'
import User from './user'
import NavBar from './nav'
  export default {
    components: {
      Geo,
      User,
      NavBar
    }
  }
</script>

<style lang="scss">
  @import "@/assets/css/public/header/index.scss";
  @import "@/assets/css/public/layout.scss";
</style>

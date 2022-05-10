<template>
  <header class="navbar">
    <div class="container">
      <el-menu
          :default-active="activeIndex"
          class=" navbar-nav "
          mode="horizontal"
          ellipsis="false"
          @select="handleSelect"
      >
        <el-menu-item index="1"><router-link to="/">Home</router-link></el-menu-item>
        <el-menu-item index="2"> <router-link to="/about">About</router-link></el-menu-item>
        <el-menu-item index="3">Processing Center</el-menu-item>
        <el-menu-item index="4">Processing Center</el-menu-item>
        <el-menu-item index="5">Processing Center</el-menu-item>
        <!--    <el-sub-menu index="2">-->
        <!--      <template #title>Workspace</template>-->
        <!--      <el-menu-item index="2-1">item one</el-menu-item>-->
        <!--      <el-menu-item index="2-2">item two</el-menu-item>-->
        <!--      <el-menu-item index="2-3">item three</el-menu-item>-->
        <!--      <el-sub-menu index="2-4">-->
        <!--        <template #title>item four</template>-->
        <!--        <el-menu-item index="2-4-1">item one</el-menu-item>-->
        <!--        <el-menu-item index="2-4-2">item two</el-menu-item>-->
        <!--        <el-menu-item index="2-4-3">item three</el-menu-item>-->
        <!--      </el-sub-menu>-->
        <!--    </el-sub-menu>-->
        <!--    <el-menu-item index="3" disabled>Info</el-menu-item>-->
        <!--    <el-menu-item index="4">Orders</el-menu-item>-->
      </el-menu>

<!--      <ul class="navbar-nav">-->
<!--        <li>-->
<!--          <router-link to="/">Home</router-link>-->
<!--        </li>-->
<!--        <li>-->
<!--          <router-link to="/about">About</router-link>-->
<!--        </li>-->
<!--      </ul>-->
<!--      <ul class=" navbar-nav right">-->
<!--        <li>-->
<!--          <a href="http://lesscss.org/" target="_blank">英文官网</a>-->
<!--        </li>-->
<!--        <li>-->
<!--          <a href="http://lesscss.org/" target="_blank">英文官网</a>-->
<!--        </li>-->
<!--      </ul>-->
<!--      <div class="right">-->
<!--        <button>avxx</button>-->
<!--        <button>avss</button>-->
<!--      </div>-->
    </div>


  </header>


</template>

<script>
export default {
  name: "Nav"
}
</script>

<style lang="less">
.navbar{
  position: fixed;
  right: 0;
  left: 0;
  background: gold;
  box-shadow: 0 1px 0 rgb(255 255 255 / 7%);
}
.container{
  padding: 0 120px;
  //.right{
  //  float: right;
  //  height: auto;
  //  button{
  //    height: auto;
  //  }
  //}
  .el-menu--horizontal{
    //width: 885px;
    //float: left;
    border-bottom:none;
    background: gold;
  }
}

</style>
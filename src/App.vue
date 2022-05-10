<template>

  <Nav />
  <div class="height"></div>
  <router-view />
</template>

<script>
import HelloWorld from "@/components/HelloWorld";
import { ElButton } from 'element-plus'
import Nav from "@/components/Nav";
import "./utils/reset.css"

export default {
  name: 'App',
  components: {
    HelloWorld,
    ElButton,
    Nav

  }
}
</script>

<style >
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /*margin-top: 60px;*/
}
.height{
  height: 58px;
}
</style>

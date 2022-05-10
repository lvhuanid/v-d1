<template>
  <div id="home">
    <div class="content">
      <p>
        For a guide and recipes on how to configure / customize this project,<br>
        check out the
        <a href="https://cli.vuejs.org" target="_blank" rel="noopener">vue-cli documentation</a>.
      </p>
      <h3>Installed CLI Plugins</h3>
    </div>
  </div>
</template>

<script>

export default {
name: "Home",
  components: {

  }
}
</script>

<style lang="less">
@width: 400px;
@height: 200px;

#home{
  width:100%;
  height: 100vh;
  display: flex;
  justify-content: center;
  //align-items: center;
  background: gray;
}
.content {
  width: @width;
  height: @height;
  background-color: yellowgreen;
}
</style>

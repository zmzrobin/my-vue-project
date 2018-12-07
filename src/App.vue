<template>
  <div id="app">
    <router-link to="/">首页</router-link>
    <router-link to="/todo">todo</router-link>
    <router-view/>
  </div>
</template>

<script>
  export default {
    name: 'App'
  }
</script>

<style lang="less">
  @import "css/common.less";

  #app {
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>

<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>

export default {
  name: 'app'
}
</script>

<style>
html,body {
  margin: 0;
  width: 100%;
  height: 100%;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  height: 100%;
  overflow: hidden;
}

a {
  text-decoration: none;
  color: #fff;
}
#app .con-wrap {
  padding-left: 160px;
  height: 100%;
  overflow-y: auto;
  overflow-x: hidden;
}
#app .con-wrap h3 {
  margin-top: 0;
  color: #324157;
}
#app .con-wrap.conCollapse {
  padding-left: 64px;
}
.el-menu-item [class^='el-icon-'] {
  vertical-align: middle;
  color: #ddd;
}
.el-submenu [class^='el-icon-'] {
  color: #ddd;
}
.el-submenu__title i {
  vertical-align: middle;
  color: #ddd;
}
</style>

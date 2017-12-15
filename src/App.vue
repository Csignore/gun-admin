<template>
  <div id="app">
    <el-container class="container">
      <el-header class="header">header</el-header>

      <el-main class="main">
        <el-aside class="aside">
          <div class="aside-item">相关数据</div>
          <div class="aside-item">用户管理</div>
          <div class="aside-item">事件管理</div>
          <div class="aside-item">事件进展</div>
        </el-aside>
        <el-main>main</el-main>
      </el-main>

      <el-footer class="footer">footer</el-footer>
    </el-container>
  </div>
</template>

<style>
.container {
  height: 100%;
  width: 100%;
  position: absolute;
  top: 0;
  bottom: 0;
}
.header {
  background-color: #ffc0cbbf;
}
.main {
  height: 100%;
  padding: 0 0 60px;
}
.aside {
  width: 25%;
  height: 100%;
  border-right: 1px solid #DFE4ED;
  padding: 0;
  float: left;
}
.footer {
  position: absolute;
  bottom: 0;
  background-color: #ffc0cbbf;
  width: 100%;
}
.aside-item {
  width: 100%;
  height: 40px;
  line-height: 40px;
  text-align: center;
}
.aside-item:nth-child(2n) {
  background-color: #ffc0cb38
}

</style>
<script>
export default {
  name: 'app'
};  
</script>


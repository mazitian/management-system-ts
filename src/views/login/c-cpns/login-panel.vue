<template>
  <div class="login-panel">
    <!-- 顶部的标题 -->
    <h1 class="title">后台管理系统</h1>

    <!-- 中间的tabs切换 -->
    <div class="tabs">
      <el-tabs type="border-card">
        <!-- 账号登录 -->
        <el-tab-pane name="account"> </el-tab-pane>
        <el-tab-pane label="Config">Config</el-tab-pane>
      </el-tabs>
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style lang="less" scoped>
.login-panel {
  width: 330px;
  margin-bottom: 150px;
  .title {
    text-align: center;
    margin-bottom: 15px;
  }
}
</style>

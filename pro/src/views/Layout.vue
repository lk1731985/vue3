<template>
  <div class="common-layout">
    <el-container>
      <el-aside width="200px"><ComAside /></el-aside>
      <el-container class="header-container">
        <el-header><ComHeader /></el-header>
        <RouterView />
      </el-container>
    </el-container>
  </div>
</template>

<style lang="less">
.el-header{
  display: flex;
  flex-direction:row
}
</style>
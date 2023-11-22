<template>
 
      <el-menu
        active-text-color="#ffd04b"
        background-color="#545c64"
        class="el-menu-vertical-demo"
        default-active="2"
        text-color="#fff"
        @open="handleOpen"
        @close="handleClose"
      >
        <!-- <h5 class="mb-2">Custom colors</h5> -->
        <el-menu-item index="4">
          <el-icon><setting /></el-icon>
          <span>Navigator Four</span>
        </el-menu-item>
        <el-sub-menu index="1">
          <template #title>
            <el-icon><location /></el-icon>
            <span>Navigator One999999999999999999999999999999999999999</span>
          </template>
          
            <el-menu-item index="1-1">item one99999999999999999999999999999999999999</el-menu-item>
            <el-menu-item index="1-2">item two</el-menu-item>
         
          
          
        </el-sub-menu>

        
        
      </el-menu>
  
</template>

<script lang="ts" setup>
const handleOpen = (key: string, keyPath: string[]) => {
  console.log(key, keyPath);
};
const handleClose = (key: string, keyPath: string[]) => {
  console.log(key, keyPath);
};
</script>
<style lang='less' scoped>
.el-menu {
    // border-right: none;
    height: 100vh;}
</style>

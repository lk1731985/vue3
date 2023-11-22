<template>
  <div class="content">
    <div class="l-content">
      <el-button>
        <el-icon><Menu /></el-icon>
      </el-button>
      <!-- <p>首页</p> -->
    </div>
    <div class="r-content">
      <el-dropdown>
        <span class="el-dropdown-link">
          <img src="../assets/user.jpg" class="u-img" />
        </span>
        <template #dropdown>
          <el-dropdown-menu>
            <el-dropdown-item>个人中心</el-dropdown-item>
            <el-dropdown-item>退出</el-dropdown-item>
          </el-dropdown-menu>
        </template>
      </el-dropdown>
    </div>
  </div>
</template>

<style>
.content {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 60px;
  width: 100%;
  background-color: #99a9bf;
  padding: 0 20px;

  .r-content {
    .u-img {
      width: 40px;
      height: 40px;
      border-radius: 50%;
      margin-right: 20px;
    }
  }
}
.el-header {
  padding: 0px;
}
</style>

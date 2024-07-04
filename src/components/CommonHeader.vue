<template>
  <div class="header">
    <div class="header-left">
      <span class="icon">
        <i class="el-icon-pear"></i>
      </span>
      <span class="text">大冻梨</span>
    </div>
    <div class="header-right">
      <el-dropdown>
        <img class="user-head" src="https://img1.baidu.com/it/u=4288672918,3634316930&fm=253&app=120&size=w931&n=0&f=JPEG&fmt=auto?sec=1693414800&t=6b1c863086ac70b499a052878e6ddf41" alt="">
        <el-dropdown-menu slot="dropdown">
          <el-dropdown-item disabled>个人中心</el-dropdown-item>
          <el-dropdown-item divided>退出</el-dropdown-item>
        </el-dropdown-menu>
      </el-dropdown>
    </div>
  </div>
</template>

<style lang="less" scoped>

</style>

<script>
export default {
  data() {
    return {};
  },
};
</script>
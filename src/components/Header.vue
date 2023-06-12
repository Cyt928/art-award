<script setup lang="ts">
</script>

<template>
    <el-menu
    default-active="index"
    class="app-menu"
    mode="horizontal"
    background-color="#545c64"
    text-color="#fff"
    active-text-color="#ffd04b"
  >
    <el-menu-item>LOGO</el-menu-item>
    <el-menu-item index="index">首页</el-menu-item>
    <el-menu-item index="info">赛事资讯</el-menu-item>
    <el-menu-item index="enter">填报参赛</el-menu-item>
    <el-menu-item index="display">作品展示</el-menu-item>
  </el-menu>

</template>

<style scoped>
.app-menu {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
}

</style>

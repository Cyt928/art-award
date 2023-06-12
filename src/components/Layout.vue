<script setup lang="ts">
import Header from './Header.vue';
import Footer from './Footer.vue';
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <div class="common-layout">
    <el-container>
      <el-header class="my-header"><Header /></el-header>
      <el-main class="main"><RouterView /></el-main>
      <el-footer class="my-footer"><Footer /></el-footer>
    </el-container>
  </div>
</template>

<style scoped>
.my-header {
    padding: 0 0;
}
.main {
    min-height: calc(100vh - 139px);
}
.my-footer {
    padding: 0 0;
}
</style>

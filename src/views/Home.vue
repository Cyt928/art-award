<script setup lang="ts">
</script>

<template>
  <div class="container">
    <el-row class="container-row" >
      <el-col :span="12">
        <el-carousel height="500px">
          <el-carousel-item v-for="item in 4" :key="item">
            <div class="carousel-item">
            <h3 class="small justify-center" text="2xl">{{'图' + item }}</h3>
            </div>
          </el-carousel-item>
        </el-carousel>
      </el-col>
    </el-row>
  </div>
</template>

<style scoped>
.container {
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: start;
    align-items: center;
    padding: 20px 50px;
}
.container-row {
  width: 100%;
}
.carousel-item {
  background-color: blueviolet;
  height: 500px;
  width: 100%;
}

</style>

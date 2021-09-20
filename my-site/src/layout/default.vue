<template>
  <div class="page-container">
    <el-container>
      <el-header>
        <Myheader />
      </el-header>
      <el-main>Main</el-main>
      <el-footer>Footer</el-footer>
    </el-container>
  </div>
</template>

<script>
import Myheader from "@/components/header/index.vue";
export default {
  components: {
    Myheader,
  },
};
</script>

<style>
</style>
<template>
  <div class="header">
    <el-row>
      <top-Bar></top-Bar>
    </el-row>
    <el-row>
      <search-Bar></search-Bar>
    </el-row>
  </div>
</template>

<script>
import topBar from "./topBar.vue";
import searchBar from "./searchBar.vue";
export default {
  components: {
    topBar,
    searchBar,
  },
};
</script>

<style>
</style>
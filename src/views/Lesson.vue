<template>
  <div class="home lesson">
    <el-header
      ><el-container><Header /></el-container
    ></el-header>
    <el-main>
      <el-container>
        <div class="lesson-main"></div>
      </el-container>
    </el-main>
    <el-footer> <Footer /> </el-footer>
  </div>
</template>

<script>
import Header from "../layout/Header.vue";
import Footer from "../layout/Footer.vue";
export default {
  name: "lesson-view",
  components: {
    Header,
    Footer,
  },
  data() {
    return {
      listFilter: [],
    };
  },
};
</script>
<style lang="scss" scoped></style>

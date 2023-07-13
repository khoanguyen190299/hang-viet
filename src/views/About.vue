<template>
  <div class="home about">
    <el-header
      ><el-container><Header /></el-container
    ></el-header>
    <el-main>
      <el-container>
        <div class="about-main"></div>
      </el-container>
    </el-main>
    <el-footer> <Footer /> </el-footer>
  </div>
</template>

<script>
import Header from "../layout/Header.vue";
import Footer from "../layout/Footer.vue";
export default {
  name: "about-view",
  components: {
    Header,
    Footer,
  },
};
</script>
<style lang="scss" scoped>
.about {
}
</style>

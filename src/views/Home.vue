<template>
  <div class="home">
    <el-header
      ><el-container><Header /></el-container>
    </el-header>
    <div class="side-bar"></div>
    <el-main>
      <div class="session">
        <el-container> a </el-container>
      </div>
    </el-main>
    <el-footer>
      <Footer />
    </el-footer>
  </div>
</template>

<script>
import Header from "../layout/Header.vue";
import Footer from "../layout/Footer.vue";
export default {
  name: "home-view",
  components: {
    Header,
    Footer,
  },
  data() {
    return {};
  },
  mounted() {},
  methods: {},
};
</script>
<style lang="scss">
.home {
  position: relative;
  display: flex;
  flex-direction: column;
  height: 100%;
  min-height: 100vh;
  .el-header {
    /* --el-header-padding: none; */
    --el-header-height: none;
    background-color: #1f2937;
    position: sticky;
    top: 0;
    z-index: 10000;
  }
  .el-main {
    /* --el-main-padding: 0 20px; */
    margin-bottom: 164px;
    flex: 1;
  }

  .el-footer {
    border-top: 1px solid #718096;
    padding-top: 23px;
    height: 100%;
  }

  .side-bar {
  }

  .session {
  }
}
</style>

<template>
  <div id="wrapper">
    <el-header>Header</el-header>
    <el-container>
      <el-aside width="200px">Aside</el-aside>
      <el-main>Main</el-main>
    </el-container>
    <el-footer>Footer</el-footer>
  </div>
</template>

<script>
  import SystemInformation from './LandingPage/SystemInformation'

  export default {
    name: 'landing-page',
    components: { SystemInformation },
    methods: {
      open (link) {

      }
    }
  }
</script>

<style lang="less">
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}
#wrapper {
  height: 100vh;
  display: flex;
  flex-direction: column;
}
.el-header {
  height: 26px;
  line-height: 26px;
  text-align: center;
}
.el-footer {
  height: 60px;;
  line-height: 60px;
  text-align: center;
}
</style>

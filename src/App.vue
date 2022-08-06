<template>
  <div id="app">
    黑马头条
    <!-- 路由出口 -->
    <router-view />
    <div>
      <i class="iconfont icon-shouji"></i>
    </div>
    <van-button type="primary">主要按钮</van-button>
    <van-button type="info">信息按钮</van-button>
    <van-button type="default">默认按钮</van-button>
    <van-button type="warning">警告按钮</van-button>
    <van-button type="danger">危险按钮</van-button>
    <div class="box">我是盒子</div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="less">
.box {
  width: 100px;
  height: 100px;
  background-color: pink;
}
</style>

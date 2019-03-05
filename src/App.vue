<template>
  <div class="app-container">
    <!-- 顶部header区域 -->
    <header class="mui-bar mui-bar-nav">
      <!-- <a class="mui-action-back mui-icon mui-icon-left-nav mui-pull-left" href></a> -->
      <h1 class="mui-title">Demo</h1>
    </header>

    <!-- 中间路由 router-view区域 -->
    <!-- 底部 tab bar -->
    <nav class="mui-bar mui-bar-tab">
      <a class="mui-tab-item mui-active" data-index="0">
        <span class="mui-icon mui-icon-home"></span>
        <span class="mui-tab-label">首页</span>
      </a>
      <a class="mui-tab-item" data-index="1">
        <span class="mui-icon mui-icon-contact"></span>
        <span class="mui-tab-label">会员</span>
      </a>
      <a class="mui-tab-item" data-index="2">
        <span class="mui-icon mui-icon-email"></span>
        <span class="mui-tab-label">购物车</span>
      </a>
      <a class="mui-tab-item" data-index="3">
        <span class="mui-icon mui-icon-search"></span>
        <span class="mui-tab-label">搜索</span>
      </a>
    </nav>
    <h1>123</h1>
  </div>
</template>

<script>
</script>


<style lang="scss" scoped>
.app-container {
  padding-top: 44px;
}
</style>

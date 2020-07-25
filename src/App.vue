<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<script>
/**
 * npm install 简历上面写了3年以上 : vue-router
 * vue-router 给我们提供了那些东西:
 * 1. 占位符 : <router-view></router-view> 跳转的a标签: <router-link to="/path">去path</router-link>
 * 2.Vue.use 方法: 就是让这个插件执行 install 方法 (Vue)
 * 3.两种路由模式: hash #/(hashchange) history: /(H5 History对象) pushState popState
 * 4.main.js里面, 根组件里面挂载了 router 节点 , 会向所有的组件里面混入(mixin) this.$route this.$router
 */
export default {
  name: 'app',
}
</script>>


<style>
</style>

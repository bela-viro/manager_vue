<template>
  <div>
    <h1>关于我们</h1>
    <p>这里是关于我们的页面内容。</p>
  </div>
</template>

<script>
export default {
  name: 'About',
  // 可以在这里添加组件的数据、方法等
  data() {
    return {
      message: '欢迎访问关于我们页面！'
    }
  }
}
</script>

<style scoped>
/* 可以在这里添加样式 */
div {
  text-align: center;
  padding: 20px;
}
</style>

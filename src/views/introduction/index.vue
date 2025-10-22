<template>
  <div class="app-container">
    <h2 style="margin: 0 0 16px;">项目介绍</h2>
    <p style="margin: 0 0 12px;">
      这是一个基于 Vue 2.x 和 Element UI 的中后台前端解决方案（vue-element-admin）。它使用 Vue Router + Vuex 构建，Webpack 3 打包，内置国际化、权限与动态路由、Mock 数据等能力，适合作为中后台管理系统的前端基础框架与示例集合。
    </p>

    <h3 style="margin: 24px 0 12px;">核心特性</h3>
    <ul style="padding-left: 18px; line-height: 1.8;">
      <li>权限与动态路由：基于角色的路由/菜单控制，动态侧边栏和面包屑</li>
      <li>标签页与缓存：多标签页（tags-view）与 keep-alive 页面缓存</li>
      <li>主题与样式：支持自定义 Element UI 主题</li>
      <li>丰富示例组件：富文本、Markdown、JSON 编辑器、剪贴板、全屏、拖拽、SplitPane、SVG 图标等</li>
      <li>表格场景：动态表格、拖拽表格、树形表格、内联编辑等</li>
      <li>文件相关：Excel 导入导出、ZIP 打包、上传（含七牛示例）</li>
      <li>数据可视化：ECharts 图表与仪表盘</li>
      <li>稳定性：401/404 页面、错误日志采集</li>
      <li>国际化：内置中英文 i18n</li>
    </ul>

    <h3 style="margin: 24px 0 12px;">运行与构建</h3>
    <ul style="padding-left: 18px; line-height: 1.8;">
      <li>安装依赖：npm install</li>
      <li>启动开发：npm run dev（默认 http://localhost:9527）</li>
      <li>构建测试环境：npm run build:sit</li>
      <li>构建生产环境：npm run build:prod</li>
    </ul>

    <h3 style="margin: 24px 0 12px;">更多资料</h3>
    <ul style="padding-left: 18px; line-height: 1.8;">
      <li><a href="https://panjiachen.github.io/vue-element-admin-site/#/" target="_blank" rel="noopener noreferrer">使用文档</a></li>
      <li><a href="https://github.com/PanJiaChen/vue-element-admin" target="_blank" rel="noopener noreferrer">Github 仓库</a></li>
      <li><a href="https://github.com/PanJiaChen/vue-element-admin/blob/master/README.zh-CN.md" target="_blank" rel="noopener noreferrer">README（中文）</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'Introduction'
}
</script>

<style scoped>
.app-container a {
  color: #409EFF;
}
</style>

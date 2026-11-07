# AI 产品经理 · 2D 教学动画学习页

新像素教育 AI 产品经理课程的 2D 教学动画集中学习页。全部 26 个动画集中在一个页面，支持播放、点选、筛选、搜索与学习进度记录。

- 在线地址：https://2013102249.github.io/ai-pm-animation-lab/
- 技术形态：单文件 HTML（原生 SVG / CSS / JS），零外部依赖，双击 `website/index.html` 即可本地预览
- 部署方式：GitHub Actions → GitHub Pages；推送 `website/**` 或工作流文件后自动重新发布
- 内容规模：6 个流程动画（55 节点 / 51 连线）、16 个步骤动画（83 步）、4 个概念对比（16 个差异点）

## 目录结构

```text
website/
  index.html          学习页（数据与渲染逻辑均已内联）
.github/workflows/
  deploy-pages.yml    GitHub Pages 自动部署工作流
```

## 内容与来源声明

页面中的动画数据整理自开源项目 [AliceDel66/ai-pm-roadmap](https://github.com/AliceDel66/ai-pm-roadmap)（维护者 Coriander）的 `src/data/animations/*.ts`，共 26 个已注册动画，标题、描述、节点、连线、步骤、示例、PM 提示与差异点均原样转换、未改写；页面渲染层与学习交互为独立重新实现。

原仓库采用 **Personal Use Only / 个人学习与非商业使用授权**：允许个人学习、研究与非商业分享（须注明来源），用于公司内训、商业课程、训练营、付费社群或对外发布前，需先取得维护者书面授权。本仓库保留此来源声明。

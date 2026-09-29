# 原料解决方案页面审核成品

独立审核页面，未接入主工程。静态 HTML/CSS/JS，无构建依赖。

## 查看
直接打开 index.html；建议使用 VS Code Live Server，以获得完整视频定位和全屏支持。
默认内容缩放 85%，范围 75%–125%，步长 5%；点击百分比重置。全屏按钮切换本页全屏。

## 结构
- index.html：独立页面
- css/raw-materials.css：独立 rm- 前缀样式
- js/raw-materials.js：缩放、返回顶部、指标悬停、弹窗、视频、报告翻页
- js/test-data.js：8 项实验指标的可编辑数据
- assets/images：页面图片
- assets/video：实验室视频
- assets/documents：原始报告、清单与报告页面预览
- assets/asset-manifest.json：原始素材映射及 SHA-256
- docs：需求、集成及验收说明

发布时保留上述 HTML/CSS/JS/assets 相对结构。不上传 PSD 和源说明资料。

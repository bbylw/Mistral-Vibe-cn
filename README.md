# Mistral Vibe 中文文档项目

这是一个基于 [Mistral Vibe 官方文档](https://docs.mistral.ai/mistral-vibe/introduction)构建的中文项目网站。该项目旨在为开发者提供一个美观、易读且本地化的 Mistral Vibe 命令行工具使用指南。

## 📂 项目结构

本项目包含以下核心页面，对应官方文档的各个章节：

| 文件名 | 页面标题 | 对应原文档 |
|--------|----------|------------|
| `index.html` | **CLI 介绍** (首页) | [Introduction](https://docs.mistral.ai/mistral-vibe/introduction) |
| `install.html` | **安装指南** | [Install](https://docs.mistral.ai/mistral-vibe/introduction/install) |
| `quickstart.html` | **快速入门** | [Quickstart](https://docs.mistral.ai/mistral-vibe/introduction/quickstart) |
| `configuration.html` | **配置指南** | [Configuration](https://docs.mistral.ai/mistral-vibe/introduction/configuration) |

### 资源目录
- `css/style.css`: 全局样式表，定义了深色科技风主题、响应式布局和组件样式。
- `js/main.js`: 交互逻辑，处理侧边栏高亮、代码块一键复制和平滑滚动。

## 🛠️ 技术栈与特性

- **纯原生实现**: 使用 HTML5, CSS3, Vanilla JavaScript 构建，无外部依赖。
- **视觉设计**:
  - 🌙 默认**深色模式**，契合开发者使用习惯和 Mistral 品牌色调。
  - 📱 **完全响应式布局**，适配桌面端和移动端阅读。
  - 🎨 使用 **CSS 变量** 管理颜色系统，易于维护。
- **交互功能**:
  - 📋 代码块自动添加**一键复制**功能。
  - 📍 智能**侧边栏导航**，自动高亮当前页面。
  - 🔗 优化的**锚点平滑滚动**体验。

## 🚀 如何使用

1. 将项目下载到本地文件夹。
2. 直接使用浏览器（Chrome, Edge, Firefox 等）打开 `index.html` 文件即可开始浏览。
3. 无需安装 Node.js 或启动本地服务器，纯静态文件即可运行。

## ⚠️ 说明

本项目为非官方中文文档，仅供学习和参考使用。最新和最准确的信息请以 [Mistral AI 官方文档](https://docs.mistral.ai/) 为准。

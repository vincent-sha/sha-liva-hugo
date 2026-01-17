<h1 align=center>Liva Hugo</h1> 

<p align=center>Liva 是一个现代且完全可定制的极简博客主题，能够帮助你创建任何类型的网站，无论是个人博客、旅行、新闻、摄影、科技、美食还是其他垂直领域。</p>

<h2 align="center"> <a target="_blank" href="https://demo.gethugothemes.com/liva" rel="nofollow">👀 演示项目</a> | <a  target="_blank" href="https://pagespeed.web.dev/report?url=https%3A%2F%2Fdemo.gethugothemes.com%2Fliva%2Fsite%2F&form_factor=desktopF">页面速度 (87%)🚀</a>
</h2>

<p align=center>
  <a href="https://github.com/gohugoio/hugo/releases/tag/v0.147.2" alt="Contributors">
    <img src="https://img.shields.io/static/v1?label=min-HUGO-version&message=0.147.2&color=f00&logo=hugo" />
  </a>

  <a href="https://github.com/gethugothemes/liva-hugo/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/gethugothemes/liva-hugo" alt="license"></a>

  <img src="https://img.shields.io/github/languages/code-size/gethugothemes/liva-hugo" alt="code size">

  <a href="https://github.com/gethugothemes/liva-hugo/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/gethugothemes/liva-hugo" alt="contributors"></a>

  <a href="https://twitter.com/intent/follow?screen_name=gethugothemes">
    <img src="https://img.shields.io/twitter/follow/gethugothemes?style=social&logo=twitter"
      alt="follow on Twitter"></a>
</p>


<p align="center">
  <img src="https://user-images.githubusercontent.com/37659754/67829978-3984f800-fb03-11e9-82d2-a38490c6ceaf.gif" width="100%" alt="Liva Blog template by themefisher">
</p>


## 🔑 关键特性
- 📄 7+ 预设计的页面
- 📊 支持 Google Analytics
- 🎨 使用 Hugo Pipe 进行 CSS 和 JS 打包
- 🅱️ 基于 Bootstrap
- ⚙️ 预定义 Netlify 设置
- ✉️ 支持联系表单
- 🔍 使用 fuse.js 进行搜索
- 🔄 启用 GDPR 合规
- 🚀 已针对 Google Page Speed 优化
- 🌐 Open Graph 元标签支持
- 🐦 Twitter Card 元标签支持

## 📄 6+ 预设计的页面

- ℹ️ 关于（About）页面
- 📄 博客列表（Post）页面
- 📝 文章详情（Post Single）页面
- 🗂️ 分类（Categories）页面
- 📄 分类详情页面
- 📞 联系（Contact）页面

## 📂 项目结构分析

本项目遵循 Hugo 标准的最佳实践，结构清晰：

- **核心配置 (`config/`)**: 采用模块化配置。
    - `hugo.toml`: 核心站点配置。
    - `languages.toml`: 多语言支持。
    - `menus.en.toml`: 导航菜单定义。
- **内容管理 (`content/`)**: 博客文章和静态页面存储在 `content/english/` 下。
- **主题布局 (`themes/liva-hugo/`)**: 包含所有 HTML 模板、基础样式和脚本。
- **资源文件 (`assets/`)**: 存放需要 Hugo 编译处理的 SCSS、JS 和图片。
- **数据文件 (`data/`)**: 存放结构化数据（如画廊配置）。
- **自动化脚本 (`scripts/`)**: 包含项目初始化和维护脚本。
- **部署配置**: 预配置了 Netlify (`netlify.toml`) 和 Vercel (`vercel.json`)。



## 🔧 本地开发

```bash
# 克隆仓库
git clone git@github.com:gethugothemes/liva-hugo.git

# 初始化项目
$ npm run project-setup

# 启动本地开发服务器
$ npm run dev
```

或查看 [完整文档](https://docs.gethugothemes.com/liva/?ref=github)。


<!-- edit with sitepins -->

## 📝 使用 CMS 编辑内容

此模板预配置了 [**Sitepins**](https://sitepins.com)，这是一个专为无缝内容管理设计的基于 Git 的无头 CMS。你可以在不触碰任何代码的情况下更新网站的文字、图片和配置。

**如何开始：**

点击下方的“使用 Sitepins 编辑”按钮，按照屏幕提示即可开始可视化编辑。

  <a target="_blank" href="https://app.sitepins.com/new/clone?name=Liva%20Hugo&repository=https://github.com/gethugothemes/liva-hugo/">
    <img src="https://sitepins.com/button.svg" alt="Edit with Sitepins">
  </a>


<!-- reporting issue -->
## 🐞 提交问题

我们使用 GitHub Issues 作为 liva 模板的官方错误跟踪器。请先搜索 [已存在的问题](https://github.com/gethugothemes/liva-hugo/issues)，可能已经有人报告过同样的问题。
如果你的问题或想法尚未被提出，请随时 [开启新 Issue](https://github.com/gethugothemes/liva-hugo/issues)。

## 📱 将你的网站提交到我们的展示厅

你正在使用 Liva Hugo 主题吗？欢迎提交到我们的 [展示厅（Showcase）](https://gethugothemes.com/showcase)。

我们的展示厅旨在向世界展示像你这样的人如何利用我们的 Hugo 主题创建出令人惊叹的网站，同时也展示了 Hugo 作为静态网站生成器的巨大潜力。

[提交](https://gethugothemes.com/showcase?submit=show) 你的 Liva Hugo 驱动的网站。

<!-- licence -->
## 📄 许可

Copyright &copy; Designed by [Themefisher](https://themefisher.com) & Developed by [Gethugothemes](https://gethugothemes.com)

**代码许可：** 在 [MIT](https://github.com/gethugothemes/liva-hugo/blob/master/LICENSE) 许可下发布。

**图片许可：** 图片仅用于演示目的。它们有各自的许可，我们没有获得分享这些图片的许可。


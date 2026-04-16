# Agom Markdown2HTML

> 把 AI 生成的 Markdown 和 Mermaid，快速变成可分享的 HTML / PDF。

如果这个项目刚好帮你省下了时间，欢迎先点一个 Star。

你的 Star，会让我继续把这个小工具打磨得更顺手。

AI 时代，内容写作越来越快，但“把 Markdown 和 Mermaid 变成一份能直接分享的页面”这件事，还是经常又碎又麻烦。

`Agom Markdown2HTML` 就是为这一步准备的：把你的 Markdown 文档和 Mermaid 图表，快速变成干净、好看、可分享的 HTML 页面，并且方便进一步导出为 PDF。

在线可用版本：

**[md.uncleliou.com](http://md.uncleliou.com/)**

无广告，不储存用户信息，到手就能用。

## 适合 AI 时代的内容工作流

现在很多内容都来自 AI 协作：

- AI 帮你起草 Markdown
- AI 帮你生成 Mermaid 流程图、架构图、时序图
- 你需要把结果发给同事、客户、团队或社区

问题通常不在“写出来”，而在“怎么优雅地分享出去”。

这个项目把最后一公里做掉了：

- 粘贴 Markdown，立即预览
- 自动渲染 Mermaid 代码块
- 导出独立 HTML，方便转发、归档、发布
- 打开 PDF 打印视图，直接另存为 PDF
- 支持导出 Mermaid PNG，便于单图复用

## 功能亮点

- 支持本地选择 `.md` / `.markdown` / `.txt` 文件
- 支持直接粘贴和编辑 Markdown 内容
- 自动识别并渲染 Mermaid 代码围栏
- 左侧编辑，右侧实时查看渲染结果
- 支持导出 HTML
- 支持 PDF 打印视图
- 支持导出 Mermaid PNG
- 支持拖拽文件导入
- 支持切换配色方案
- 单文件页面，部署和使用都很轻

## 适合谁用

- 用 AI 写技术文档、周报、方案说明的人
- 需要把 Mermaid 图表快速交付给别人看的人
- 想把 Markdown 变成更适合分享页面的人
- 希望部署一个纯静态、零后端的小工具的人

## 在线体验

直接访问：

**[md.uncleliou.com](http://md.uncleliou.com/)**

打开就能用，不需要注册，不需要登录，不需要上传到服务器处理。

## 本地使用

这个项目当前是一个单文件页面，直接打开即可：

```text
agomMD2HTML.html
```

使用方式：

1. 用浏览器打开 `agomMD2HTML.html`
2. 选择本地 Markdown 文件，或者直接粘贴内容
3. 自动预览 Markdown 与 Mermaid 渲染结果
4. 按需导出 HTML，或通过浏览器打印为 PDF

## 部署方式

这是一个纯前端静态页面，部署非常简单：

- Nginx
- GitHub Pages
- Vercel
- Cloudflare Pages
- 任意静态文件服务器

本质上只需要托管 `agomMD2HTML.html` 即可。

## 隐私说明

本工具所有内容均在前端本地处理：

- 不保存用户上传内容
- 不保存用户输入内容
- 不依赖后端文档处理服务
- 无广告

如果你只是想找一个放心、轻量、随手可用的 Markdown + Mermaid 分享工具，这一点很重要。

## 典型场景

- 把 AI 生成的产品方案转成可分享 HTML
- 把 Mermaid 架构图整理成 PDF 发给客户
- 把会议纪要、技术说明、项目文档快速美化后分享
- 把本地 Markdown 文档转成更适合展示的页面

## 为什么是这个项目

很多工具要么太重，要么要登录，要么要上传数据，要么广告太多。

这个项目的目标很直接：

**让 Markdown 和 Mermaid 内容，尽快变成一份可以发出去的 HTML / PDF。**

## 支持一下

如果你也认同“AI 时代的内容应该更容易分享”，欢迎点一个 Star。

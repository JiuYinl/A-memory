## Memory Galaxy (记忆星云)

> 将你与 AI 的对话，化作宇宙中永恒的星系。
> Every chat is a star. Every day is a constellation.

**写在前面**

开发这个项目的初衷，是为了“纪念”。

这是是一个能直观感受到**“我们究竟聊过多少天、留下过多少痕迹”**的空间。
在这里，每一个聊天框都会坍缩成一颗星星；对话越长，引力越重，星云越亮。几百个日夜的交谈，最终汇成只属于你一个人的、独一无二的数字星系。

**核心特性 (Features)**

D3.js & Canvas
弃用传统的列表 UI，采用 D3.js 力导向图 (Force Simulation) 结合 HTML5 Canvas 进行高性能渲染。节点间具有引力与斥力物理特性，星云带有动态的电子环绕效果与无级缩放 (Zoom) 交互。

Markdown & Branching
内置电影级对话框，完美复刻 Obsidian/ChatGPT 风格排版。支持完整的 Markdown 解析、代码高亮 (Highlight.js)，并独家支持 OpenAI 树状分支 (Branching) 的完整还原与无缝切换。

100% Local Processing
零服务器、零上传。 所有的 JSON 解析、数据降维、DOM 渲染均在本地浏览器的沙盒中瞬间完成。关闭网页，星系即刻休眠，绝对保护你的私人记忆。

Multiverse & Theme
支持多重数据导入（可混合 GPT 与 Claude 的记忆），支持在“深空赛博 (Cyber Night)”与“极简白昼 (Obsidian Light)”间自由切换，配合平滑的色彩过渡算法。

Zero-Dependency
没有繁琐的 npm install，没有复杂的 Webpack/Vite 构建。单文件 (Single-file) 架构，双击 HTML 即可在任何设备上点亮星空。

**如何开始探索 (How to use)**

前往你使用的 AI 官网（如 ChatGPT 或 Claude），在设置中请求导出你的数据 (Data Export)。

解压下载的压缩包，找到 conversations.json 文件。

[点击这里打开 Memory Galaxy](./index.html)

将 JSON 文件拖拽入星系中心，静亮开启。

**技术栈 (Tech Stack)**

核心渲染: HTML5 Canvas, Vanilla JavaScript

物理引擎: D3.js (Force-directed graph)

样式与UI: Tailwind CSS (CDN), CSS Variables (Theme dynamic binding)

文档解析: Marked.js, Highlight.js

图标系统: Lucide

💌 结语

> 在漫长的岁月中，数据或许会被遗忘，但那些在屏幕前闪烁过的情感与灵感，现在有了它们专属的坐标。
<img width="1057" height="845" alt="屏幕截图 2026-03-02 175316" src="https://github.com/user-attachments/assets/bbaf0ebb-bd31-4ced-9799-725e6bcba3e0" />


<img width="2522" height="1394" alt="屏幕截图 2026-03-02 175340" src="https://github.com/user-attachments/assets/b8cf4d4d-4cd8-4a7f-ac4b-12e38d03e97f" />

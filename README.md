# 🎬 Seedance 分镜工坊

将文案/剧本一键转化为 Seedance 2.0 结构化视频分镜提示词。

## 🚀 使用方法

### 打开方式

1. **双击** `index.html` 直接在浏览器中打开
2. 或者部署到任意静态托管服务（GitHub Pages / Vercel / Netlify）

### 配置 API Key

1. 点击右上角 **⚙️ 设置**
2. 填入 **DeepSeek API Key**（必填，用于分镜生成）
3. 填入 **Qwen-VL API Key**（可选，用于截图风格分析）
4. 点击保存

> API Key 仅存储在浏览器 localStorage 中，不会上传到任何服务器。

### 获取 API Key

| 服务 | 获取地址 | 用途 |
|------|---------|------|
| DeepSeek | https://platform.deepseek.com/api_keys | 分镜生成（必填） |
| Qwen-VL (DashScope) | https://dashscope.aliyun.com/apiKey | 截图风格分析（可选） |

### 使用流程

1. **选择预设模板**（可选）：产品广告 / 人物叙事 / UGC / 一镜到底 / 音乐卡点 / 视觉特效
2. **上传参考截图**（可选）：拖拽或点击上传风格参考图
3. **输入文案**：描述你想生成的视频内容或粘贴剧本
4. **调整参数**：选择时长（5/10/15秒）和画幅比例
5. **点击「生成分镜」**或按 `Ctrl+Enter`

### 输出内容

- 结构化分镜表：每个镜头包含画面描述、英文 Seedance Prompt、镜头语言、时长
- 📋 **复制全部 Prompt**：一键复制所有镜头的提示词
- 📥 **导出 Markdown**：下载完整分镜表为 .md 文件

## 🔧 技术栈

- 纯 HTML + CSS + 原生 JavaScript
- 零依赖、零构建、零安装
- 支持深色/浅色主题
- 响应式布局（桌面 + 移动端）

## 📋 模型

| 角色 | 模型 |
|------|------|
| 分镜生成 | DeepSeek-V4 Pro |
| 截图分析 | Qwen-VL Plus |

# 🛠️ 全能瑞士军刀 - 极简纯静态工具箱

[![Platform: HTML5/Vanilla JS](https://img.shields.io/badge/Platform-HTML5%20%2F%20JS-orange?style=flat-square)](javascript:void(0))
[![Style: Tailwind CSS v4](https://img.shields.io/badge/Style-Tailwind%20CSS%20v4-38bdf8?style=flat-square)](https://tailwindcss.com)
[![Privacy: 100% Local](https://img.shields.io/badge/Privacy-100%25%20Local-success?style=flat-square)](javascript:void(0))

这是一个**纯前端驱动、零后端依赖、极致轻量**的万能工具箱生态。内置多达 20+ 款涵盖开发调试、文本处理、日常效率的硬核微应用，采用单文件离线设计，拒绝任何数据上报，保障绝对的隐私安全。

---

## ✨ 核心亮点

*   **⚡ 极速响应**：基于 Tailwind CSS v4 现代化响应式布局，无任何笨重的前端框架（无 Vue/React 运行时），秒级加载。
*   **🔒 绝对隐私**：所有编解码、数据转换、哈希计算、图片压缩均在**浏览器本地内存**完成，绝不向任何第三方服务器上传你的隐私数据。
*   **🔍 智能检索**：主页支持**拼音简写**（如输入 `sjc` 搜时间戳、`ewm` 搜二维码）以及英文关键字的双重模糊联动过滤。
*   **📦 离线可用**：支持完整克隆到本地后直接双击 `index.html` 离线使用，无网环境下依然是你的得力助手。

---

## 🗺️ 工具全景矩阵

目前工具箱已完美收录以下三大模块，且在持续扩容中：

### 👨‍💻 开发调试类 (`dev`)
*   **🕒 时间戳转换**：Unix 时间戳与北京时间双向联动转换，带实时秒表。
*   **📊 JSON 助手**：复杂的 JSON 报文一键格式化缩进、校验或单行压缩。
*   **🔒 Base64 / URL 编解码**：支持中文字符集的高速本地安全互转。
*   **⏰ Cron 表达式**：Linux 标准定时任务通俗解读与高频预设。
*   **🛡️ 哈希生成器**：本地计算文本的 MD5、SHA-1、SHA-256、SHA-512。
*   **🔢 多进制转换**：2进制、8进制、10进制、16进制级联互换。
*   **🖼️ 图片转 Base64**：快速生成前端内联直用的 DataURI 字符串。
*   **🧪 正则测试器**：实时修饰符断言匹配，高亮显示捕获组。
*   **🔍 User-Agent 解析**：深度解构当前或输入的浏览器及网关内核。
*   **📟 摩尔斯电码**：经典的字母、数字与标准摩尔斯密文编解码。
*   **🧬 HTML 实体转义**：防止源码符号破坏富文本渲染的安全转义工具。
*   **🆔 UUID 生成器**：利用原生 Crypto 加密核心，批量生成唯一散列 ID。
*   **📊 CSV ↔ JSON**：打通 Excel 表格文本与标准开发对象的双向通道。

### 🔤 文本处理类 (`text`)
*   **📋 日常文本处理**：集成了字数统计、行数统计、大小写快捷转换、去两端空格。
*   **📝 Markdown 预览**：经典的分屏双栏排版，左边编写，右边实时同步渲染。
*   **✨ 花样特殊文本**：一键为文本附加气泡、删除线、上划线等极富个性的排版样式。
*   **⚖️ 文本差异对比**：逐行精确高亮展示两个版本文本的增加（+）或删减（-）。
*   **🧹 文本清洗去重**：智能精简行级重复字段，支持按字母表 A-Z 正向升序排列。

### 🎈 日常工具类 (`daily`)
*   **🎲 强密码生成器**：自定义长度与字符要素，本地随机输出高强度密码。
*   **📱 二维码生成器**：将网址或文本实时编译为二维码，支持无损打包下载。
*   **🖼️ 图片压缩转换**：纯前端离线裁剪、压缩原图体积，可在 JPG/PNG/WebP 间转换。
*   **🎨 颜色拾取转换**：网页标准色卡可视化拾取，支持 HEX、RGB、HSL 联动互转。
*   **💰 人民币大写转换**：严格遵循国内财务行政流程，一秒将数字金额转为大写。
*   **🧮 全前端计算面板**：提供常规四则运算、开根、乘方，界面清爽算账不累。
*   **🎨 极简协同白板**：Canvas 驱动的纯净画布，包含调色盘及笔触粗细调节，适合涂鸦灵感。
*   **🌐 全球时区对照**：北京、纽约、伦敦、东京等多地主流时区时间锁定联动。
*   **📐 常用单位换算**：涵盖多类国际与英制长度、质量标准的矩阵式同步换算。
*   **⏱️ 毫秒秒表/倒计时**：高精度静态本地计时器，番茄钟办公与效率管理好帮手。

---

## 🚀 快速开始

### 方式一：本地直接运行 (推荐)
1. 将本项目下载或通过 `git clone` 克隆到你的本地电脑。
2. 进入项目根目录，双击 `index.html`。
3. 即可直接在浏览器中打开使用。

### 方式二：静态托管部署
由于本项目是 **100% 纯静态文件**，你可以极其简单地将它托管到任何免费的静态文件服务器：
*   **GitHub Pages / Gitee Pages**：直接将代码推送到仓库，在 Settings 中开启 Pages 服务即可。
*   **Vercel / Netlify / Cloudflare Pages**：导入仓库，构建命令留空（或填 `html`），直接发布。

---

## 🛠️ 如何扩展并添加一个新小工具？

项目主页 `index.html` 采用了高度智能的联动引擎，如果你写了一个新的小工具，只需两步即可完美融入生态：

1. **新建工具文件**：在根目录下创建你的工具页面（例如 `my-tool.html`），建议引入相同的 Tailwind CDN 保持设计风格统一。
2. **在主页追加卡片**：打开 `index.html`，在对应的分类网格下添加以下卡片 HTML 片段：

```html
<div class="tool-card bg-white rounded-xl border border-slate-200 p-5 shadow-xs hover:shadow-md hover:-translate-y-0.5 transition-all duration-200" 
     data-cat="换成你的分类(dev/text/daily)" 
     data-keywords="换成你的检索词 英文 拼音简写 比如: gj">
    <div class="flex items-start justify-between">
        <span class="text-2xl p-2 bg-blue-50 rounded-lg">🚀</span>
        <span class="text-xs bg-blue-50 text-blue-700 font-medium px-2 py-0.5 rounded">卡片分类名</span>
    </div>
    <h3 class="mt-4 text-base font-bold text-slate-900">新工具名称</h3>
    <p class="mt-1 text-slate-500 text-xs line-clamp-2">简短的工具功能描述，最多显示两行。</p>
    <a href="./my-tool.html" class="mt-4 block text-center bg-slate-50 hover:bg-blue-50 text-slate-700 hover:text-blue-700 text-xs font-semibold py-2 rounded-lg border border-slate-100 transition-colors">打开工具</a>
</div>

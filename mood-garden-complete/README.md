# Mood Garden 情绪花园 · 完整交付包

本压缩包包含「Mood Garden 情绪花园」UX/UI 设计案例的全部可交付物，可直接用于作品集展示、网站嵌入、AI 画布生成与 Figma 二次编辑。

---

## 包内结构

```
mood-garden-complete/
├── README.md                              # 本说明
│
├── case-1/                                # 作品集网页完整包
│   ├── index.html                         # 作品集入口
│   ├── portfolio.css
│   ├── portfolio.js
│   └── mood-garden/
│       ├── mood-garden.html               # 高保真可交互原型
│       ├── mood-garden.css
│       └── mood-garden.js
│
├── mood-garden-prototype/                 # 可交互原型模组
│   ├── index.html                         # 原型入口
│   ├── screenshot-guide.html              # 截图导航页
│   ├── mood-garden.css
│   └── mood-garden.js
│
└── mood-garden-ai-canvas-kit/             # AI 画布 / Figma 素材包
    ├── README.md
    ├── design-system.md                   # 完整设计系统
    ├── pages.md                           # 页面结构说明
    ├── prompts/
    │   └── ai-canvas-prompt.txt           # Trae AI 画布 prompt
    └── assets/
        ├── brand/
        │   └── logo.svg
        ├── icons/
        └── illustrations/
```

---

## 三个子包分别怎么用

### 1. case-1 — 作品集网页

这是可以直接塞进 React/Vue/Angular 作品集网站里的静态页面。

**使用方式：**

将 `case-1` 文件夹整个复制到你项目的 `public/cases/case-1/` 目录下：

```
your-portfolio/public/cases/case-1/index.html
```

访问地址：

```
https://your-domain/cases/case-1/index.html
```

内部包含完整的设计案例叙事：背景与目标、角色、设计过程、最终方案、界面视觉、交互流程、设计系统、成果验证、复盘思考。

---

### 2. mood-garden-prototype — 可交互原型模组

这是带 iPhone 15 Pro 手机外框的高保真可交互原型，可单独打开演示，也可通过 iframe 嵌入到其他网站。

**直接打开完整演示：**

```
https://your-domain/mood-garden-prototype/index.html
```

**作为 iframe 嵌入（只显示手机，无标题和标注）：**

```html
<iframe
  src="https://your-domain/mood-garden-prototype/index.html#embed=1"
  width="450"
  height="920"
  frameborder="0"
  loading="lazy"
  title="Mood Garden 情绪花园可交互原型">
</iframe>
```

**截图模式（页面自动撑开，无需滚动）：**

```
https://your-domain/mood-garden-prototype/index.html#screenshot=1&tab=garden
```

也提供了 `screenshot-guide.html` 导航页，一键打开各个页面的截图模式。

---

### 3. mood-garden-ai-canvas-kit — AI 画布 / Figma 素材包

这是把设计喂给 Trae AI 画布、或在 Figma 中手动重建时需要的素材和说明。

**使用方法：**

1. 自己用截图模式截好 6 个核心页面的高清 PNG。
2. 复制 `prompts/ai-canvas-prompt.txt` 到 Trae AI 画布的提示词区域。
3. 将 `design-system.md` 和 `pages.md` 作为上下文上传/粘贴给 AI。
4. 按页面逐个上传截图，AI 会生成类似参考图中的多页面画布效果。
5. 生成后下载到 Figma 微调。

---

## 快速验证

所有资源均为纯静态文件，无需后端。任意一个子文件夹都可以直接用本地静态服务器预览：

```bash
cd case-1 && python3 -m http.server 8000
cd mood-garden-prototype && python3 -m http.server 8001
cd mood-garden-ai-canvas-kit && python3 -m http.server 8002
```

---

## 项目关键词

情绪记录、心理健康、植物养成、游戏化、自然治愈、年轻活力、iOS App、UX/UI、设计系统、Figma、AI 画布。

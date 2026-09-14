# Mood Garden 情绪花园 · AI 画布素材包

本素材包用于将「Mood Garden 情绪花园」设计项目导入 Trae AI 画布（或类似 AI 设计工具），生成可在 Figma 中进一步微调的高保真界面页面。

## 使用方式

1. **截取核心页面截图**
   - 打开原型网页，按 iPhone 15 Pro 尺寸 393 × 852 px 截取以下页面：
     - Onboarding 引导流程（3–4 页）
     - 花园首页
     - 记录页
     - 洞察页
     - 发现页
     - 我的页
   - 建议导出 2×（786 × 1704 px）高清 PNG。

2. **准备 AI 画布输入**
   - 将 `prompts/ai-canvas-prompt.txt` 的内容复制到 Trae AI 画布的提示词区域。
   - 按页面逐个上传截图。
   - 将 `design-system.md` 和 `pages.md` 作为上下文粘贴/上传给 AI。

3. **在 Figma 中微调**
   - AI 画布生成页面后，下载为 Figma 可编辑文件，或在 Figma 中导入生成的图片/组件。
   - 使用 `design-system.md` 中的 Token 统一颜色、字体、间距。

## 文件夹说明

```
mood-garden-ai-canvas-kit/
├── README.md                    # 本说明
├── design-system.md             # 完整设计系统（颜色 / 字体 / 间距 / 组件）
├── pages.md                     # 每个核心页面的结构与交互说明
├── prompts/
│   └── ai-canvas-prompt.txt     # 可直接复制给 Trae AI 画布的 prompt
└── assets/
    ├── icons/                   # 核心图标 SVG
    ├── illustrations/           # 植物 / 情绪插画 SVG
    └── brand/                   # 品牌 Logo SVG
```

## 项目关键词

情绪记录、心理健康、植物养成、游戏化、自然治愈、年轻活力、情感化设计、iOS App、Figma、AI 画布。

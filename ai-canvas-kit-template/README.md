# [项目名称] · AI 画布 / Figma 素材包

本素材包用于将「[项目名称]」设计项目导入 Trae AI 画布（或类似 AI 设计工具），生成可在 Figma 中进一步微调的高保真界面页面。

## 使用方式

1. **截取核心页面截图**
   - 打开原型网页，按目标设备尺寸截取每个核心页面。
   - 建议导出 2× 高清 PNG。

2. **准备 AI 画布输入**
   - 将 `prompts/ai-canvas-prompt.txt` 的内容复制到 Trae AI 画布的提示词区域。
   - 将 `design-system.md` 和 `pages.md` 作为上下文粘贴/上传给 AI。

3. **在 Figma 中微调**
   - AI 画布生成页面后，下载为 Figma 可编辑文件，或在 Figma 中导入生成的图片/组件。
   - 使用 `design-system.md` 中的 Token 统一颜色、字体、间距。

## 文件夹说明

```
[项目缩写]-ai-canvas-kit/
├── README.md                    # 本说明
├── design-system.md             # 完整设计系统
├── pages.md                     # 每个核心页面的结构与交互说明
├── prompts/
│   └── ai-canvas-prompt.txt     # 可直接复制给 AI 画布的 prompt
└── assets/
    ├── icons/                   # 核心图标 SVG
    ├── illustrations/           # 插画/品牌视觉 SVG
    └── brand/                   # Logo 等
```

## 项目关键词

[填写 5–10 个与项目相关的关键词，用于 AI 理解风格与领域]

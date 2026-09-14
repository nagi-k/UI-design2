# AI 画布素材包 · 复用说明

这个模板用于给新项目快速生成一套可以喂给 Trae AI 画布的素材包。

## 使用步骤

### 第一步：复制本模板

把 `ai-canvas-kit-template` 文件夹复制一份，改名为 `[项目名]-ai-canvas-kit`。

### 第二步：替换所有 `[填写]` 占位符

打开下面三个文件，按你项目的实际情况填写：

1. `README.md`
2. `design-system.md`
3. `pages.md`
4. `prompts/ai-canvas-prompt.txt`

### 第三步：准备 SVG 素材

把项目中的图标、插画、Logo 导出成 SVG，放到对应目录：

```
assets/
├── icons/           # Tab 图标、行内图标
├── illustrations/   # 页面插画、情绪插画
└── brand/           # Logo、品牌图形
```

如果没有 SVG，PNG 也可以，但 SVG 更适合 AI 识别和 Figma 编辑。

### 第四步：截取核心页面高清图

按设备尺寸截取每个核心页面，建议 2× 高清。使用项目原型中的 `#screenshot=1` 模式可以自动撑开页面、避免滚动。

### 第五步：喂给 AI 画布

1. 复制 `prompts/ai-canvas-prompt.txt` 的内容到 Trae AI 画布。
2. 把 `design-system.md` 和 `pages.md` 粘贴到上下文。
3. 按页面逐个上传截图。
4. 等待 AI 生成，再导入 Figma 微调。

## 检查清单

- [ ] 项目名称已替换
- [ ] 色彩 Token 已填写完整
- [ ] 字体、字号、间距已填写
- [ ] 每个核心页面有结构说明
- [ ] 多状态（空态/加载态/错误态）已说明
- [ ] 核心图标/插画已放入 assets
- [ ] prompt 已根据项目调整
- [ ] 已验证所有路径为相对路径

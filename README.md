# 朱阿祥 · 个人主页

复刻 [DeepSeek Harness](https://www.deepseek.com/harness/) 设计风格的个人主页，在线地址：

🔗 **https://zhuax-07.github.io/**

单文件、零构建依赖，深色主题 + 玻璃拟态 + 边缘高光。

## 本地预览

直接用浏览器打开 `index.html`，或：

```bash
npx serve .
```

## 设计风格对照（DeepSeek Harness → 本页）

| Harness 元素 | 本页对应 |
| --- | --- |
| 深色主题 `#0a0a0a` | `--ds-bg-page` |
| 品牌蓝 `#6799fe` / 浅蓝 `#73a3d2` | `--ds-brand` / `--ds-brand-light` |
| 玻璃拟态卡片 `hsla(0,0%,100%,.06)` | `.card` |
| 卡片顶部内高光 `inset 0 1px 0 hsla(...)` | `--ds-shadow-card` |
| Host Grotesk（展示字体） | Space Grotesk |
| DM Sans（正文） | DM Sans + Noto Sans SC |
| Fragment Mono（等宽） | JetBrains Mono |
| `npx` 复制代码块 | `profile.json` 终端卡片 |
| `Agent = Model + Harness` 公式 | 「深度学习 × 大模型应用 = 让 AI 落地」 |

## 定制

改主题色：修改 `index.html` 中 `:root` 的 `--ds-brand` 即可全局生效。

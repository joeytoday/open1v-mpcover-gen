# open1v-mpcover-gen

公众号封面图生成技能。4 种视觉风格，百炼 CLI 生图 → HTML 叠字 → Playwright 导出 PNG。

## 安装

把这句话发给你的 AI Agent：

> 帮我安装公众号封面生成技能。克隆 `https://github.com/joeytoday/open1v-mpcover-gen.git` 到 `~/.agents/skills/open1v-mpcover-gen`，然后进入目录执行 `npm install`。

或手动：

```bash
git clone https://github.com/joeytoday/open1v-mpcover-gen.git ~/.agents/skills/open1v-mpcover-gen
cd ~/.agents/skills/open1v-mpcover-gen && npm install
```

## 四种风格

| 风格 | 感受 | 文图模式 | 适合 |
|------|------|----------|------|
| 01 大字报 | "有态度" | 全幅背景+左遮罩 | 深度评论、历史、社会观察 |
| 02 杂志风 | "有品位" | 左文字+右方框图片 | 文化、人物、读书、设计 |
| 03 极简抽象 | "很清晰" | 纯色底+左文字+右图标 | 技术博客、产品更新 |
| 04 像素风 | "有趣" | 全幅背景+左遮罩 | 游戏、趣味技术、怀旧 |

<img width="2836" height="1598" alt="image" src="https://github.com/user-attachments/assets/29d1a2e7-6b74-44fb-ae10-06e94caa0063" />


## 使用

对 Agent 说：

```
帮我给这篇文章做个公众号封面
```

触发词：`公众号封面`、`封面生成`、`cover`、`生成封面`、`做个封面`

## 依赖

- [百炼 CLI](https://bailian.console.aliyun.com/cli) — AI 生图（首次使用时自动检测安装）
- [Playwright](https://playwright.dev/) — HTML → PNG 渲染（`npm install` 自动安装）

## License

MIT © [joeytoday](https://github.com/joeytoday)

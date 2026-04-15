# ✨ English Learning Studio

> AI-powered English writing practice — Grammar Check · Sentence Upgrade · Typing Practice, all in one HTML file.

**[🔗 Live Demo →](https://tianhaoyang778-hue.github.io/english-learning-studio/)** ｜ **[📄 Product Page →](https://tianhaoyang778-hue.github.io/english-learning-studio/landing.html)**

---

## What is this?

English Learning Studio is a single-page web app for English learners who want to improve their writing. It uses AI to check grammar, upgrade sentences, and includes a MonkeyType-style typing trainer — zero installation, just open and use.

### Core Features

**🔍 Grammar Check**
- Paste your essay → AI identifies every grammar error
- Each error becomes a flippable quiz card (tap to see detailed explanation)
- Cards show: error → correction, grammar category, rule explanation, example sentence
- Save cards to your **Grammar Bank** for long-term review
- Filter saved cards by category (Past Tense, Subject-Verb Agreement, etc.)

**✨ Sentence Upgrade**
- AI rewrites your text at 3 levels: Intermediate → Advanced → Native-like
- One-click save entire upgraded essays to your **Essay Bank**
- Select any word or sentence → save to your **Phrases Bank** (好词好句库)
- Compare original vs upgraded versions side by side

**⌨️ Typing Practice**
- MonkeyType-style typing trainer, 100% local (no API needed)
- **Words mode**: Random common English words (10/25/50/100)
- **Custom mode**: Paste your own essay to practice typing
- Real-time WPM, accuracy, and time tracking

### Data Storage

All saved data (Grammar Bank, Essay Bank, Phrases Bank) is stored in your browser's `localStorage`. Data persists across sessions but stays private to your browser — no accounts, no server.

---

## Quick Start

### Step 1 — Get a free API key

| Provider | Model | Cost | Link |
|---|---|---|---|
| Zhipu AI | GLM-4-Flash | Free (20M tokens for new users) | [bigmodel.cn](https://bigmodel.cn) |
| Google Gemini | Gemini 2.0 Flash | Free tier | [aistudio.google.com](https://aistudio.google.com/app/apikey) |

### Step 2 — Open the app

**Option A: Use Online (Recommended)**
Visit the [Live Demo →](https://tianhaoyang778-hue.github.io/english-learning-studio/)

**Option B: Run Locally**
1. Download `index.html`
2. Open it in any modern browser (Chrome, Firefox, Safari, Edge)
3. Click **⚙️ API Settings** and paste your API key
4. Start learning

> 🔒 Your API keys are stored only in your own browser's localStorage — never transmitted anywhere except directly to the AI provider's API.

---

## Tech Stack

- **Frontend**: React 18 + Babel (in-browser transpilation)
- **AI**: Zhipu GLM-4-Flash · Google Gemini 2.0 Flash · user-supplied keys
- **Storage**: Browser localStorage (no backend)
- **Deployment**: Single HTML file, GitHub Pages compatible

---

## Project Structure

```
english-learning-studio/
├── index.html      # Main application
├── landing.html    # Product landing page
├── README.md       # This file
└── LICENSE
```

---

## Development

Built through **vibe coding** — iterative collaboration between a human product designer and Claude AI.

- V1: Grammar Check + Sentence Upgrade + Typing Practice
- V2: Fixed API calls for long texts (200+ words)
- V3: Grammar Bank with flip quiz cards
- V4: Essay Bank + save buttons on upgrade results
- V5: Phrases Bank with text selection → save
- V6: Dual AI provider (Zhipu + Gemini), optimized prompts
- V7: User-configurable API keys, removed hardcoded credentials

---

## License

Source Available License — free for personal and educational use.  
Commercial use requires permission. See [LICENSE](./LICENSE) for details.

---

## Acknowledgments

- [Zhipu AI](https://bigmodel.cn) — Free GLM-4-Flash API
- [Google AI Studio](https://aistudio.google.com) — Gemini API
- [MonkeyType](https://monkeytype.com) — Typing practice inspiration
- Built with [Claude](https://claude.ai) by Anthropic

---

---

# ✨ English Learning Studio（中文说明）

> AI 驱动的英语写作练习工具 — 语法检查 · 句子升级 · 打字练习，一个 HTML 文件搞定。

**[🔗 在线体验 →](https://tianhaoyang778-hue.github.io/english-learning-studio/)** ｜ **[📄 项目介绍页 →](https://tianhaoyang778-hue.github.io/english-learning-studio/landing.html)**

---

## 这是什么？

English Learning Studio 是一个为英语学习者设计的单页网页应用，用 AI 检查语法错误、升级句子表达，并内置 MonkeyType 风格的打字练习器。无需安装，打开即用。

### 核心功能

**🔍 语法检查**
- 粘贴文章 → AI 识别所有语法错误
- 每个错误变成可翻转的记忆卡片（点击查看详细解释）
- 卡片显示：错误 → 正确、语法分类、规则说明、例句
- 保存卡片到**语法错题本**，长期复习
- 按类别筛选（时态、主谓一致等）

**✨ 句子升级**
- AI 将你的文本改写为三个层次：中级 → 高级 → 母语级
- 一键保存整篇升级文章到**文章库**
- 划选任意词句 → 保存到**好词好句库**
- 对比原文与升级版

**⌨️ 打字练习**
- MonkeyType 风格，纯本地运行（不需要 API）
- **单词模式**：随机常用英语单词（10/25/50/100 个）
- **自定义模式**：粘贴自己的文章练习打字
- 实时显示 WPM、准确率、用时

### 数据存储

所有保存的数据（语法错题本、文章库、好词好句库）存储在浏览器的 `localStorage` 中，跨会话持久保存，完全私密，无需账户。

---

## 快速开始

### 第一步 — 获取免费 API Key

| 服务商 | 模型 | 费用 | 获取链接 |
|---|---|---|---|
| 智谱 AI | GLM-4-Flash | 免费（新用户 2000 万 token）| [bigmodel.cn](https://bigmodel.cn) |
| Google Gemini | Gemini 2.0 Flash | 免费额度 | [aistudio.google.com](https://aistudio.google.com/app/apikey) |

### 第二步 — 打开应用

**方式一：直接在线使用（推荐）**
访问[在线体验链接 →](https://tianhaoyang778-hue.github.io/english-learning-studio/)

**方式二：本地运行**
1. 下载 `index.html`
2. 用任意现代浏览器打开（Chrome、Firefox、Safari、Edge）
3. 点击顶部 **⚙️ API Settings**，粘贴你的 API Key
4. 开始学习

> 🔒 API Key 仅保存在你自己浏览器的 localStorage 中，不会传输到任何地方，只在调用 AI 接口时直接发送给对应的 AI 服务商。

---

## 适用场景

- **雅思 / 托福备考** — 检查作文语法，学习升级表达，积累好句
- **日常英文写作** — 邮件、报告、论文发出前先检查润色
- **语法薄弱点突破** — 错题卡片自动分类，精准复习
- **打字速度训练** — 粘贴范文练手感，边打字边熟悉好表达

---

## 技术栈

- **前端**：React 18 + Babel（浏览器内编译）
- **AI**：智谱 GLM-4-Flash · Google Gemini 2.0 Flash · 用户自填 Key
- **存储**：浏览器 localStorage（无后端）
- **部署**：单 HTML 文件，兼容 GitHub Pages

---

## 开发历程

本项目通过 **vibe coding** 方式构建——人类产品设计师与 Claude AI 迭代协作。

- V1：语法检查 + 句子升级 + 打字练习
- V2：修复长文本（200+ 词）API 调用
- V3：语法错题本 + 翻转记忆卡片
- V4：文章库 + 升级结果保存按钮
- V5：好词好句库 + 划选保存
- V6：双 AI 提供商（智谱 + Gemini），优化 prompt
- V7：用户自填 API Key，移除硬编码密钥

---

## 开源协议

Source Available License — 个人和教育用途免费使用。  
商业使用需获得授权，详见 [LICENSE](./LICENSE)。

---

## 致谢

- [智谱 AI](https://bigmodel.cn) — 免费 GLM-4-Flash API
- [Google AI Studio](https://aistudio.google.com) — Gemini API
- [MonkeyType](https://monkeytype.com) — 打字练习设计灵感
- 由 [Claude](https://claude.ai)（Anthropic）协助构建

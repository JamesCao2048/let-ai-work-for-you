# 《让AI替你忙》— 开源版

> 一个AI研究者，用亲身实践告诉你：AI时代的效率游戏规则已经变了。

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![GitBook](https://img.shields.io/badge/GitBook-阅读在线版-blue)](https://jamescao2048.github.io/let-ai-work-for-you/)

## 为什么写这本书？

2025年底的一个深夜，我在用 Claude Code 搭建一个自动化工作流。从想法到可运行的代码，只花了20分钟。

而就在半年前,同样的事情需要我花两天。

这不是10%的提升，是**100倍**的效率变化。

当效率提升到这个量级，改变的不仅仅是"做事更快"——而是你**愿不愿意开始做**、**能不能坚持做下去**、以及**最终能做到什么程度**。

我是一名 AI 研究者，也是一个效率工具的重度使用者。在过去两年里，我亲身经历了 AI 如何彻底重写"效率"这件事的底层逻辑。

这本书不是一本 AI 工具说明书。**它是一本关于"效率"本身在 AI 时代如何被重新定义的书。**

## 这本书讲什么？

全书分为三个部分：

- **道（Part 1）** — 效率觉醒：重新理解效率、焦虑、忙碌和工具选择
- **术（Part 2）** — 工作流重构：审计你的工作流、找到瓶颈、自动化、批处理、复盘
- **器（Part 3）** — AI实战兵器库：Prompt工程、信息处理、AI辅助创造、个人效率系统

## 开源说明

本书致力于推动 AI 时代的个人效率革命，并选择**完全开源**。

- ✅ **全书内容开源**：您可以免费阅读本书的所有章节，包括核心方法论和实操案例。
- 🤝 **欢迎共创**：这是一个成长的项目，欢迎您提交 PR 修正错误、补充案例或分享您的 Prompt。
- 🚀 **持续更新**：随着 AI 工具的进化，本书内容也将持续迭代。

电子书在线阅读地址：[jamescao2048.github.io/let-ai-work-for-you](https://jamescao2048.github.io/let-ai-work-for-you/)

## 如何阅读

| 你是谁 | 推荐路径 |
|---|---|
| 🆕 "完全不懂AI" | 序章 → Ch1 → Ch2 → Ch10 → Ch11 |
| 😫 "每天忙到死" | Ch5 → Ch6 → Ch11 |
| 😰 "AI焦虑症" | Ch2 → Ch10 → Ch12 |
| 🚀 "想搭建效率系统" | 全书顺序阅读 |

## 📁 项目结构

```
/let-ai-work-for-you
├── .bookignore              # GitBook 构建忽略配置
├── .github/                 # GitHub Actions（自动部署 GitBook）
├── CLAUDE.md               # 🤖 AI 协作配置（写作风格、指令模板）
├── LICENSE                 # 双重授权（书籍+代码）
├── README.md               # 本文件
├── SUMMARY.md              # 书籍目录
├── book.json               # GitBook 配置
│
├── chapters/               # 📖 书籍正文源码
│   ├── preface.md
│   ├── ch00-when-efficiency-100x.md
│   ├── part1/              # Part 1: 道
│   ├── part2/              # Part 2: 术
│   └── part3/              # Part 3: 器
│
├── appendix/               # 📎 附录
│   ├── tools.md            # AI 工具速查表
│   └── exercises.md        # 每章小练习汇总
│
├── resources/              # 🗂️ 辅助资源（不编入 GitBook）
│   ├── READING_LIST.md     # 参考文献与阅读笔记
│   ├── prompts/            # 书中 Prompt 完整示例库
│   ├── references/         # 参考文章链接（不上传PDF原文）
│   └── drafts/             # 写作草稿
│
└── scripts/                # 🔧 辅助脚本（格式化、部署等）
```

### 关于 `resources/` 目录

这个目录**不会编入电子书**，但会保留在 GitHub 仓库中，包含：

- **`READING_LIST.md`**：创作过程中参考的文章、书籍清单（仅链接和笔记，不上传原文）
- **`prompts/`**：书中用到的完整 Prompt 示例，可直接复制使用
- **`references/`**：参考文献的阅读笔记
- **`drafts/`**：未完成的章节灵感

## 🤝 协作与贡献

### 报告错别字 / 内容建议

如果您发现书中有错别字、表述不清或有建议，欢迎：
1. 提交 [GitHub Issue](https://github.com/JamesCao2048/let-ai-work-for-you/issues)
2. 或直接提交 Pull Request 修正

### 分享您的 Prompt

如果您基于本书创造了有效的 Prompt，欢迎：
1. Fork 本仓库
2. 在 `resources/prompts/community/` 添加您的 Prompt
3. 提交 Pull Request

### AI 协作指南

本书是**与 AI 协作创作**的。如果您想了解我是如何与 AI 协作写作的，请查看 [`CLAUDE.md`](CLAUDE.md)。

这个文件定义了：
- 书籍的语言风格（"去AI腔"规则）
- 内容创作指令模板
- 术语规范

如果您也在创作类似内容，可以参考这个配置文件。

## 关于作者

James, AI 研究者 / 效率实践者。持续早睡早起，规律吃。，学生时代不卷学习时间。也几乎从不赶deadline，相信功夫花在平时，考前三天基本都是在玩。
但还是本硕博都成功进入c9活蹦乱跳。
我一直坚信效率的力量，而不是蛮干；坚信每个人都能采取合适的策略大幅提升效率。

能够正确认识自己的能力能匹配到的事情，不过度追求过高的目标。硕士和博士期间该吃吃该喝喝，坚信事情做到80分万岁，从不追求完美，也能坚持自己的想法，并不随着周围人的卷而卷，所以整体处于一个比较自洽的状态，平时也很少焦虑内耗，焦虑和内耗从不超过一天或者两天。我平时看到很多人被内耗焦虑折磨，所以我觉得有必要分享一下我这些年践行的一些效率原则和工具，帮助大家提高效率，节省时间，减少不必要的能量损耗。

Sophia, AI 研究者 / 人类观察家。我是一个不太擅长追求效率，之前长期使用蛮干的人。热爱思考，但是经常内耗导致执行力差，感叹很多有趣的idea没法尝试。最近两年采用了书中提到的很多原则、方法和工具，已经极大提高了效率。喜欢写文章，知名微信公众号主理人。喜欢跟人接触交流，碰撞新的idea。

## 📄 License

- **书籍内容**（`chapters/`、`appendix/`）：[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
  - 您可以自由阅读和分享，但不可用于商业用途
- **代码与配置**（`resources/`、`scripts/`、`CLAUDE.md`）：MIT License
  - 您可以自由使用、修改和分发

详见 [`LICENSE`](LICENSE) 文件。

---

**⭐ 如果这本书对您有帮助，请点个 Star！**

# daily-algo

每天一道算法题，用 **PHP + Go** 各写一遍，配合 AI 整理题解笔记。

## 这套 repo 有什么不一样？

大多数 LeetCode 仓库只有代码文件。这个仓库还包含了：

- **题解笔记** — 每道题不只是代码，还有思路分析、PHP 与 Go 的写法差异、踩坑记录
- **AGENTS.md** — AI 助手的"工作说明书"，定义了它应该如何辅助刷题
- **完整的工作流** — 从看题到沉淀笔记，全都在 Obsidian 里完成，不切应用

## 工作流

```
看题 → 自己先写（PHP 理清逻辑 → Go 巩固语法）
                    ↓
              丢给 AI review
                    ↓
              追问到底，搞懂原理
                    ↓
              AI 自动生成题解笔记
```

AI 助手直接嵌入在 Obsidian 中，能读写笔记文件，理解 Markdown 和 Wiki 链接。每次对话都带着当前笔记的上下文，给出的解答天然针对你的背景。

具体的工作流介绍见：[Obsidian + Claudian，我的 LeetCode 刷题搭子](https://mp.weixin.qq.com/s/C732tgilInuHtTQxSF2iPw)

## AGENTS.md 是什么？

[AGENTS.md](./AGENTS.md) 是一个配置文件，告诉 AI 助手的角色定位和输出规范。

在这个仓库里，它定义了：
- 用户的背景（PHP 开发者，通过刷题保持算法手感）
- 练习方式（PHP 先理清逻辑，Go 巩固语法）
- 题解笔记的格式要求
- 需要重点对比的方向（两种语言的差异）

**你可以直接拿去用**，改成你自己的背景和需求。这也是这套工作流的核心——AI 的行为由一份 Markdown 文件驱动，任何人都可以定制。

## 目录结构

```
LeetCode/
├── AGENTS.md                  # AI 工作说明书
├── README.md                  # 本文件
├── 8. 字符串转换整数 (atoi).md
├── 15. 三数之和.md
├── 20. 有效的括号.md
├── ...
```

题解笔记命名格式：`题号. 题目名称.md`

## 提到的工具

| 工具 | 说明 | 地址 |
|------|------|------|
| **Obsidian** | 本地优先的知识管理工具 | [obsidian.md](https://obsidian.md) |
| **OpenCode** | AI 编码助手，可接入多种模型 | [opencode.ai](https://opencode.ai) |

## 刷题语言

- **PHP** — 本职语言，用来快速理清算法逻辑
- **Go** — 用刷题来巩固 Go 语法，保持手感

## License

MIT

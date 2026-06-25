# AI 学习教练（ai-learning-coach-zh）

一个中文 Codex Skill，用来把 AI 从“解释器”变成“学习教练”。

它适合用在这些场景：

- 你想系统学习一个新主题，但不知道从哪里开始
- 你希望 AI 帮你制定可执行学习计划
- 你学完一部分内容后，想让 AI 逐题考你
- 你想把知识压缩成一页速查表
- 你感觉自己懂了，但讲不清楚，想用费曼方法修补理解

## 核心方法

这个 Skill 来自一篇关于如何用 Claude 高效学习的文章启发：

https://x.com/sairahul1/status/2068250224532050089

它把学习过程拆成 6 个模块：

1. **学习阶梯**：把主题拆成 5 个阶段，从完全新手到自信实践者。
2. **20 小时学习计划**：用 80/20 原则，先学习最有用的核心部分。
3. **资源筛选**：只推荐 5 个高杠杆资源，减少资料噪音。
4. **主动回忆测验**：让 AI 一题一题考你，暴露真实知识缺口。
5. **一页速查表**：把知识压缩成 5 分钟可复习的结构。
6. **费曼循环**：你讲回来，AI 找漏洞，再补课，直到讲清楚。

## 安装方式

把仓库克隆到 Codex Skills 目录：

```bash
git clone https://github.com/pupuqiu/ai-learning-coach-zh.git ~/.codex/skills/ai-learning-coach-zh
```

如果目录已存在，可以先删除旧版本再克隆：

```bash
rm -rf ~/.codex/skills/ai-learning-coach-zh
git clone https://github.com/pupuqiu/ai-learning-coach-zh.git ~/.codex/skills/ai-learning-coach-zh
```

安装后重启 Codex 或新开一个会话，让技能列表重新加载。

## 使用示例

```text
使用 ai-learning-coach-zh，帮我系统学习大模型应用开发。
```

```text
我刚学完 RAG，使用 ai-learning-coach-zh 考考我。
```

```text
使用 ai-learning-coach-zh，用费曼方法帮我理解 Transformer。
```

```text
使用 ai-learning-coach-zh，帮我把提示词工程整理成一页速查表。
```

## 适合谁

- AI 产品经理
- 独立开发者
- 学习型创作者
- 想用 AI 提升学习效率的人
- 正在搭建个人知识系统的人

## 文件结构

```text
ai-learning-coach-zh/
├── SKILL.md
└── agents/
    └── openai.yaml
```

## 设计原则

这个 Skill 不追求让 AI “讲得更多”，而是让 AI 帮你：

- 规划路径
- 安排练习
- 主动测试
- 发现缺口
- 压缩复习
- 反复修补理解

真正的学习不是获得答案，而是形成反馈循环。

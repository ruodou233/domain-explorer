# 陌生领域速通｜Topic Research & Learning

Get up to speed on a new topic through its history, competing approaches, expert debates, and practical experience.

很多人问我为什么学各种领域都这么快，所以我把核心技巧开源出来。这个 skill 帮你给陌生的技术、行业、学科或概念体系画一张地图：它怎么发展到今天，有哪些路线，专家在争什么，实际干这行的人又怎么看。先看懂来龙去脉，再决定自己往哪钻。

## 什么时候拿出来用

- **从零入门**：“我想了解机器人领域，先帮我建立整体认识。”从关键问题和发展路线讲起，把零散名词放回各自的位置，知道接下来该学什么。
- **看懂一个行业**：“储能行业有哪些玩家，各自在解决什么问题？”把主要路线、参与者和差异放在一起，方便继续研究某家公司或某项技术。
- **弄清专家为什么吵起来**：“关于大模型推理能力，大家的分歧到底在哪？”分别看各方主张和依据，再对照实践中已经发生的事。
- **补上熟悉领域的盲区**：“我会用数据库，但想系统了解不同数据库为什么会出现。”沿着旧问题、新解法和新代价往下走，把会用的东西串成知识体系。

对 Agent 说“帮我了解 XX 领域”或“我想入门 XX”，可以选择速览、入门、深入三档深度。

## 它怎么工作

核心理念：理解一个领域最好的方式不是罗列概念，而是理解**每个东西是为了解决什么问题而被发明的**，以及**专家共识和从业者认知是两个独立证据源，必须分开采集、显式对照**。

四条研究线：

- **历史演化**：从起源到现在的演进链，每个节点回答"解决了什么问题"，确有代价或新问题时一并记录
- **竞争格局**：当前主要玩家/流派/路线，核心主张与差异维度，标注时间窗口
- **专家共识与争议**：主流共识清单 + 活跃争议清单（双方立场、代表人物）
- **公开实践信号**：搜索 Reddit / HN / 知乎 / 垂直论坛，只采用对象自身原生正向计数不少于 10 的讨论，与专家共识做四分类对照（相互印证 / tacit knowledge / 民间迷思 / 实践已投票），关键判断标注来源、时间窗口、证据强度（强/中/弱）和适用边界

## 安装

### Claude Code

```bash
git clone https://github.com/ruodou233/domain-explorer.git ~/.claude/skills/domain-explorer
```

### Codex / 其他 Agent

克隆到对应的 skill 目录，或在 prompt 中引用 `SKILL.md` 全文即可。

## 反馈与作者

这个 skill 我长期维护。如果你有修改方案、发现问题、或者改出了更好的版本，欢迎通过以下任一渠道找到我：

- GitHub：本仓库提 issue 或 PR
- 小红书：错误乱码
- 微信公众号：能工智人错误乱码
- B站：若逗道人

## 相关 Skill 推荐

<!-- 本表由维护脚本生成，勿手工编辑 -->
- [improve-product-plan](https://github.com/ruodou233/improve-product-plan)：想做成一个作品？把应用、工具、自动化和游戏想法打磨成能开工的方案<br>Plan product requirements and MVP scope, then produce a development spec with milestones and acceptance criteria.
- [de-ai-taste](https://github.com/ruodou233/de-ai-taste)：AI 写的中文一眼就能看出来？逐条找出 AI 味、给出具体修改建议，让文章、讲稿和文案读起来像你写的。<br>Review AI-written Chinese and suggest edits to remove formulaic phrasing while preserving the author's voice.

完整目录见 [GitHub 主页](https://github.com/ruodou233)。

## License

MIT

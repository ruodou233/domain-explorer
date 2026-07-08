# domain-explorer 领域探索器 Skill

很多人问我为什么学各种领域都这么快，所以我把核心技巧开源出来。这个 skill 四线并行采集一个陌生领域的历史演化、竞争格局、专家共识与争议、实践信号，帮你在几分钟内建立全景认知，而不是花几周慢慢摸索。

## 它怎么工作

核心理念：理解一个领域最好的方式不是罗列概念，而是理解**每个东西是为了解决什么问题而被发明的**，以及**专家共识和从业者认知是两个独立证据源，必须分开采集、显式对照**。

四条并行研究线：

- **历史演化**：从起源到现在的演进链，每个节点回答"解决了什么问题 / 付出了什么代价 / 引入了什么新问题"
- **竞争格局**：当前主要玩家/流派/路线，核心主张与差异维度，标注时间窗口
- **专家共识与争议**：主流共识清单 + 活跃争议清单（双方立场、代表人物）
- **从业者视角**：搜索 Reddit / HN / 知乎 / 垂直论坛的高赞从业者认知，与专家共识做四分类对照（相互印证 / tacit knowledge / 民间迷思 / 实践已投票），每条带证据等级和适用边界

## 安装

### Claude Code

```bash
git clone https://github.com/ruodou233/domain-explorer.git ~/.claude/skills/domain-explorer
```

### Codex / 其他 Agent

克隆到对应的 skill 目录，或在 prompt 中引用 `SKILL.md` 全文即可。

## 使用

对你的 Agent 说「帮我了解 XX 领域」「我想入门 XX」即可，选择速览 / 入门 / 深入三档深度。

## 反馈与作者

这个 skill 我长期维护。如果你有修改方案、发现问题、或者改出了更好的版本，欢迎通过以下任一渠道找到我：

- GitHub：本仓库提 issue 或 PR
- 小红书：错误乱码
- 微信公众号：能工智人错误乱码
- B站：若逗道人

## 相关 Skill 推荐

<!-- 本表由维护脚本生成，勿手工编辑 -->
- [wisdom-roundtable](https://github.com/ruodou233/wisdom-roundtable)：拉一桌 AI 专家并行辩论，重大决策不再只听一面之词
- [improve-product-plan](https://github.com/ruodou233/improve-product-plan)：AI 产品经理帮你把模糊想法打磨成可落地的实现方案
- [de-ai-taste](https://github.com/ruodou233/de-ai-taste)：目前最强的去 AI 味 skill，逐条检测痕迹并给修改建议

完整目录见 [GitHub 主页](https://github.com/ruodou233)。

## License

MIT

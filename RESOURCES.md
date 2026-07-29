# Mattpocock Skills 学习资源

## Knowledge

这些资源是我们学习的主要来源。所有 skills 都已安装到本地 `~/.agents/skills/` 目录下，每个 skill 的 `SKILL.md` 是权威说明。

### 总览与导航

- [`~/.agents/skills/ask-matt/SKILL.md`](file:///C:/Users/38623/.agents/skills/ask-matt/SKILL.md)
  所有 skills 的“路由器”。当你不知道该用哪个 skill 时，先读它。它把 skills 组织成 main flow（idea → ship）、on-ramps、codebase health、vocabulary layer 和 standalone skills。

- [`~/.agents/skills/setup-matt-pocock-skills/SKILL.md`](file:///C:/Users/38623/.agents/skills/setup-matt-pocock-skills/SKILL.md)
  在真实项目里使用 engineering skills 之前的配置步骤：issue tracker、triage labels、domain docs（CONTEXT.md / ADR）。

### 核心工程工作流

- [`~/.agents/skills/grilling/SKILL.md`](file:///C:/Users/38623/.agents/skills/grilling/SKILL.md) / [`grill-with-docs/SKILL.md`](file:///C:/Users/38623/.agents/skills/grill-with-docs/SKILL.md) / [`grill-me/SKILL.md`](file:///C:/Users/38623/.agents/skills/grill-me/SKILL.md)
   relentless interview（ relentless 提问）的核心技能。`grill-with-docs` 会在提问过程中更新 `CONTEXT.md` 和 ADR；`grill-me` 是无代码库时的纯对话版本。

- [`~/.agents/skills/to-spec/SKILL.md`](file:///C:/Users/38623/.agents/skills/to-spec/SKILL.md)
  把当前对话整理成 PRD/spec，发布到 issue tracker。

- [`~/.agents/skills/to-tickets/SKILL.md`](file:///C:/Users/38623/.agents/skills/to-tickets/SKILL.md)
  把 spec 拆成 tracer-bullet tickets，每个 ticket 声明 blocking edges。

- [`~/.agents/skills/implement/SKILL.md`](file:///C:/Users/38623/.agents/skills/implement/SKILL.md)
  基于 spec/tickets 实现功能，内部驱动 `/tdd`，最后跑 `/code-review`。

- [`~/.agents/skills/tdd/SKILL.md`](file:///C:/Users/38623/.agents/skills/tdd/SKILL.md)
  测试驱动开发的规则： seams、anti-patterns、red-green 循环。

- [`~/.agents/skills/code-review/SKILL.md`](file:///C:/Users/38623/.agents/skills/code-review/SKILL.md)
  双轴代码审查：Standards（是否符合项目规范 + Fowler code smells）和 Spec（是否实现需求）。

### 调试、设计与架构

- [`~/.agents/skills/diagnosing-bugs/SKILL.md`](file:///C:/Users/38623/.agents/skills/diagnosing-bugs/SKILL.md)
  难 bug 的诊断流程：先建 tight feedback loop，再 reproduce、hypothesise、instrument、fix、post-mortem。

- [`~/.agents/skills/codebase-design/SKILL.md`](file:///C:/Users/38623/.agents/skills/codebase-design/SKILL.md)
  共享设计词汇：module、interface、depth、seam、adapter、leverage、locality；如何设计 deep module。

- [`~/.agents/skills/improve-codebase-architecture/SKILL.md`](file:///C:/Users/38623/.agents/skills/improve-codebase-architecture/SKILL.md)
  扫描代码库，找出 deepening opportunities，生成 HTML 报告，然后进入 grilling 循环。

- [`~/.agents/skills/domain-modeling/SKILL.md`](file:///C:/Users/38623/.agents/skills/domain-modeling/SKILL.md)
  主动构建和打磨项目的领域模型：维护 `CONTEXT.md`、写 ADR、challenge 模糊术语。

### 规划、研究与交接

- [`~/.agents/skills/wayfinder/SKILL.md`](file:///C:/Users/38623/.agents/skills/wayfinder/SKILL.md)
  大型/模糊项目的 wayfinding：在 issue tracker 上绘制 shared map，逐个解决决策型 ticket。

- [`~/.agents/skills/triage/SKILL.md`](file:///C:/Users/38623/.agents/skills/triage/SKILL.md)
  对 issue/PR 进行分类、验证、grill，输出 agent-ready brief。

- [`~/.agents/skills/research/SKILL.md`](file:///C:/Users/38623/.agents/skills/research/SKILL.md)
  启动后台 agent 针对 primary sources 做研究，输出带引用的 Markdown。

- [`~/.agents/skills/handoff/SKILL.md`](file:///C:/Users/38623/.agents/skills/handoff/SKILL.md)
  把当前对话压缩成 handoff 文档，供新 session 继续工作。

- [`~/.agents/skills/prototype/SKILL.md`](file:///C:/Users/38623/.agents/skills/prototype/SKILL.md)
  写一次性原型来回答设计问题（状态模型、UI 感觉），得到答案后删除或归档。

- [`~/.agents/skills/teach/SKILL.md`](file:///C:/Users/38623/.agents/skills/teach/SKILL.md)
  在当前目录建立跨 session 的学习工作区（本目录就是它产出的）。

### 写作与通用工具

- [`~/.agents/skills/writing-great-skills/SKILL.md`](file:///C:/Users/38623/.agents/skills/writing-great-skills/SKILL.md)
  如何写好 skill：predictability、context load vs cognitive load、information hierarchy、leading words。

- [`~/.agents/skills/writing-shape/SKILL.md`](file:///C:/Users/38623/.agents/skills/writing-shape/SKILL.md) / [`writing-beats/SKILL.md`](file:///C:/Users/38623/.agents/skills/writing-beats/SKILL.md) / [`writing-fragments/SKILL.md`](file:///C:/Users/38623/.agents/skills/writing-fragments/SKILL.md)
  写作三阶段：fragments（探索）、beats（按节奏组装）、shape（成文）。**注意：这三个在仓库里仍属 in-progress（实验性），行为可能变化。**

> 已废弃（deprecated，勿用于新工作）：`ubiquitous-language`（能力已由 domain-modeling 覆盖）、`design-an-interface`、`qa`、`request-refactor-plan`。

## Wisdom (Communities)

- [Matt Pocock 的 GitHub Skills 仓库](https://github.com/mattpocock/skills)
  skills 的源码和更新来源。如果发现本地 skill 行为与预期不符，先检查仓库是否有新版本或相关 issue。

- [Total TypeScript / ai-hero.dev 社区](https://www.aihero.dev/)
  Matt Pocock 围绕 AI 辅助开发的教学内容发源地，适合理解 skills 背后的设计理念。

> 用户偏好：暂未要求加入社区；后续若改变，记录于此。

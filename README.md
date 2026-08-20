# Wanbinyu

**Language / 语言:** [中文](#中文) | [English](#english)

<p align="center">
  <img src="https://count.getloli.com/get/@Wanbinyu?theme=moebooru" alt="Visitor count" />
</p>

## 中文

我在构建本地优先的 AI 辅助软件开发工具，方向包括多代理编排、Agent Skills、DeepSeek Harness 插件，以及更容易观察和验证的开发者工具。

我关心的不是“看起来很智能”的系统，而是在真实工程压力下仍然可靠的系统：权限边界清晰、工具调用可追踪、完成状态有证据、失败时也能被检查。

### 我在做什么

- 面向编码和软件交付的多代理编排。
- 面向 API、工具、MCP、发布安全的 Agent Skills。
- 本地优先、可观察、可验证的 AI 开发者工具。
- 小而完整的展示型项目，用来表达交互、视觉和想法。

### 从这里开始

#### [MAO - Multi-Agent Orchestrator](https://github.com/Wanbinyu/multi-agent-orchestrator)

一个证据驱动的多模型工程代理，包含明确的权限边界、工具证据、验证关卡、CLI 和 WebUI。

#### [PetDeck / pet-tty](https://github.com/Wanbinyu/pet-tty)

Windows 桌面宠物，用本地 hooks 和本地 HTTP bridge 展示 AI coding agent 正在做什么。

#### [Wanbinyu Harness Toolbox](https://github.com/Wanbinyu/wanbinyu-harness-toolbox)

DeepSeek Harness 的独立第三方插件和工具集合，包含检查、诊断和日常操作辅助能力。

#### [DSH Provider Probe](https://github.com/Wanbinyu/dsh-provider-probe)

用于 DeepSeek Harness 的 provider 连通性和延迟手动检查工具。

#### [Agent Audit Gate](https://github.com/Wanbinyu/agent-audit-gate)

面向 coding agents 的完成状态审计 sidecar，用证据判断任务是 completed 还是 blocked。

#### [Visitor Counter / 访客计数展示](https://count.getloli.com/)

Profile README 中的访客计数展示组件，用来给主页增加一点可见的访问反馈。

### Agent Skills

#### [API Platform Skills](https://github.com/Wanbinyu/api-platform-skills)

面向 API 契约演进的 Agent Skills：breaking changes、compatibility、deprecation、idempotency、webhooks 和 OpenAPI 工作流。

#### [AI Surface Skills](https://github.com/Wanbinyu/ai-surface-skills)

面向工具和 MCP 契约的 Agent Skills：设计、权限、人类确认、breaking-change review 和评估。

#### [Ship Guard Skills](https://github.com/Wanbinyu/ship-guard-skills)

面向 AI 辅助编码之后交付阶段的 Agent Skills：secrets、repros、flaky-test triage、feature flags 和 environment drift。

### 项目地图

- 对外展示：`Wanbinyu`
- 主要工具：`multi-agent-orchestrator`、`pet-tty`、`wanbinyu-harness-toolbox`
- DeepSeek Harness 插件：`dsh-*`
- Skills 集合：`api-platform-skills`、`ai-surface-skills`、`ship-guard-skills`
- 创意实验：`qixi-*`
- 历史镜像：`skill-*`

独立的 `skill-*` 仓库是已归档的历史镜像；新的工作会进入上面的三个 skills 集合。

## English

I build local-first tools for AI-assisted software development, including multi-agent orchestration, Agent Skills, DeepSeek Harness plugins, and developer tools that are easier to observe and verify.

I care less about systems that merely look intelligent and more about systems that remain useful under real engineering pressure: clear permission boundaries, traceable tool use, evidence-backed completion, and inspectable failure modes.

### What I Build

- Multi-agent orchestration for coding and software delivery.
- Agent Skills for API, tool, MCP, and release-safety workflows.
- Local-first AI developer tools that are observable and verifiable.
- Small showcase projects for interaction, visuals, and ideas.

### Start Here

#### [MAO - Multi-Agent Orchestrator](https://github.com/Wanbinyu/multi-agent-orchestrator)

An evidence-driven multi-model engineering agent with explicit permission boundaries, tool evidence, verification gates, CLI, and WebUI.

#### [PetDeck / pet-tty](https://github.com/Wanbinyu/pet-tty)

A Windows desktop pet that shows what an AI coding agent is doing through local hooks and a local HTTP bridge.

#### [Wanbinyu Harness Toolbox](https://github.com/Wanbinyu/wanbinyu-harness-toolbox)

Independent third-party plugins and tools for DeepSeek Harness, including inspection, diagnostics, and operational helpers.

#### [DSH Provider Probe](https://github.com/Wanbinyu/dsh-provider-probe)

Manual provider connectivity and latency checks for DeepSeek Harness.

#### [Agent Audit Gate](https://github.com/Wanbinyu/agent-audit-gate)

A sidecar completion audit for coding agents where evidence decides completed vs blocked.

#### [Visitor Counter](https://count.getloli.com/)

The visitor counter displayed in this profile README, used as a small visible feedback element for the showcase page.

### Agent Skills

#### [API Platform Skills](https://github.com/Wanbinyu/api-platform-skills)

Agent skills for API contract evolution: breaking changes, compatibility, deprecation, idempotency, webhooks, and OpenAPI workflows.

#### [AI Surface Skills](https://github.com/Wanbinyu/ai-surface-skills)

Agent skills for tool and MCP contracts: design, permissions, human approval, breaking-change review, and evaluation.

#### [Ship Guard Skills](https://github.com/Wanbinyu/ship-guard-skills)

Agent skills for shipping after AI-assisted coding: secrets, repros, flaky-test triage, feature flags, and environment drift.

### Repository Map

- Showcase: `Wanbinyu`
- Main tools: `multi-agent-orchestrator`, `pet-tty`, `wanbinyu-harness-toolbox`
- DeepSeek Harness plugins: `dsh-*`
- Skill collections: `api-platform-skills`, `ai-surface-skills`, `ship-guard-skills`
- Creative experiments: `qixi-*`
- Historical mirrors: `skill-*`

Standalone `skill-*` repositories are archived historical mirrors; new work lives in the three skill collections above.

# Wanbinyu

Building local-first tools for AI-assisted software development: multi-agent orchestration, agent skills, and inspectable developer tooling.

I care about AI systems that are useful under real engineering pressure: clear permissions, observable tool use, verification gates, and small interfaces that make agent work easier to understand.

<p align="center">
  <img src="https://count.getloli.com/get/@Wanbinyu?theme=moebooru" alt="Visitor count" />
</p>

## What I Build

- Multi-agent orchestration for coding and software delivery.
- Agent Skills for API, tool, MCP, and release-safety workflows.
- Local-first developer tools that make AI activity inspectable.

## Start Here

### [MAO - Multi-Agent Orchestrator](https://github.com/Wanbinyu/multi-agent-orchestrator)

An evidence-driven multi-model engineering agent with explicit permission boundaries, tool evidence, verification gates, CLI, and WebUI.

### [PetDeck / pet-tty](https://github.com/Wanbinyu/pet-tty)

A Windows desktop pet that shows what an AI coding agent is doing through local hooks and a local HTTP bridge.

### [Wanbinyu Harness Toolbox](https://github.com/Wanbinyu/wanbinyu-harness-toolbox)

Independent third-party plugins and tools for DeepSeek Harness, including inspection and operational helpers.

### [DSH Provider Probe](https://github.com/Wanbinyu/dsh-provider-probe)

Manual provider connectivity and latency checks for DeepSeek Harness.

### [Agent Audit Gate](https://github.com/Wanbinyu/agent-audit-gate)

A sidecar completion audit for coding agents where evidence decides completed vs blocked.

## Agent Skills

### [API Platform Skills](https://github.com/Wanbinyu/api-platform-skills)

Agent skills for API contract evolution: breaking changes, compatibility, deprecation, idempotency, webhooks, and OpenAPI workflows.

### [AI Surface Skills](https://github.com/Wanbinyu/ai-surface-skills)

Agent skills for tool and MCP contracts: design, permissions, human approval, breaking-change review, and evaluation.

### [Ship Guard Skills](https://github.com/Wanbinyu/ship-guard-skills)

Agent skills for shipping after AI-assisted coding: secrets, repros, flaky-test triage, feature flags, and environment drift.

## Repository Map

- Main tools: `multi-agent-orchestrator`, `pet-tty`, `wanbinyu-harness-toolbox`
- DeepSeek Harness plugins: `dsh-*`
- Skill collections: `api-platform-skills`, `ai-surface-skills`, `ship-guard-skills`
- Creative experiments: `qixi-*`

Standalone `skill-*` repositories are archived historical mirrors; new work lives in the three skill collections above.

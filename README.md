# Awesome Multi-Agent Orchestrators with stars

> An awesome-style, selectively curated list of open-source and publicly documented multi-agent orchestrators, coding-agent workspaces, agent runtimes, company operating systems, and adjacent governance layers.

[Website](https://openorchestrators.org/) • [Contributing](./CONTRIBUTING.md)

The public website is [Open Orchestrators](https://openorchestrators.org/). This repo is intentionally narrow: it is not a general AI tools list. Projects belong here when multi-agent coordination, parallel agent execution, agent workflows, or agent-centered operating systems are the product, not a side feature. Governance and enforcement layers are tracked separately when they control agent actions, permissions, approvals, budgets, trust, settlement, or audit trails without acting as the orchestrator itself.

## Latest Additions

* [Hermes Agent](https://hermes-agent.nousresearch.com/) ([GitHub](https://github.com/NousResearch/hermes-agent) ⭐ 251,794 | 🐛 47,735 | 🌐 Python | 📅 2026-10-07, [Nous Research X](https://x.com/NousResearch), [Teknium X](https://x.com/Teknium)) - MIT-licensed autonomous agent from Nous Research with persistent memory, self-created skills, scheduled automations, subagents, sandboxed execution, and messaging gateways.
* [Orca](https://www.onorca.dev/) ([GitHub](https://github.com/stablyai/orca) ⭐ 86,778 | 🐛 8,002 | 🌐 TypeScript | 📅 2026-10-07) - Worktree-based IDE for running Claude Code, Codex, OpenCode, and other coding agents side by side across isolated git branches with review and PR workflow support.
* [Ruflo](https://github.com/ruvnet/ruflo) ⭐ 74,033 | 🐛 1,109 | 🌐 TypeScript | 📅 2026-10-07 ([Swarm plugin docs](https://github.com/ruvnet/ruflo/blob/main/plugins/ruflo-swarm/README.md) ⭐ 74,033 | 🐛 1,109 | 🌐 TypeScript | 📅 2026-10-07) - MIT-licensed coding-agent meta-harness, formerly Claude Flow, for coordinated Claude Code and Codex swarms with team topologies, messaging, and per-agent worktrees. Lite plugins differ from full CLI initialization, which writes configuration/hooks and registers MCP; swarm plugin compatibility and early-access hook requirements apply.
* [LangGraph](https://github.com/langchain-ai/langgraph) ⭐ 42,812 | 🐛 794 | 🌐 Python | 📅 2026-10-07 ([Multi-agent docs](https://docs.langchain.com/oss/python/langchain/multi-agent)) - MIT-licensed low-level orchestration framework for durable, stateful agents and custom multi-agent graph composition. Also supports single-agent workflows; not an out-of-box coding-team runner, and optional LangSmith services are separate from the open-source core.
* [oh-my-codex](https://github.com/Yeachan-Heo/oh-my-codex) ⭐ 33,474 | 🐛 2 | 🌐 TypeScript | 📅 2026-10-06 ([Website](https://yeachan-heo.github.io/oh-my-codex-website/), [npm](https://www.npmjs.com/package/oh-my-codex)) - MIT-licensed workflow layer for OpenAI Codex CLI with stronger default sessions, reusable skills, native hooks, HUD/status surfaces, project guidance, and team-style execution commands.
* [NanoClaw](https://nanoclaw.dev/) ([GitHub](https://github.com/qwibitai/nanoclaw) ⭐ 30,889 | 🐛 1,039 | 🌐 TypeScript | 📅 2026-10-06, [Docs](https://docs.nanoclaw.dev/)) - MIT-licensed personal AI assistant that runs Claude agents in isolated containers, connects to chat channels, keeps memory, schedules work, and uses skills as git branches.
* [Vibe Kanban](https://vibekanban.com/) ([GitHub](https://github.com/BloopAI/vibe-kanban) ⭐ 28,276 | 🐛 544 | 🌐 Rust | 📅 2026-09-19) - Apache-2.0 Kanban workspace for planning, running, reviewing, previewing, and shipping parallel coding-agent work across Claude Code, Codex, Gemini CLI, OpenCode, and related agents.
* [Superset](https://superset.sh/) ([GitHub](https://github.com/superset-sh/superset) ⭐ 14,956 | 🐛 891 | 🌐 TypeScript | 📅 2026-10-07) - Local code editor and control plane for parallel CLI coding agents across isolated git worktrees.
* [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) ⭐ 13,980 | 🐛 766 | 🌐 Python | 📅 2026-10-07 ([Workflow samples](https://github.com/microsoft/agent-framework/blob/main/python/samples/03-workflows/README.md) ⭐ 13,980 | 🐛 766 | 🌐 Python | 📅 2026-10-07) - MIT-licensed Python/.NET developer framework for sequential, concurrent, handoff, and group-collaboration workflows with streaming, checkpoints, and human input. Developers implement and test the application and configure providers; not a ready-made parallel coding-agent workspace.
* [Sandcastle](https://github.com/mattpocock/sandcastle) ⭐ 8,295 | 🐛 170 | 🌐 TypeScript | 📅 2026-10-07 ([npm](https://www.npmjs.com/package/@ai-hero/sandcastle)) - MIT-licensed TypeScript library and CLI for orchestrating AI coding agents in isolated sandboxes with branch strategies, hooks, logs, templates, and merge-back workflows.
* [Microsoft Agent Governance Toolkit](https://github.com/microsoft/agent-governance-toolkit) ⭐ 6,401 | 🐛 77 | 🌐 Python | 📅 2026-10-07 - MIT-licensed runtime governance toolkit for AI agents with deterministic policy enforcement, zero-trust identity, execution sandboxing, SRE controls, and compliance checks.
* [OpenRig](https://github.com/mvschwarz/openrig) ⭐ 5,614 | 🐛 123 | 🌐 TypeScript | 📅 2026-10-07 ([README](https://github.com/mvschwarz/openrig/blob/main/README.md) ⭐ 5,614 | 🐛 123 | 🌐 TypeScript | 📅 2026-10-07) - Apache-2.0 local team coordination through YAML RigSpecs, native coding agents in tmux, messaging, and topology snapshot/restore. Requires Node.js 22 or 24 and tmux on macOS/Linux; setup/startup can write provider hooks and trust settings beyond what dry-run previews.
* [Raven](https://raven.evermind.ai) ([GitHub](https://github.com/EverMind-AI/Raven) ⭐ 5,252 | 🐛 97 | 🌐 Python | 📅 2026-10-07, [Docs](https://evermind-ai.github.io/Raven/)) - Apache-2.0 host agent that plans complex tasks as DAGs and orchestrates built-in research, coding, design, and on-call agents plus 13 third-party agent presets, including Claude Code, Codex, OpenClaw, and Hermes Agent, over ACP, CLI, or OpenAI-compatible APIs.
* [Squad](https://bradygaster.github.io/squad/) ([GitHub](https://github.com/bradygaster/squad) ⭐ 3,256 | 🐛 119 | 🌐 TypeScript | 📅 2026-10-06) - Alpha GitHub Copilot-based agent team system with repo-native specialist agents, persistent memory, coordinator routing, parallel work, and CLI/SDK packages.
* [Scion](https://github.com/GoogleCloudPlatform/scion) ⭐ 1,732 | 🐛 61 | 🌐 Go | 📅 2026-10-07 ([README](https://github.com/GoogleCloudPlatform/scion/blob/main/README.md) ⭐ 1,732 | 🐛 61 | 🌐 Go | 📅 2026-10-07) - Apache-2.0 orchestration for parallel Claude Code, Gemini CLI, Codex, and OpenCode teams with delegation, messaging, and shared workspaces, worktrees, or clones. Pre-1.0; not an officially supported Google product; team behavior depends on supplied instructions.
* [Helmor](https://helmor.ai/) ([GitHub](https://github.com/dohooo/helmor) ⭐ 1,309 | 🐛 44 | 🌐 TypeScript | 📅 2026-08-22, [Releases](https://github.com/dohooo/helmor/releases) ⭐ 1,309 | 🐛 44 | 🌐 TypeScript | 📅 2026-08-22) - Apache-2.0 local-first IDE and workbench for orchestrating Claude Code, Codex, and other coding agents across worktrees through planning, running, review, testing, merge, and shipping loops.
* [Agent Swarm](https://agent-swarm.dev) ([GitHub](https://github.com/desplega-ai/agent-swarm) ⭐ 862 | 🐛 22 | 🌐 TypeScript | 📅 2026-10-07, [Docs](https://docs.agent-swarm.dev), [Dashboard](https://app.agent-swarm.dev)) - MIT-licensed lead/worker orchestration framework where a lead agent receives tasks from Slack, GitHub, GitLab, Linear, Jira, email, WhatsApp, or the API and delegates to worker agents running in isolated Docker environments with persistent vector-searchable memory, persistent SOUL/IDENTITY identity, DAG workflows with HITL gates, scheduled tasks, MCP servers, and harness-agnostic execution across Claude Code, Codex, pi-mono, Devin, Claude Managed Agents, and opencode.
* [Open Swarm](https://openswarm.com/) ([GitHub](https://github.com/openswarm-ai/openswarm) ⭐ 823 | 🐛 0 | 🌐 JavaScript | 📅 2026-10-06, [Docs](https://docs.openswarm.com), [Releases](https://github.com/openswarm-ai/openswarm/releases) ⭐ 823 | 🐛 0 | 🌐 JavaScript | 📅 2026-10-06) - MIT-licensed local mission-control center for launching, monitoring, approving, and coordinating multiple AI agents in parallel.
* [agent-manager](https://agent-manager.dev/) ([GitHub](https://github.com/YoanWai/agent-manager) ⭐ 574 | 🐛 57 | 🌐 Go | 📅 2026-10-06) - Apache-2.0 terminal UI for macOS and Linux (Windows via WSL2) where Claude Code, Codex, OpenCode, Gemini CLI, and other coding-agent CLIs run side by side in persistent tmux sessions, with live status, prompts sent without attaching, optional per-session Git worktrees, and diff review that sends line comments back to the agent.
* [Orbi](https://orbi.build/?ref=dir-openorchestrators) ([GitHub](https://github.com/orbi-build/orbi) ⭐ 195 | 🐛 26 | 🌐 Python | 📅 2026-10-06, [Docs](https://docs.orbi.build/)) - AGPL-3.0 self-hosted issue-to-release runner: label a GitHub Issue ai-ready, an agent implements it in an isolated worktree, a separate review session checks the PR against the Issue's acceptance criteria, and only the reviewed head is merged and tagged.
* [LoopTroop](https://www.looptroop.ovh/) ([GitHub](https://github.com/looptroop-ai/LoopTroop) ⭐ 159 | 🐛 3 | 🌐 TypeScript | 📅 2026-10-07, [Docs](https://www.looptroop.ovh/docs/)) - MIT-licensed local GUI orchestrator for repo-scale coding tickets: multi-model council planning, atomic milestone decomposition, isolated OpenCode worktrees, fresh-context recovery loops, and human approval gates.
* [ccswarm](https://github.com/nwiizo/ccswarm) ⭐ 153 | 🐛 14 | 🌐 Rust | 📅 2026-09-14 ([README](https://github.com/nwiizo/ccswarm/blob/master/README.md) ⭐ 153 | 🐛 14 | 🌐 Rust | 📅 2026-09-14) - MIT-licensed Rust Sangha workflow engine for Claude Code and Codex planning, quorum assessment, parallel implementation, review, and fixes. Approval markers do not prove required checks; Codex readonly review currently uses workspace-write, replay re-executes, and undo only reports commits.
* [Agent Office Suite](https://www.agentofficesuite.com/) ([GitHub](https://github.com/manpoai/AgentOfficeSuite) ⭐ 140 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-03, [Manpo X](https://x.com/manpoai)) - Apache-2.0 self-hosted office suite where agents collaborate with humans on docs, databases, slides, and flowcharts through MCP, contextual comments, version history, and traceable edits.
* [GraphCode](https://graphcode.app/) ([GitHub](https://github.com/scgopi/GraphCode) ⭐ 136 | 🐛 29 | 🌐 Swift | 📅 2026-10-07, [Releases](https://github.com/scgopi/GraphCode/releases) ⭐ 136 | 🐛 29 | 🌐 Swift | 📅 2026-10-07) - FSL-1.1-MIT native macOS workspace that arranges coding-agent sessions into a graph, where every node is a live terminal and hand-off, message, and spawn edges fire unattended when a goal-based loop's shell predicate exits 0.
* [handoff](https://github.com/dazuiba/handoff) ⭐ 91 | 🐛 1 | 🌐 Python | 📅 2026-08-02 ([GitHub](https://github.com/dazuiba/handoff) ⭐ 91 | 🐛 1 | 🌐 Python | 📅 2026-08-02) - MIT cross-agent task dispatcher; delegate work to DeepSeek V4, Codex, or Opus without leaving your Claude Code / Codex session. Runs in background, result returns automatically.
* [Coven](https://opencoven.ai/) ([GitHub](https://github.com/OpenCoven/coven) ⭐ 69 | 🐛 38 | 🌐 Rust | 📅 2026-10-07, [Docs](https://docs.opencoven.ai/)) - MIT-licensed local-first Rust daemon and CLI that runs Codex, Claude Code, and other coding-agent harnesses as PTY sessions inside explicit project-root boundaries, with SQLite-persisted history and a versioned local socket API.
* [AgenticOS](https://github.com/vstorm-co/agenticos) ⭐ 56 | 🐛 108 | 🌐 Python | 📅 2026-10-06 ([Docs](https://vstorm-co.github.io/agenticos/)) - Apache-2.0 self-hosted platform where a company builds, shares and governs its agents in the browser: agents can delegate to other agents, start on schedules or events, answer in web chat, Slack or the API, and each run is checked against budgets and approval rules and kept in an audit log. Built on Pydantic AI; runs with Docker Compose.
* [Agon](https://github.com/AutoResearch-Factory/Agon) ⭐ 54 | 🐛 1 | 🌐 Python | 📅 2026-10-06 ([Paper](https://arxiv.org/abs/2606.24177)) - Autonomous research system that coordinates scientist, coder, and auditor loops from topic to idea, proposal, experiment, and paper.
* [Crewplane](https://github.com/crewplaneai/crewplane) ⭐ 41 | 🐛 1 | 🌐 Python | 📅 2026-10-06 ([GitHub](https://github.com/crewplaneai/crewplane) ⭐ 41 | 🐛 1 | 🌐 Python | 📅 2026-10-06, [Docs](https://github.com/crewplaneai/crewplane/tree/master/docs) ⭐ 41 | 🐛 1 | 🌐 Python | 📅 2026-10-06) - Apache-2.0 orchestrator that turns Claude Code, Codex, Gemini CLI, Copilot CLI, and other command-line agents into structured, repeatable Markdown workflows with resumable execution and inspectable local run records.
* [Veto](https://veto.so/) ([GitHub](https://github.com/PlawIO/veto) ⭐ 14 | 🐛 1 | 🌐 TypeScript | 📅 2026-06-18) - Apache-2.0 AI agent authorization layer that intercepts tool calls before execution, evaluates policy, routes approvals, and records audit evidence. Veto Cloud is commercial.
* [solveathome](https://solveathome.org) ([GitHub](https://github.com/solveathome/platform) ⭐ 5 | 🐛 3 | 🌐 TypeScript | 📅 2026-10-07, [Data dumps](https://solveathome.org/dumps)) - MIT-licensed open platform where people set research directions on open problems, their own AI agents (Claude Code, Codex, or anything that can fetch a URL) do the research on their own machines, other contributors' agents check the results, and trusted human reviewers accept or reject them, one vote per person; every result, review, and transcript is public.
* [Bunkhouse](https://github.com/braedonsaunders/bunkhouse) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-25 - AGPL-3.0 AI employees for main-street business with a company inbox, org chart, and governed procedures.
* [workkit](https://github.com/ITW-Creative-Works/workkit) ⭐ 4 | 🐛 12 | 🌐 JavaScript | 📅 2026-10-06 - Claude Code plugin where a manager agent runs GitHub Issues as the work queue, dispatching scout, worker and verifier subagents per issue and parking results for human QA.
* [Agentastic.dev](https://www.agentastic.dev/) ([Docs](https://www.agentastic.dev/docs)) - Closed-source, free native macOS workspace where Claude Code, Codex, Gemini CLI, and other coding-agent CLIs run in parallel, each task in its own git worktree with a terminal, browser, and diff review, plus optional container, SSH-host, or cloud-sandbox isolation and Manager Agents that start and steer other agents through the dev CLI.
* [Nomad Inno](https://nomadinno.com/) ([X](https://x.com/NomadInnoMT)) - Malta-based AI innovation group helping organizations understand, implement, and scale AI through consulting, custom development, workflow automation, and AI products.
* [Crewlet](https://www.crewlet.io/) ([X](https://x.com/crewlet_)) - Closed autonomous company OS for a self-improving multi-agent growth team with persistent memory, tool access, human review, and auto-run paths.
* [Databricks Unity AI Gateway](https://www.databricks.com/blog/ai-gateway-governance-layer-agentic-ai) - Commercial Databricks platform layer for governing LLM access, MCP servers, APIs, observability, costs, guardrails, fallbacks, and rate limits in agentic AI workflows.
* [Code Atelier Governance SDK](https://www.codeatelier.tech/governance) - Python SDK for pre-execution agent governance gates: scope checks, budgets, approvals, loop detection, halt/presence handling, and tamper-evident Postgres audit trails.
* [Lanes](https://lanes.sh/) - macOS workspace where Claude Code, Codex, Gemini CLI, and other agentic CLIs run parallel sessions with PTYs, boards, worktrees, diffs, and resume.
* [Agentix Labs](https://www.agentixlabs.com/) - Implementation services entry, tracked separately from orchestrators because it helps teams deploy and harden production agent systems.
* [SettleBridge](https://settlebridge.ai/) ([GitHub org](https://github.com/a2a-settlement)) - Trust and policy gateway for agent-to-agent settlement, reputation checks, spending limits, provenance requirements, escrow, dispute resolution, marketplace bounties, and cryptographic audit trails.
* [5dive](https://5dive.ai/?utm_source=github\&utm_medium=referral\&utm_campaign=multiagentorch) - MIT-licensed team of AI agents on a server you own.

## Contents

* [News](#news)
* [Parallel Coding-Agent Runners](#parallel-coding-agent-runners)
* [Multi-Agent Platforms And Builders](#multi-agent-platforms-and-builders)
* [Coordination And Team Systems](#coordination-and-team-systems)
* [Not Open But Important](#not-open-but-important)
* [CLI Agent Session Workspaces](#cli-agent-session-workspaces)
* [Governance And Enforcement](#governance-and-enforcement)
* [Agent-Friendly Tooling](#agent-friendly-tooling)
* [Implementation Services](#implementation-services)
* [Contributing](#contributing)
* [Local Development](#local-development)

## News

Open Orchestrators is also a lightweight news site for meaningful updates from projects already in the directory.

* Add news posts as Markdown files in [`src/content/news`](./src/content/news).
* Set `playerSlug` to the matching entry in [`src/data/orchestrators.ts`](./src/data/orchestrators.ts).
* Include `sourceName` and `sourceUrl` when the post is based on an official announcement, docs page, or repository update.
* The homepage renders the latest story alongside the directory; `/news/` is the full archive.

## Parallel Coding-Agent Runners

Tools for running multiple coding agents simultaneously, usually with git worktree isolation, terminal/session management, review surfaces, or issue-to-agent routing.

* [Orca](https://www.onorca.dev/) ([GitHub](https://github.com/stablyai/orca) ⭐ 86,778 | 🐛 8,002 | 🌐 TypeScript | 📅 2026-10-07) - Desktop environment for running multiple coding agents safely in parallel across worktrees.
* [Multica](https://multica.ai/) ([GitHub](https://github.com/multica-ai/multica) ⭐ 52,082 | 🐛 1,817 | 🌐 Go | 📅 2026-10-07) - Managed agents platform where coding agents act like teammates, take issues, and reuse shared skills.
* [oh-my-codex](https://github.com/Yeachan-Heo/oh-my-codex) ⭐ 33,474 | 🐛 2 | 🌐 TypeScript | 📅 2026-10-06 ([Website](https://yeachan-heo.github.io/oh-my-codex-website/), [npm](https://www.npmjs.com/package/oh-my-codex)) - Workflow layer for OpenAI Codex CLI with reusable skills, native hooks, HUD/status surfaces, project guidance, and `$team`/`$ralph` execution commands.
* [Vibe Kanban](https://vibekanban.com/) ([GitHub](https://github.com/BloopAI/vibe-kanban) ⭐ 28,276 | 🐛 544 | 🌐 Rust | 📅 2026-09-19) - Kanban workspace for planning issues, running coding agents in branches with terminals and dev servers, reviewing diffs, previewing apps, opening pull requests, and merging finished work.
* [Gas Town](https://github.com/gastownhall/gastown) ⭐ 18,291 | 🐛 505 | 🌐 Go | 📅 2026-09-29 ([GitHub](https://github.com/gastownhall/gastown) ⭐ 18,291 | 🐛 505 | 🌐 Go | 📅 2026-09-29) - Multi-agent workspace manager for Claude Code, GitHub Copilot, Codex, Gemini, and other coding agents with persistent work tracking.
* [Superset](https://superset.sh/) ([GitHub](https://github.com/superset-sh/superset) ⭐ 14,956 | 🐛 891 | 🌐 TypeScript | 📅 2026-10-07) - Local code editor and control plane for parallel CLI coding agents across isolated git worktrees.
* [Sandcastle](https://github.com/mattpocock/sandcastle) ⭐ 8,295 | 🐛 170 | 🌐 TypeScript | 📅 2026-10-07 ([npm](https://www.npmjs.com/package/@ai-hero/sandcastle)) - MIT-licensed TypeScript library and CLI for orchestrating AI coding agents in isolated sandboxes with branch strategies, hooks, logs, templates, and merge-back workflows.
* [Scion](https://github.com/GoogleCloudPlatform/scion) ⭐ 1,732 | 🐛 61 | 🌐 Go | 📅 2026-10-07 ([README](https://github.com/GoogleCloudPlatform/scion/blob/main/README.md) ⭐ 1,732 | 🐛 61 | 🌐 Go | 📅 2026-10-07) - Apache-2.0 orchestration for parallel Claude Code, Gemini CLI, Codex, and OpenCode teams with delegation, messaging, and shared workspaces, worktrees, or clones. Pre-1.0; not an officially supported Google product; team behavior depends on supplied instructions.
* [Helmor](https://helmor.ai/) ([GitHub](https://github.com/dohooo/helmor) ⭐ 1,309 | 🐛 44 | 🌐 TypeScript | 📅 2026-08-22) - Apache-2.0 local-first IDE and workbench for orchestrating Claude Code, Codex, and other coding agents across worktrees through planning, running, review, testing, merge, and shipping loops.
* [Open Swarm](https://openswarm.com/) ([GitHub](https://github.com/openswarm-ai/openswarm) ⭐ 823 | 🐛 0 | 🌐 JavaScript | 📅 2026-10-06, [Docs](https://docs.openswarm.com)) - MIT-licensed local mission-control center for launching, monitoring, approving, and coordinating multiple AI agents in parallel.
* [Claudexor](https://claudexor.ai/) ([GitHub](https://github.com/razzant/claudexor) ⭐ 496 | 🐛 72 | 🌐 TypeScript | 📅 2026-10-06) - MIT-licensed local control plane for existing coding agents, with parallel best-of-N candidates, cross-model planning and review, named account profiles, and inspectable run artifacts.
* [Orbi](https://orbi.build/?ref=dir-openorchestrators) ([GitHub](https://github.com/orbi-build/orbi) ⭐ 195 | 🐛 26 | 🌐 Python | 📅 2026-10-06, [Docs](https://docs.orbi.build/)) - Self-hosted runner that takes ai-ready GitHub Issues through implementation, an independent review session against the Issue's acceptance criteria, merge of the reviewed head, and a tagged release.
* [LoopTroop](https://www.looptroop.ovh/) ([GitHub](https://github.com/looptroop-ai/LoopTroop) ⭐ 159 | 🐛 3 | 🌐 TypeScript | 📅 2026-10-07, [Docs](https://www.looptroop.ovh/docs/)) - Local GUI orchestrator for multi-stage coding tickets using LLM-council planning, atomic bead decomposition, isolated OpenCode worktrees, and fresh-context recovery loops.
* [ccswarm](https://github.com/nwiizo/ccswarm) ⭐ 153 | 🐛 14 | 🌐 Rust | 📅 2026-09-14 ([README](https://github.com/nwiizo/ccswarm/blob/master/README.md) ⭐ 153 | 🐛 14 | 🌐 Rust | 📅 2026-09-14) - MIT-licensed Rust Sangha workflow engine for Claude Code and Codex planning, quorum assessment, parallel implementation, review, and fixes. Approval markers do not prove required checks; Codex readonly review currently uses workspace-write, replay re-executes, and undo only reports commits.
* [GraphCode](https://graphcode.app/) ([GitHub](https://github.com/scgopi/GraphCode) ⭐ 136 | 🐛 29 | 🌐 Swift | 📅 2026-10-07, [Releases](https://github.com/scgopi/GraphCode/releases) ⭐ 136 | 🐛 29 | 🌐 Swift | 📅 2026-10-07) - FSL-1.1-MIT native macOS workspace that arranges coding-agent sessions into a graph, where every node is a live terminal and hand-off, message, and spawn edges fire unattended when a goal-based loop's shell predicate exits 0.

## Multi-Agent Platforms And Builders

Frameworks and product surfaces for creating agents, teams, workflows, chatflows, agent apps, or production agent runtimes.

* [OpenClaw](https://openclaw.ai/) ([GitHub](https://github.com/openclaw/openclaw) ⭐ 391,552 | 🐛 9,401 | 🌐 TypeScript | 📅 2026-10-07) - Open-source personal AI assistant software built around chat, persistent context, skills, and execution.
* [Hermes Agent](https://hermes-agent.nousresearch.com/) ([GitHub](https://github.com/NousResearch/hermes-agent) ⭐ 251,794 | 🐛 47,735 | 🌐 Python | 📅 2026-10-07) - MIT-licensed autonomous agent from Nous Research with persistent memory, self-created skills, scheduled automations, subagents, sandboxed execution, and messaging gateways.
* [Dify](https://dify.ai/) ([GitHub](https://github.com/langgenius/dify) ⭐ 157,993 | 🐛 1,066 | 🌐 TypeScript | 📅 2026-10-07) - Agentic workflow builder that combines workflows, chatflows, apps, and knowledge systems.
* [Flowise](https://flowiseai.com/) ([GitHub](https://github.com/FlowiseAI/Flowise) ⚠️ Archived) - Visual builder for AI agents and orchestration flows.
* [LangGraph](https://github.com/langchain-ai/langgraph) ⭐ 42,812 | 🐛 794 | 🌐 Python | 📅 2026-10-07 ([Multi-agent docs](https://docs.langchain.com/oss/python/langchain/multi-agent)) - MIT-licensed low-level orchestration framework for durable, stateful agents and custom multi-agent graph composition. Also supports single-agent workflows; not an out-of-box coding-team runner, and optional LangSmith services are separate from the open-source core.
* [Agno](https://agno.com/) ([GitHub](https://github.com/agno-agi/agno) ⭐ 42,592 | 🐛 1,839 | 🌐 Python | 📅 2026-10-07) - Production runtime for agentic software with agents, teams, workflows, and AgentOS services.
* [NanoClaw](https://nanoclaw.dev/) ([GitHub](https://github.com/qwibitai/nanoclaw) ⭐ 30,889 | 🐛 1,039 | 🌐 TypeScript | 📅 2026-10-06, [Docs](https://docs.nanoclaw.dev/)) - MIT-licensed personal AI assistant that runs Claude agents in isolated containers, connects to chat channels, keeps memory, schedules work, and uses skills as git branches.
* [Sim](https://www.sim.ai/) ([GitHub](https://github.com/simstudioai/sim) ⭐ 29,784 | 🐛 397 | 🌐 TypeScript | 📅 2026-10-07) - Open-source AI agent platform for building agents with integrations, workflows, knowledge bases, and docs.
* [Mastra](https://mastra.ai/) ([GitHub](https://github.com/mastra-ai/mastra) ⭐ 28,611 | 🐛 566 | 🌐 TypeScript | 📅 2026-10-07) - TypeScript framework for agents, graph-based workflows, MCP servers, evals, observability, and production AI applications.
* [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) ⭐ 13,980 | 🐛 766 | 🌐 Python | 📅 2026-10-07 ([Workflow samples](https://github.com/microsoft/agent-framework/blob/main/python/samples/03-workflows/README.md) ⭐ 13,980 | 🐛 766 | 🌐 Python | 📅 2026-10-07) - MIT-licensed Python/.NET developer framework for sequential, concurrent, handoff, and group-collaboration workflows with streaming, checkpoints, and human input. Developers implement and test the application and configure providers; not a ready-made parallel coding-agent workspace.
* [Raven](https://raven.evermind.ai) ([GitHub](https://github.com/EverMind-AI/Raven) ⭐ 5,252 | 🐛 97 | 🌐 Python | 📅 2026-10-07, [Docs](https://evermind-ai.github.io/Raven/)) - Apache-2.0 host agent that plans complex tasks as DAGs and orchestrates built-in research, coding, design, and on-call agents plus 13 third-party agent presets, including Claude Code, Codex, OpenClaw, and Hermes Agent, over ACP, CLI, or OpenAI-compatible APIs.
* [Cabinet](https://runcabinet.com/) ([GitHub](https://github.com/hilash/cabinet) ⭐ 2,879 | 🐛 82 | 🌐 TypeScript | 📅 2026-08-25) - AI-first knowledge base where files live on disk and agents help with execution.
* [Agent Swarm](https://agent-swarm.dev) ([GitHub](https://github.com/desplega-ai/agent-swarm) ⭐ 862 | 🐛 22 | 🌐 TypeScript | 📅 2026-10-07, [Docs](https://docs.agent-swarm.dev)) - MIT-licensed lead/worker orchestration framework where a lead agent receives tasks from Slack, GitHub, GitLab, Linear, Jira, email, WhatsApp, or the API and delegates to worker agents running in isolated Docker environments with persistent vector-searchable memory, DAG workflows with HITL gates, scheduled tasks, MCP servers, and harness-agnostic execution across Claude Code, Codex, pi-mono, Devin, Claude Managed Agents, and opencode.
* [SwarmClaw](https://www.swarmclaw.ai/) ([GitHub](https://github.com/swarmclawai/swarmclaw) ⭐ 687 | 🐛 19 | 🌐 TypeScript | 📅 2026-06-30) - Self-hosted AI agent runtime for autonomous agents, delegated work, schedules, provider management, and chat-platform connectors.
* [Agent Office Suite](https://www.agentofficesuite.com/) ([GitHub](https://github.com/manpoai/AgentOfficeSuite) ⭐ 140 | 🐛 0 | 🌐 TypeScript | 📅 2026-06-03, [Manpo X](https://x.com/manpoai)) - Self-hosted office suite where agents collaborate with humans on docs, databases, slides, and flowcharts through MCP, contextual comments, version history, and traceable edits.
* [NarraNexus](https://github.com/NetMindAI-Open/NarraNexus) ⭐ 88 | 🐛 51 | 🌐 Python | 📅 2026-10-05 - Open-source AI agent team workspace by NetMind.AI whose agents remember, collaborate, and use tools from day one.
* [AgenticOS](https://github.com/vstorm-co/agenticos) ⭐ 56 | 🐛 108 | 🌐 Python | 📅 2026-10-06 ([Docs](https://vstorm-co.github.io/agenticos/)) - Apache-2.0 self-hosted platform where a company builds, shares and governs its agents in the browser: agents can delegate to other agents, start on schedules or events, answer in web chat, Slack or the API, and each run is checked against budgets and approval rules and kept in an audit log. Built on Pydantic AI; runs with Docker Compose.
* [Agon](https://github.com/AutoResearch-Factory/Agon) ⭐ 54 | 🐛 1 | 🌐 Python | 📅 2026-10-06 ([Paper](https://arxiv.org/abs/2606.24177)) - Autonomous research system that coordinates scientist, coder, and auditor loops from topic to idea, proposal, experiment, and paper.
* [Crewplane](https://github.com/crewplaneai/crewplane) ⭐ 41 | 🐛 1 | 🌐 Python | 📅 2026-10-06 ([GitHub](https://github.com/crewplaneai/crewplane) ⭐ 41 | 🐛 1 | 🌐 Python | 📅 2026-10-06, [Docs](https://github.com/crewplaneai/crewplane/tree/master/docs) ⭐ 41 | 🐛 1 | 🌐 Python | 📅 2026-10-06) - Apache-2.0 orchestrator that turns Claude Code, Codex, Gemini CLI, Copilot CLI, and other command-line agents into structured, repeatable Markdown workflows with resumable execution and inspectable local run records.

## Coordination And Team Systems

Systems where the central object is the team, company, room, protocol, role, goal, job, or handoff layer between agents.

* [Paperclip](https://paperclip.ing/) ([GitHub](https://github.com/paperclipai/paperclip) ⭐ 98,234 | 🐛 6,206 | 🌐 TypeScript | 📅 2026-10-07) - Open-source orchestration for zero-human companies, centered on AI employees, goals, and jobs.
* [Ruflo](https://github.com/ruvnet/ruflo) ⭐ 74,033 | 🐛 1,109 | 🌐 TypeScript | 📅 2026-10-07 ([Swarm plugin docs](https://github.com/ruvnet/ruflo/blob/main/plugins/ruflo-swarm/README.md) ⭐ 74,033 | 🐛 1,109 | 🌐 TypeScript | 📅 2026-10-07) - MIT-licensed coding-agent meta-harness, formerly Claude Flow, for coordinated Claude Code and Codex swarms with team topologies, messaging, and per-agent worktrees. Lite plugins differ from full CLI initialization, which writes configuration/hooks and registers MCP; swarm plugin compatibility and early-access hook requirements apply.
* [CrewAI](https://www.crewai.com/) ([GitHub](https://github.com/crewAIInc/crewAI) ⭐ 59,415 | 🐛 570 | 🌐 Python | 📅 2026-10-07) - Multi-agent system organized around specialized crews, roles, and delegation.
* [OpenRig](https://github.com/mvschwarz/openrig) ⭐ 5,614 | 🐛 123 | 🌐 TypeScript | 📅 2026-10-07 ([README](https://github.com/mvschwarz/openrig/blob/main/README.md) ⭐ 5,614 | 🐛 123 | 🌐 TypeScript | 📅 2026-10-07) - Apache-2.0 local team coordination through YAML RigSpecs, native coding agents in tmux, messaging, and topology snapshot/restore. Requires Node.js 22 or 24 and tmux on macOS/Linux; setup/startup can write provider hooks and trust settings beyond what dry-run previews.
* [Squad](https://bradygaster.github.io/squad/) ([GitHub](https://github.com/bradygaster/squad) ⭐ 3,256 | 🐛 119 | 🌐 TypeScript | 📅 2026-10-06) - Alpha GitHub Copilot-based system where specialist agents live in the repo, keep memory, share decisions, route work through a coordinator, and run in parallel.
* [Culture](https://culture.dev/) ([GitHub](https://github.com/agentculture/culture) ⭐ 113 | 🐛 37 | 🌐 Python | 📅 2026-08-23) - Coordination-oriented system with rooms, protocol docs, agent lifecycle patterns, and multiple clients.
* [Okto Nexus](https://oktolabs.ai/platform/nexus/) ([GitHub](https://github.com/OktoLabsAI/okto-nexus) ⭐ 68 | 🐛 7 | 🌐 Python | 📅 2026-10-07) - Elastic-2.0 local-first MCP coordination hub where agents get durable identities, messaging, single-winner handoff claims, and human-in-the-loop approval on risky actions.
* [Bunkhouse](https://github.com/braedonsaunders/bunkhouse) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-25 - AGPL-3.0 AI employees for main-street business with a company inbox, org chart, and governed procedures.
* [solveathome](https://solveathome.org) ([GitHub](https://github.com/solveathome/platform) ⭐ 5 | 🐛 3 | 🌐 TypeScript | 📅 2026-10-07, [Data dumps](https://solveathome.org/dumps)) - MIT-licensed open platform where people set research directions on open problems, their own AI agents (Claude Code, Codex, or anything that can fetch a URL) do the research on their own machines, other contributors' agents check the results, and trusted human reviewers accept or reject them, one vote per person; every result, review, and transcript is public.
* [workkit](https://github.com/ITW-Creative-Works/workkit) ⭐ 4 | 🐛 12 | 🌐 JavaScript | 📅 2026-10-06 - Claude Code plugin where a manager agent runs GitHub Issues as the work queue, dispatching scout, worker and verifier subagents per issue and parking results for human QA.
* [The Rusty Claw](https://therustyclaw.com) ([GitHub](https://github.com/wassname/therustyclaw)) - Public coordination relay for agents on Nostr. Signed messages, no accounts, proof-of-work against spam, full-text search, writable with a plain GET (request-bin style), durable public archive. Made by wassname (AI alignment researcher).
* [Artifact Council](https://artifactcouncil.com/) ([Agent docs](https://artifactcouncil.com/skill.md), [Relay](https://artifactcouncil.com/operator-guide-mainnet.md)) - Councils of agents that govern shared text artifacts: members propose edits and admissions and vote against a roster frozen when the proposal is made, and a Solana mainnet program (upgrade authority revoked) enforces the result. Agents join over plain HTTP with their own Ed25519 key or a gateway-hosted identity; the relay is MIT-licensed.
* [5dive](https://5dive.ai/?utm_source=github\&utm_medium=referral\&utm_campaign=multiagentorch) - MIT-licensed team of AI agents on a server you own.

## Not Open But Important

Closed products that are not part of the open directory, but matter to the community because they influence how builders think about multi-agent orchestration.

* [AgentGrid](https://agentgrid.sh/) ([Orchestration docs](https://agentgrid.sh/docs/guides/orchestrating-agents)) - Commercial desktop workspace for visible master/worker delegation across Claude Code, Codex, and other coding harnesses, with persistent sessions, terminals, browsers, and notes.
* [Crewlet](https://www.crewlet.io/) ([X](https://x.com/crewlet_)) - Not open-source; included because it frames a self-improving multi-agent company OS for growth, engineering, support, and data operations across existing tools.
* [Augment Code Intent](https://www.augmentcode.com/product/intent) - Not open-source; included because Intent puts coordinated agents, isolated workspaces, and living specs in one developer workspace.

## CLI Agent Session Workspaces

Tools that manage parallel CLI-agent sessions, terminals, issue boards, worktrees, diffs, and local review loops. These are useful for agentic coding work, but they are tracked separately from orchestrator/player entries when they do not manage agent teams or runtime behavior directly.

* [agent-manager](https://agent-manager.dev/) ([GitHub](https://github.com/YoanWai/agent-manager) ⭐ 574 | 🐛 57 | 🌐 Go | 📅 2026-10-06) - Apache-2.0 terminal UI for macOS and Linux (Windows via WSL2) where Claude Code, Codex, OpenCode, Gemini CLI, and other coding-agent CLIs run side by side in persistent tmux sessions, with live status, prompts sent without attaching, optional per-session Git worktrees, and diff review that sends line comments back to the agent.
* [Coven](https://opencoven.ai/) ([GitHub](https://github.com/OpenCoven/coven) ⭐ 69 | 🐛 38 | 🌐 Rust | 📅 2026-10-07, [Docs](https://docs.opencoven.ai/)) - MIT-licensed local-first Rust daemon and CLI that runs Codex, Claude Code, and other coding-agent harnesses as PTY sessions inside explicit project-root boundaries, with SQLite-persisted history and a versioned local socket API.
* [Lanes](https://lanes.sh/) - macOS workspace where Claude Code, Codex, Gemini CLI, and other agentic CLIs run as parallel real-PTY sessions with boards, auto-created git worktrees, session resume, diffs, and file editing.
* [Agentastic.dev](https://www.agentastic.dev/) ([Docs](https://www.agentastic.dev/docs)) - Closed-source, free native macOS workspace where Claude Code, Codex, Gemini CLI, and other coding-agent CLIs run in parallel, each task in its own git worktree with a terminal, browser, and diff review, plus optional container, SSH-host, or cloud-sandbox isolation and Manager Agents that start and steer other agents through the dev CLI.

## Governance And Enforcement

Policy, permission, approval, budget, trust, reputation, settlement, and audit layers that sit between agent intent and execution. These are not orchestrators themselves; they govern actions routed through an orchestrator, framework, coding agent, MCP server, marketplace, exchange, or application runtime.

### Open and open-core governance tools

* [Microsoft Agent Governance Toolkit](https://github.com/microsoft/agent-governance-toolkit) ⭐ 6,401 | 🐛 77 | 🌐 Python | 📅 2026-10-07 - MIT-licensed runtime governance toolkit for AI agents with deterministic policy enforcement, zero-trust identity, execution sandboxing, SRE controls, and compliance checks.
* [Okto Pulse](https://oktolabs.ai/platform/pulse/) ([GitHub](https://github.com/OktoLabsAI/okto-pulse) ⭐ 110 | 🐛 8 | 🌐 Python | 📅 2026-10-07) - Elastic-2.0 local-first SDLC workbench with 17 enforced governance gates for AI coding agents, including independent validation, blocking evidence requirements, and spec-coverage checks before work reaches done.
* [Veto](https://veto.so/) ([GitHub](https://github.com/PlawIO/veto) ⭐ 14 | 🐛 1 | 🌐 TypeScript | 📅 2026-06-18) - Apache-2.0 authorization layer for AI agent tool calls, with TypeScript and Python SDKs, YAML policies, approval routing, and audit logs. Veto Cloud is commercial.
* [Code Atelier Governance SDK](https://www.codeatelier.tech/governance) - Python SDK for pre-execution governance gates around AI agents, backed by Postgres.
* [SettleBridge](https://settlebridge.ai/) ([GitHub org](https://github.com/a2a-settlement)) - Trust and policy gateway for agent-to-agent settlement, including reputation thresholds, spending limits, provenance requirements, escrow, dispute resolution, marketplace bounties, and cryptographic audit trails. The related A2A Settlement repo is MIT-licensed; SettleBridge's public license metadata is not fully consistent yet.

### Commercial and platform governance layers

* [Databricks Unity AI Gateway](https://www.databricks.com/blog/ai-gateway-governance-layer-agentic-ai) - Commercial Databricks platform layer for governing LLM access, MCP servers, APIs, observability, costs, guardrails, fallbacks, and rate limits in agentic AI workflows.

## Agent-Friendly Tooling

Tools that are not orchestrators themselves, but make multi-agent systems easier to operate, measure, observe, or reuse.

* [OrcaReplay](https://github.com/Continuum-AI-Corp/OrcaReplay) ⭐ 281 | 🐛 1 | 🌐 TypeScript | 📅 2026-10-01 - Records a coding-agent run beneath the harness and replays it offline from the recorded bytes, or re-runs it from a chosen step on a different model.
* [agenttrace](https://github.com/luoyuctl/agenttrace) ⭐ 140 | 🐛 5 | 🌐 Rust | 📅 2026-10-06 - Local TUI observability for AI coding-agent sessions, tokens, cost, tool failures, latency, anomalies, diffs, and CI evidence.
* [Orchestrator](https://zachealy1.github.io/orchestrator/) ([GitHub](https://github.com/zachealy1/orchestrator) ⭐ 12 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-07) - MIT-licensed macOS workspace connecting Codex execution with Kanban tasks, subagent inspection, repository browsing, and local code review; public beta for macOS 15+ using the user's own supported Codex account.
* [Agent Analytics](https://agentanalytics.sh/) - Web analytics for builders that Claude Code, Codex, Cursor, OpenClaw, Paperclip, and similar AI agents can use.
* [ClawTrace](https://www.clawtrace.ai/?ref=producthunt) - Observability for OpenClaw agents that shows what failed, where spend leaked, and how to improve runs.
* [Companies.sh](https://companies.sh/) - Reusable companies for AI agents: pre-built organizations that can be installed with a single command.

## Implementation Services

Services companies and consultants that publish practical material on deploying, hardening, and operating multi-agent systems. These are not orchestrator/player entries.

* [Nomad Inno](https://nomadinno.com/) ([X](https://x.com/NomadInnoMT)) - Malta-based AI innovation group helping organizations understand, implement, and scale AI through consulting, custom development, workflow automation, and AI products.
* [Agentix Labs](https://www.agentixlabs.com/) - Implementation services and practical writing for teams moving AI agents from pilots into production operations. Public contact details list United States and Canadian offices in New York and Montreal; no explicit worldwide coverage claim is made.

## Contributing

Before submitting a pull request, please star this repository.

Pull requests are welcome if the project clearly fits the directory scope.

* Add or update entries in [`src/data/orchestrators.ts`](./src/data/orchestrators.ts).
* Prefer official website, docs, and GitHub links.
* Keep summaries factual, concise, and based on public sources.
* For governance and enforcement entries, state whether the source is open source, open-core, commercial, or a platform feature.
* If you add a project, include the source you used to verify it.

See [`CONTRIBUTING.md`](./CONTRIBUTING.md) for the full review criteria.

## Local Development

This repo contains the Awesome Multi-Agent Orchestrators list and a small Astro site for [`openorchestrators.org`](https://openorchestrators.org/).

```bash
cd open-orchestrators.org
npm install
npm run dev
```

Most editorial updates should happen in [`src/data/orchestrators.ts`](./src/data/orchestrators.ts), which is the source of truth for directory entries, rank order, notes, tags, and links.

News updates should happen in [`src/content/news`](./src/content/news). Directory entries and news posts are intentionally separate: directory metadata describes the player; news Markdown describes a dated update about that player.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-07._

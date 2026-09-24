<p align="center">
  <img src="assets/agent-garden-banner.png" width="100%" alt="A friendly robot tending a glowing garden of connected ideas under a starry sky">
</p>

<p align="center">
  <a href="https://x.com/Av1dlive"><img src="https://avatars.githubusercontent.com/u/52658655?v=4" width="112" height="112" alt="Avidlive logo"></a>
</p>

<h1 align="center">Avidlive</h1>

<p align="center"><strong>Growing a garden of tools for agents with very short memories. 🌱🤖</strong></p>

<p align="center">
  Local-first software · Agent infrastructure · Creative tools · Hardware
</p>

<p align="center">
  <a href="https://x.com/Av1dlive"><img src="https://img.shields.io/badge/Follow-%40Av1dlive-111111?style=flat-square&logo=x&logoColor=white" alt="Follow @Av1dlive on X"></a>
  <a href="https://github.com/codejunkie99?tab=repositories"><img src="https://img.shields.io/badge/Explore-my_projects-6E75BF?style=flat-square&logo=github&logoColor=white" alt="Explore my GitHub projects"></a>
</p>

---

I’m **Avidlive**, building practical tools around a recurring problem: useful agent work should survive the next session, the next model, and the next tool.

My projects cover shared memory, coding-agent workspaces, model routing, verified execution loops, image workflows, and hardware development. I share builds, experiments, and guides on **[X · @Av1dlive](https://x.com/Av1dlive)**.

## Start here

| Project | What you can do with it |
| --- | --- |
| **[Agentic Stack](https://github.com/codejunkie99/agentic-stack)** | Carry one `.agent/` memory-and-skills layer across coding tools. Run bounded work loops, inspect activity, and keep reusable lessons. |
| **[Agentic Stack Desktop](https://github.com/codejunkie99/agentic-stack-desktop)** | Search conversations across Claude Code, Codex, OpenCode, and Cursor; explore a local knowledge graph; work with custom agents, tasks, and terminals in a native macOS app. |
| **[Brain](https://github.com/codejunkie99/brain)** | Give agents shared, Git-backed memory through a CLI, terminal dashboard, and MCP server. Search notes and sync when you choose. |
| **[Continual Memory Policy Model](https://github.com/codejunkie99/continual-memory-policy-model)** | Explore how an agent chooses what to remember: six memory operations, delayed outcome feedback, a read-only Memory Center, and evaluated adapter training with human promotion. **Experimental research.** |
| **[Image Loop](https://github.com/codejunkie99/image-loop)** + **[Image Reconstruction](https://github.com/codejunkie99/image-reconstruction)** | Break references into named parts, preserve chosen details, compile prompts, review edits, and repair failed requirements. Includes visual maps, reusable JSON, and worked examples. |
| **[Agent Harness](https://github.com/codejunkie99/agent-harness)** | Give a coding agent a repeatable spec → plan → implement → verify → release workflow for SaaS, CLI, MCP, and mobile work. |
| **[GateFlow](https://github.com/codejunkie99/Gateflow-Plugin)** | Work on SystemVerilog, Verilog, and VHDL with agent-assisted design, linting, testbenches, simulation, formal checks, and FPGA tooling. |
| **[ztk](https://github.com/codejunkie99/ztk)** | Reduce the command-output noise entering an agent’s context, integrate with supported agent hooks, and inspect savings locally. |
| **[Meridian OS](https://github.com/codejunkie99/meridian-company-os)** | Explore a company console for goals, tasks, agents, budgets, approvals, and activity. Includes a simulation mode and optional runtime connections. |

## More to explore

- **Memory and knowledge:** [ContextHub](https://github.com/codejunkie99/contexthub), [Familiar Second Brain](https://github.com/codejunkie99/familiar-second-brain), [Design Brain](https://github.com/codejunkie99/design-brain), and [Graph Engineering](https://github.com/codejunkie99/graph-engineering).
- **Model routing and execution:** [SageRoute](https://github.com/codejunkie99/sageroute), [Quota Flow](https://github.com/codejunkie99/quota-flow), [Fable Orchestrator](https://github.com/codejunkie99/fable-orchestrator), and [Scoped Agent Loop](https://github.com/codejunkie99/scoped-agent-loop).
- **Writing and creative work:** [X Article Skills](https://github.com/codejunkie99/x-article-skills), [Prompt Skills](https://github.com/codejunkie99/prompt-skills), and [RosterRoom](https://github.com/codejunkie99/rosterroom).
- **Everyday tools:** [LocalFlow](https://github.com/codejunkie99/LocalFlow) for on-device dictation, [Cove](https://github.com/codejunkie99/cove) for a local productivity workspace, and [spotify-kitty](https://github.com/codejunkie99/spotify-kitty) for music in the terminal.

## How I like to build

**Keep context portable. Make decisions inspectable. Verify the result.**

That means local data where practical, reusable files and open interfaces, bounded execution, and human control over consequential actions. Some repositories are working tools; others are prototypes or research experiments. Each project’s README explains its setup, evidence, and limits.

<details>
<summary><strong>Browse the full public project directory</strong></summary>


### Memory and context

- **[agentic-stack](https://github.com/codejunkie99/agentic-stack)** — Portable memory, skills, protocols, and bounded loops across coding-agent tools.
- **[agentic-stack-desktop](https://github.com/codejunkie99/agentic-stack-desktop)** — Native macOS workspace with shared conversation search, a knowledge graph, custom agents, and terminals.
- **[brain](https://github.com/codejunkie99/brain)** — Git-backed agent memory with a CLI, terminal dashboard, MCP server, and explicit sync.
- **[continual-memory-policy-model](https://github.com/codejunkie99/continual-memory-policy-model)** — Experimental memory policies with delayed feedback, a local Memory Center, and gated adapter training.
- **[contexthub](https://github.com/codejunkie99/contexthub)** — Local MCP context layer with connectors, line-level retrieval, and scope filtering.
- **[familiar-second-brain](https://github.com/codejunkie99/familiar-second-brain)** — Markdown-vault memory, Kimi session capture, daily briefs, and MCP access.
- **[design-brain](https://github.com/codejunkie99/design-brain)** — Capture design tokens and patterns from websites and screenshots; search, compare, and export them.

### Agent runtimes, routing, and loops

- **[agent-harness](https://github.com/codejunkie99/agent-harness)** — File-based workflows for taking SaaS, CLI, MCP, and mobile projects from specification to verification.
- **[agentic-harness](https://github.com/codejunkie99/agentic-harness)** — Rust-native agent runtime, SDK, and CLI.
- **[autoharness](https://github.com/codejunkie99/autoharness)** — Local macOS control center for direct tasks, bounded loops, swarms, and task graphs.
- **[sageroute](https://github.com/codejunkie99/sageroute)** — OpenAI-compatible model routing that escalates based on agent execution evidence.
- **[quota-flow](https://github.com/codejunkie99/quota-flow)** — Codex orchestration skill with implementation, focused review, and verified repair loops.
- **[fable-orchestrator](https://github.com/codejunkie99/fable-orchestrator)** — Fable-led orchestration with focused implementation workers.
- **[codex-self-improving-loop](https://github.com/codejunkie99/codex-self-improving-loop)** — Task execution, grading, and prompt revision in a repeatable Codex loop.
- **[scoped-agent-loop](https://github.com/codejunkie99/scoped-agent-loop)** — Two-agent planner/executor loop with explicit policy and execution receipts.
- **[claude-model-switch](https://github.com/codejunkie99/claude-model-switch)** — Provider switching, custom API keys, and multi-model tmux orchestration for Claude Code.
- **[dsh-rs](https://github.com/codejunkie99/dsh-rs)** — Rust/GPUI desktop harness project.
- **[ztk](https://github.com/codejunkie99/ztk)** — Compact command output before it enters an agent’s context; inspect compression statistics.
- **[tokensavings-pro](https://github.com/codejunkie99/tokensavings-pro)** — Reusable dual-model workflow with compact implementation and reasoning packets.

### Creative tools and reusable skills

- **[image-loop](https://github.com/codejunkie99/image-loop)** — Reference-driven image creation and editing with visual maps, review, and bounded repairs.
- **[image-reconstruction](https://github.com/codejunkie99/image-reconstruction)** — Map a reference into named parts, reusable JSON, and reconstruction or edit prompts.
- **[x-article-skills](https://github.com/codejunkie99/x-article-skills)** — Skills for researching, writing, and packaging articles on X.
- **[prompt-skills](https://github.com/codejunkie99/prompt-skills)** — Reusable prompt templates for writing, analysis, technical work, and productivity.
- **[prompting-skill](https://github.com/codejunkie99/prompting-skill)** — Portable workflow for designing and improving LLM prompts.
- **[avids-essential-skills](https://github.com/codejunkie99/avids-essential-skills)** — A collection of practical Claude Code skills.
- **[rosterroom](https://github.com/codejunkie99/rosterroom)** — Ready-to-use team rosters for Grok Bot.
- **[ste100-loop](https://github.com/codejunkie99/ste100-loop)** — Draft, grade, and revise technical writing with a clarity-focused review loop.

### Company systems and research

- **[meridian-company-os](https://github.com/codejunkie99/meridian-company-os)** — Company console with goals, tasks, agents, budgets, approvals, and a built-in simulation.
- **[company-foundry](https://github.com/codejunkie99/company-foundry)** — Company-harness methods, agent presets, and operating artifacts.
- **[agentic-os](https://github.com/codejunkie99/agentic-os)** — Engineering-activity knowledge graph and execution-drift detection MVP.
- **[business-workflow-autopilot](https://github.com/codejunkie99/business-workflow-autopilot)** — Agent skill for turning business operations into structured workflows.
- **[graph-engineering](https://github.com/codejunkie99/graph-engineering)** — Knowledge-graph pipelines, task-graph patterns, teaching mode, and reusable workflows.
- **[agent-roadmap-2026](https://github.com/codejunkie99/agent-roadmap-2026)** — A staged learning roadmap for AI agent engineering, grounded in primary sources.
- **[larp-bench](https://github.com/codejunkie99/larp-bench)** — Research benchmark exploring models that invent personal experiences.
- **[murmur](https://github.com/codejunkie99/murmur)** — Multi-agent social-media simulation engine.
- **[voice-agent-builder](https://github.com/codejunkie99/voice-agent-builder)** — Builder’s guide and executable skill for voice-agent development.

### Hardware and everyday tools

- **[Gateflow-Plugin](https://github.com/codejunkie99/Gateflow-Plugin)** — Claude Code hardware-development plugin with HDL design, simulation, formal verification, and FPGA workflows.
- **[gateflow-cli](https://github.com/codejunkie99/gateflow-cli)** — AI-assisted SystemVerilog development environment.
- **[LocalFlow](https://github.com/codejunkie99/LocalFlow)** — On-device dictation for Apple silicon Macs.
- **[cove](https://github.com/codejunkie99/cove)** — Local browser workspace for tasks, notes, pages, habits, and journaling.
- **[spotify-kitty](https://github.com/codejunkie99/spotify-kitty)** — Spotify terminal client with inline album art, search, playlists, and playback controls.
- **[homebrew-tap](https://github.com/codejunkie99/homebrew-tap)** — Homebrew distribution for my tools.
- **[homebrew-ztk](https://github.com/codejunkie99/homebrew-ztk)** — Homebrew tap for ztk.
- **[homebrew-contexthub](https://github.com/codejunkie99/homebrew-contexthub)** — Homebrew tap for ContextHub.

</details>

<details>
<summary><strong>Public forks and upstream projects</strong></summary>

These are forks of other projects. Original authorship and licenses belong to their respective upstream projects.

- [agent-skills](https://github.com/codejunkie99/agent-skills)
- [CloakBrowser](https://github.com/codejunkie99/CloakBrowser)
- [codex-router](https://github.com/codejunkie99/codex-router)
- [finding-unknowns-skills](https://github.com/codejunkie99/finding-unknowns-skills)
- [hyperclaw-avid](https://github.com/codejunkie99/hyperclaw-avid)
- [lunel](https://github.com/codejunkie99/lunel)
- [omi](https://github.com/codejunkie99/omi)
- [pi-mono](https://github.com/codejunkie99/pi-mono)
- [sqlcx](https://github.com/codejunkie99/sqlcx)
- [x-algorithm](https://github.com/codejunkie99/x-algorithm)

</details>

---

**Follow the builds:** [X / @Av1dlive](https://x.com/Av1dlive) · [All repositories](https://github.com/codejunkie99?tab=repositories)

Found a bug or have an idea? Open an issue in the relevant project.

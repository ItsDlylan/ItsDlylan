# Hey, I'm Dylan 👋
**AI-Augmented Full-Stack Engineer**

---

## 👨‍💻 About Me
I build production software with AI coding agents. Not prompting for snippets — I'm talking full applications architected, built, and shipped using Claude Code as a daily driver.

I've gone from leading engineering teams and shipping Laravel/React/Node apps to fundamentally rethinking how software gets built. Every project below was developed with AI augmentation, and each one pushed my workflow further — faster iteration, higher quality, less busywork.

My stack shifts based on the problem: Rust + TypeScript for performance-critical tools, Laravel + Inertia for rapid full-stack apps, Swift for native macOS. The constant is using AI to move faster without cutting corners.

---

## 🚀 AI-Augmented Projects

These are all built with [Claude Code](https://docs.anthropic.com/en/docs/claude-code) — each one leveled up my workflow.

### [AgentCanvas](https://github.com/ItsDlylan/AgentCanvas) — Infinite Canvas for AI Agent Orchestration
`Electron` `React` `React Flow` `xterm.js` `TypeScript`
A spatial desktop workspace for working with AI coding agents. Spawn terminal, browser, note, PDF, and task tiles on a single infinite, zoomable canvas — then let agents orchestrate *each other* across them: spinning up worker terminals, driving live browser tiles via CDP, generating PDF reports, and tracking work as first-class task tiles with a derived lifecycle (raw → researched → planned → executing → review → done). An entire HTTP API lets an agent in one tile spawn and wire up the rest.

> 💼 **My first commercial product** — AgentCanvas is the first thing I'm bringing to market. It's backed by a custom **Laravel + Inertia + React** platform for licensing, subscriptions, and device management: a customer portal for managing plans and an admin CRM driving sales, activation, and support.

### [Wickeban](https://github.com/ItsDlylan/wicke-kanban) — AI Agent Orchestration Platform
`Rust` `TypeScript` `React` `SQLx` `PostgreSQL`
Kanban-style task manager purpose-built for orchestrating AI coding agents. Manages parallel agent execution, task decomposition, plan generation, and PR review workflows. Supports Claude Code, Gemini CLI, Codex, and more. Full Rust backend with React frontend.

### Maison Neptune — Yacht Charter Platform
`Laravel 12` `Inertia v2` `TypeScript` `PHP 8.4`
Full-featured yacht charter booking platform with search, checkout, owner intake portal, admin dashboard, blog, and yacht management (pricing, fees, locations, media, toys). Built on the latest Laravel ecosystem.

### WickeTCG — Pokemon TCG Business Platform
`PHP` `JavaScript` `TypeScript` `Python`
All-in-one inventory, trading, and profit tracking for Pokemon TCG vendors. Tracks cost basis through multi-level trade chains, real-time TCGPlayer pricing, eBay integration, event/card show management with QR code sharing, grading submission tracking, and public storefronts.

---

## 🛠️ Open Source

### [WhisprMute](https://github.com/ItsDlylan/WhisprMute) — macOS Menu Bar App
`Swift`
Auto-mutes your mic in meeting apps when Wispr Flow is recording, then unmutes when done. Native Discord RPC and Chrome DevTools Protocol integration for focus-free muting — no keyboard shortcut juggling.

### [claude-dotfiles](https://github.com/ItsDlylan/claude-dotfiles)
My personal [Claude Code](https://docs.anthropic.com/en/docs/claude-code) scripts and configuration — version-controlled and ready to clone onto any machine.

Includes a **custom status line** with live usage quota tracking and context window visualization, **tab title management** with configurable ticket detection (Linear, Jira, GitHub Issues), **macOS notification hooks** for idle/permission/done events, and a **LaunchAgent watcher** that nudges you when scripts have uncommitted changes.

One `./install.sh` sets up symlinks so you can edit scripts in `~/.claude/scripts/` and track changes via git. Great starting point if you want to customize your own Claude Code setup.

### [Vegas-Agentic-Skills](https://github.com/ItsDlylan/Vegas-Agentic-Skills) — Claude Code Custom Skills
A collection of reusable [Claude Code skills](https://docs.anthropic.com/en/docs/claude-code) (slash commands) that extend agent capabilities. Symlinked to `~/.claude/skills/` for global availability across all projects.

| Skill | What it does |
|-------|-------------|
| **ship** | Full shipping workflow — merges feature branches to develop, generates changelogs, creates release PRs to main |
| **tier2** | Spins up isolated git worktree environments with their own PostgreSQL database and Herd site |
| **safety-net-brainstorm** | Spawns 5 parallel agents to brainstorm test cases after a bug fix, covering edge cases, state transitions, auth/security, integration, and failure modes |
| **agent-browser** | Browser automation with session isolation for parallel agent work — snapshot, click, fill, screenshot |
| **grill-me** | Stress-tests a plan or design by interviewing you relentlessly until every branch of the decision tree is resolved |
| **name-tab** | Auto-renames terminal tabs with `#project #branch #task` context |
| **remotion-best-practices** | Comprehensive rules for Remotion video creation in React |

---

## 💬 Ask Me About
- Building full applications with AI coding agents
- Orchestrating parallel AI agent workflows
- Rust + TypeScript for backend systems
- Laravel + Inertia for rapid full-stack development
- Going from idea → shipped product faster with Claude Code

---

## 🌐 Find Me
- **Portfolio** → [itsdlylan.github.io](https://itsdlylan.github.io/)
- **LinkedIn** → [linkedin.com/in/dylanschwindt](https://www.linkedin.com/in/dylanschwindt/)

---

> "Code should empower people — and the developers who write it."

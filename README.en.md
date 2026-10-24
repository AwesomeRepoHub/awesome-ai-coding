<div align="center">
<h3>AwesomeRepoHub</h3>
<h1>Awesome AI Coding</h1>
<p>AI tools that actually edit your codebase — terminal agents, IDE assistants, context tooling and specs</p>

<p><img alt="stars" src="https://img.shields.io/github/stars/AwesomeRepoHub/awesome-ai-coding?style=flat-square&color=0969da&label=stars"> <img alt="license" src="https://img.shields.io/github/license/AwesomeRepoHub/awesome-ai-coding?style=flat-square&color=2da44e"> <img alt="last commit" src="https://img.shields.io/github/last-commit/AwesomeRepoHub/awesome-ai-coding?style=flat-square&color=8250df"></p>

<p><a href="README.md">中文</a> · <a href="CONTRIBUTING.md">Contributing</a> · <a href="https://github.com/AwesomeRepoHub/awesome-index">All collections</a></p>
</div>

> **26 projects, 1.4M stars in total.** Stars, licenses and last-commit dates are pulled from the GitHub API and refreshed on 2026-10-24. Sorted by stars for reference only — popularity is not quality.

<sub>Reading the tables: stars and "Updated" come from the GitHub API at build time; license is read from the repository; notes in parentheses are limitations worth knowing first.</sub>

## Pick in 30 seconds

| Your situation | Start here |
|:--|:--|
| Chat and edit inside VS Code | [Cline](https://github.com/cline/cline) — autonomous edits, terminal access and screenshots in one panel — good for unfamiliar repos |
| Hand over a whole issue | [OpenHands](https://github.com/All-Hands-AI/OpenHands) — opens a shell, edits files, runs tests: closest thing to a junior engineer |
| Light edits from the terminal | [Aider](https://github.com/Aider-AI/aider) — git-based context control keeps diffs and rollbacks obvious |
| Code cannot leave the network | [Tabby](https://github.com/TabbyML/tabby) — self-hosted completion; model and data stay on your machines |

## Contents

- [Coding agents](#coding-agents)
- [Context and MCP tooling](#context-and-mcp-tooling)
- [Self-hosted](#self-hosted)
- [Specs and cost control](#specs-and-cost-control)
- [Chat and mobile access](#chat-and-mobile-access)

## Coding agents

_These read, write and execute inside your repo. The difference is how much autonomy they get and how tightly you can bound it._

| Project | What it does | Stars | License | Updated |
|:--|:--|--:|:--|--:|
| [OpenCode](https://github.com/sst/opencode) | The open source coding agent. | 221k | `MIT` | 2026-10 |
| [Codex CLI](https://github.com/openai/codex) | Lightweight coding agent that runs in your terminal | 131k | `Apache-2.0` | 2026-10 |
| [Gemini CLI](https://github.com/google-gemini/gemini-cli) | An open-source AI agent that brings the power of Gemini directly into your terminal. | 108k | `Apache-2.0` | 2026-10 |
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | 🙌 OpenHands: AI-Driven Development | 91.7k | `MIT` | 2026-10 |
| [Cline](https://github.com/cline/cline) | Autonomous coding agent as an SDK, IDE extension, or CLI assistant. | 70.8k | `Apache-2.0` | 2026-10 |
| [Goose](https://github.com/block/goose) | an open source, extensible AI agent that goes beyond code suggestions - install, execute, edit, and test with any LLM | 55.6k | `Apache-2.0` | 2026-10 |
| [Aider](https://github.com/Aider-AI/aider) | aider is AI pair programming in your terminal | 49.7k | `Apache-2.0` | 2026-05 |
| [Continue](https://github.com/continuedev/continue) | open-source coding agent | 36.3k | `Apache-2.0` | 2026-10 |
| [Qwen Code](https://github.com/QwenLM/qwen-code) | An open-source AI coding agent that lives in your terminal. | 28.7k | `Apache-2.0` | 2026-10 |
| [Kilo Code](https://github.com/Kilo-Org/kilocode) | Kilo is the all-in-one agentic engineering platform. Build, ship, and iterate faster with the most popular open source… | 27.7k | `MIT` | 2026-10 |
| [Superset](https://github.com/superset-sh/superset) | Superset is an agentic IDE to orchestrate 100+ coding agents in parallel. Run any agent with your own subscription.（资源占用高） | 15.5k | `custom` | 2026-10 |
| [Agent Orchestrator](https://github.com/OrchestratorInc/agent-orchestrator) | Open-source (Apache-2.0) orchestrator for Claude Code, Codex & 30+ coding agents. Plan, run and supervise agent teams… | 13.5k | `Apache-2.0` | 2026-10 |

<sub>[Back to top](#contents)</sub>

## Context and MCP tooling

_Strong models still fail on the wrong context. These projects fix "show it the right few hundred lines"._

| Project | What it does | Stars | License | Updated |
|:--|:--|--:|:--|--:|
| [Code Review Graph](https://github.com/tirth8205/code-review-graph) | Local-first code intelligence graph for MCP and CLI. Builds a persistent map of your codebase so AI coding tools read… | 32.4k | `MIT` | 2026-10 |
| [Serena](https://github.com/oraios/serena) | A powerful MCP toolkit for coding, providing semantic retrieval and editing capabilities - the IDE for your agent | 30.7k | `custom` | 2026-10 |
| [avante.nvim](https://github.com/yetone/avante.nvim) | Use your Neovim like using Cursor AI IDE! | 18.2k | `Apache-2.0` | 2026-10 |
| [Claude Context](https://github.com/zilliztech/claude-context) | Code search MCP for Claude Code. Make entire codebase the context for any coding agent. | 12.6k | `MIT` | 2026-07 |
| [Desktop Commander MCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) | This is MCP server for Claude that gives it terminal control, file system search and diff file editing capabilities | 10.1k | `MIT` | 2026-10 |

<sub>[Back to top](#contents)</sub>

## Self-hosted

_For teams whose code cannot leave the network._

| Project | What it does | Stars | License | Updated |
|:--|:--|--:|:--|--:|
| [Ollama](https://github.com/ollama/ollama) | Get up and running with Kimi, GLM, MiniMax, DeepSeek, gpt-oss, Qwen, Gemma and other models. | 184k | `MIT` | 2026-10 |
| [Tabby](https://github.com/TabbyML/tabby) | Self-hosted AI coding assistant | 33.9k | `custom` | 2026-06 |
| [Copilot for Xcode](https://github.com/intitni/CopilotForXcode) | The first GitHub Copilot, Codeium and ChatGPT Xcode Source Editor Extension | 8.2k | `MIT` | 2026-04 |

<sub>[Back to top](#contents)</sub>

## Specs and cost control

_Two ways to stop rework and token burn: write the spec first, then compress what you send._

| Project | What it does | Stars | License | Updated |
|:--|:--|--:|:--|--:|
| [rtk](https://github.com/rtk-ai/rtk) | CLI proxy that reduces LLM token consumption by 60-90% on common dev commands. Single Rust binary, zero dependencies | 84.4k | `Apache-2.0` | 2026-10 |
| [OpenSpec](https://github.com/Fission-AI/OpenSpec) | Spec-driven development (SDD) for AI coding assistants. | 72.9k | `MIT` | 2026-10 |
| [codeburn](https://github.com/getagentseal/codeburn) | Free, local tool to track AI coding token usage and cost across 37 tools and agents (Claude Code, Cursor, Codex, Gemini… | 11.6k | `MIT` | 2026-10 |
| [CCPM](https://github.com/automazeio/ccpm) | Project management skill system for Agents that uses GitHub Issues and Git worktrees for parallel agent execution. | 8.4k | `MIT` | 2026-10 |

<sub>[Back to top](#contents)</sub>

## Chat and mobile access

| Project | What it does | Stars | License | Updated |
|:--|:--|--:|:--|--:|
| [AionUi](https://github.com/iOfficeAI/AionUi) | Open-source 24/7 Cowork app for OpenClaw, Hermes, Claude Code, Codex, OpenCode and 20+ more CLI Agent \| Customize your… | 33.7k | `Apache-2.0` | 2026-10 |
| [cc-connect](https://github.com/chenhg5/cc-connect) | Bridge local AI coding agents (Claude Code, Cursor, Gemini CLI, Codex) to messaging platforms (Feishu/Lark, DingTalk…（许可证待确认） | 16.1k | `custom` | 2026-10 |

<sub>[Back to top](#contents)</sub>

## Why this list

AI coding tools look alike. What separates them is whether they can run and verify their own work, how they fetch context, and how you roll back. Hence the grouping: agents, context, specs — not vendors.

## Selection criteria

- A clear use case, a README you can follow and code that runs. No concept-only or demo-video projects.
- Explicit license and a repository that is not archived. Unmaintained projects are flagged and moved out of the main tables.
- One first choice per use case; alternatives sit in the same section for comparison instead of piling up.
- Stars are context, not a verdict. Maintenance cadence, issue response and docs matter more.
- Every line states the problem it solves and who it is for. No copy-pasted marketing copy.

## Contributing

Found a better project, a dead link or a wrong description? Open an issue or send a PR — see [CONTRIBUTING.md](CONTRIBUTING.md). Accepted entries get real stars and license data on the next build.

## About this list

- Stars, licenses and last-commit dates are fetched from the GitHub API at build time — never hand-copied, never stale.
- Adding or dropping a project edits one curated data file; the generator refreshes both languages and all numbers.
- If this saved you from opening a dozen repos, a **star** is the cheapest way to say thanks: [⭐ Star awesome-ai-coding](https://github.com/AwesomeRepoHub/awesome-ai-coding/stargazers)

## License

Content is licensed under [MIT](LICENSE) — reuse freely with attribution. Each project keeps its own copyright and license.

---

<sub>Generated from curated data and the GitHub API. Do not edit directly — see [CONTRIBUTING.md](CONTRIBUTING.md).</sub>

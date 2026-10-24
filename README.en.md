<div align="center">
<h3>AwesomeRepoHub</h3>
<h1>Awesome AI Coding</h1>
<p>AI tools that actually edit your codebase — terminal agents, IDE assistants, context tooling and specs</p>

<p><img alt="stars" src="https://img.shields.io/github/stars/AwesomeRepoHub/awesome-ai-coding?style=flat-square&color=0969da&label=stars"> <img alt="license" src="https://img.shields.io/github/license/AwesomeRepoHub/awesome-ai-coding?style=flat-square&color=2da44e"> <img alt="last commit" src="https://img.shields.io/github/last-commit/AwesomeRepoHub/awesome-ai-coding?style=flat-square&color=8250df"></p>

<p><a href="README.md">中文</a> · <a href="CONTRIBUTING.md">Contributing</a> · <a href="https://github.com/AwesomeRepoHub/awesome-index">All collections</a></p>
</div>

> **16 projects, 915k stars in total.** Stars, licenses and last-commit dates are pulled from the GitHub API and refreshed on 2026-10-24. Sorted by stars for reference only — popularity is not quality.

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

## Coding agents

These read, write and execute inside your repo. The difference is how much autonomy they get and how tightly you can bound it.

| Project | What it does | Stars | License |
|:--|:--|--:|:--|
| [Gemini CLI](https://github.com/google-gemini/gemini-cli) | An open-source AI agent that brings the power of Gemini directly into your terminal. | 108k | `Apache-2.0` |
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | 🙌 OpenHands: AI-Driven Development | 91.7k | `MIT` |
| [Cline](https://github.com/cline/cline) | Autonomous coding agent as an SDK, IDE extension, or CLI assistant. | 70.8k | `Apache-2.0` |
| [Goose](https://github.com/block/goose) | an open source, extensible AI agent that goes beyond code suggestions - install, execute, edit, and test with any LLM | 55.6k | `Apache-2.0` |
| [Aider](https://github.com/Aider-AI/aider) | aider is AI pair programming in your terminal | 49.7k | `Apache-2.0` |
| [Continue](https://github.com/continuedev/continue) | open-source coding agent | 36.3k | `Apache-2.0` |
| [Qwen Code](https://github.com/QwenLM/qwen-code) | An open-source AI coding agent that lives in your terminal. | 28.7k | `Apache-2.0` |
| [Kilo Code](https://github.com/Kilo-Org/kilocode) | Kilo is the all-in-one agentic engineering platform. Build, ship, and iterate faster with the most popular open source… | 27.7k | `MIT` |

<sub>[Back to top](#contents)</sub>

## Context and MCP tooling

Strong models still fail on the wrong context. These projects fix "show it the right few hundred lines".

| Project | What it does | Stars | License |
|:--|:--|--:|:--|
| [Serena](https://github.com/oraios/serena) | A powerful MCP toolkit for coding, providing semantic retrieval and editing capabilities - the IDE for your agent | 30.7k | `custom` |
| [avante.nvim](https://github.com/yetone/avante.nvim) | Use your Neovim like using Cursor AI IDE! | 18.2k | `Apache-2.0` |
| [Claude Context](https://github.com/zilliztech/claude-context) | Code search MCP for Claude Code. Make entire codebase the context for any coding agent. | 12.6k | `MIT` |
| [Desktop Commander MCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) | This is MCP server for Claude that gives it terminal control, file system search and diff file editing capabilities | 10.1k | `MIT` |

<sub>[Back to top](#contents)</sub>

## Self-hosted

For teams whose code cannot leave the network.

| Project | What it does | Stars | License |
|:--|:--|--:|:--|
| [Ollama](https://github.com/ollama/ollama) | Get up and running with Kimi, GLM, MiniMax, DeepSeek, gpt-oss, Qwen, Gemma and other models. | 184k | `MIT` |
| [Tabby](https://github.com/TabbyML/tabby) | Self-hosted AI coding assistant | 33.9k | `custom` |

<sub>[Back to top](#contents)</sub>

## Specs and cost control

Two ways to stop rework and token burn: write the spec first, then compress what you send.

| Project | What it does | Stars | License |
|:--|:--|--:|:--|
| [rtk](https://github.com/rtk-ai/rtk) | CLI proxy that reduces LLM token consumption by 60-90% on common dev commands. Single Rust binary, zero dependencies | 84.4k | `Apache-2.0` |
| [OpenSpec](https://github.com/Fission-AI/OpenSpec) | Spec-driven development (SDD) for AI coding assistants. | 72.9k | `MIT` |

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

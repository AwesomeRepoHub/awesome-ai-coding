<div align="center">
<h3>AwesomeRepoHub</h3>
<h1>AI 编程精选</h1>
<p>能改你代码库的 AI 工具：终端代理、IDE 插件、上下文与规范，按上手成本排序</p>

<p><img alt="stars" src="https://img.shields.io/github/stars/AwesomeRepoHub/awesome-ai-coding?style=flat-square&color=0969da&label=stars"> <img alt="license" src="https://img.shields.io/github/license/AwesomeRepoHub/awesome-ai-coding?style=flat-square&color=2da44e"> <img alt="last commit" src="https://img.shields.io/github/last-commit/AwesomeRepoHub/awesome-ai-coding?style=flat-square&color=8250df"></p>

<p><a href="README.en.md">English</a> · <a href="CONTRIBUTING.md">参与贡献</a> · <a href="REFERENCES.md">借鉴的清单</a> · <a href="https://github.com/AwesomeRepoHub/awesome-index">全部合集</a></p>
</div>

> **26 个项目，共 1.4M Stars。** Stars、许可证、最近提交时间由 GitHub API 实时读取，数据更新于 2026-10-24。排名按 Stars 排序，仅作热度参考，不代表质量。

<sub>读表说明：Stars 与「更新」都是生成时从 GitHub API 读到的真实值；许可证取自仓库；括号里是使用前要知道的限制。</sub>

## 30 秒选型

| 你的情况 | 从这里开始 |
|:--|:--|
| 在 VS Code 里边聊边改 | [Cline](https://github.com/cline/cline) — 自主改文件、跑命令、看截图都在一个面板，适合接手陌生项目 |
| 丢一个 issue 让它自己做完 | [OpenHands](https://github.com/All-Hands-AI/OpenHands) — 会自己开终端、改代码、跑测试，接近一个初级工程师 |
| 终端里轻量改，不想开 IDE | [Aider](https://github.com/Aider-AI/aider) — 靠 git 提交控制上下文，回滚和对比都清楚 |
| 代码不能出内网 | [Tabby](https://github.com/TabbyML/tabby) — 自托管补全，模型和数据都在自己机器上 |

## 目录

- [编码代理](#编码代理)
- [上下文与工具协议](#上下文与工具协议)
- [自托管与内网](#自托管与内网)
- [规范与成本控制](#规范与成本控制)
- [协作与消息接入](#协作与消息接入)

## 编码代理

_能自主读写仓库、执行命令的一类，差别在权限范围与可控性。_

| 项目 | 一句话说明 | Stars | 许可证 | 更新 |
|:--|:--|--:|:--|--:|
| [OpenCode](https://github.com/sst/opencode) | 开源编码 agent，终端与 IDE 都能用，provider 可换 | 221k | `MIT` | 2026-10 |
| [Codex CLI](https://github.com/openai/codex) | OpenAI 官方终端 agent，沙箱里跑命令、改代码，规格写得很细 | 131k | `Apache-2.0` | 2026-10 |
| [Gemini CLI](https://github.com/google-gemini/gemini-cli) | Gemini 官方终端代理，免费额度大，能直接读整个仓库 | 108k | `Apache-2.0` | 2026-10 |
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | 会开终端、改代码、跑测试的开源工程师，社区最活跃之一 | 91.7k | `MIT` | 2026-10 |
| [Cline](https://github.com/cline/cline) | VS Code 里的自主编码代理，改文件、跑命令、看截图都在一个面板 | 70.8k | `Apache-2.0` | 2026-10 |
| [Goose](https://github.com/block/goose) | Block 开源的本地代理，可接任意模型，能力靠 MCP 扩展 | 55.6k | `Apache-2.0` | 2026-10 |
| [Aider](https://github.com/Aider-AI/aider) | 命令行改代码的老牌选手，用 git 提交做上下文，适合脚本化 | 49.7k | `Apache-2.0` | 2026-05 |
| [Continue](https://github.com/continuedev/continue) | 自建补全与对话，支持本地模型，团队可共享规则 | 36.3k | `Apache-2.0` | 2026-10 |
| [Qwen Code](https://github.com/QwenLM/qwen-code) | 通义千问的终端代理，中文场景与国产模型适配好 | 28.7k | `Apache-2.0` | 2026-10 |
| [Kilo Code](https://github.com/Kilo-Org/kilocode) | 一体化代理平台，内置多模型与任务编排 | 27.7k | `MIT` | 2026-10 |
| [Superset](https://github.com/superset-sh/superset) | 在一个 IDE 里并行跑上百个 coding agent（资源占用高） | 15.5k | `自定义` | 2026-10 |
| [Agent Orchestrator](https://github.com/OrchestratorInc/agent-orchestrator) | 给 Claude Code、Codex 等 30+ agent 派活与回收结果 | 13.5k | `Apache-2.0` | 2026-10 |

<sub>[回到目录](#目录)</sub>

## 上下文与工具协议

_模型再强，取不到对的代码也白搭。这一组解决“让它看到正确的那几百行”。_

| 项目 | 一句话说明 | Stars | 许可证 | 更新 |
|:--|:--|--:|:--|--:|
| [Code Review Graph](https://github.com/tirth8205/code-review-graph) | 本地代码知识图谱，给 MCP 与 CLI 提供结构化上下文 | 32.4k | `MIT` | 2026-10 |
| [Serena](https://github.com/oraios/serena) | 用语言服务器做语义检索和精确改写，比全文搜索省大量 token | 30.7k | `自定义` | 2026-10 |
| [avante.nvim](https://github.com/yetone/avante.nvim) | Neovim 里的类 Cursor 体验，侧边对话直接改缓冲区 | 18.2k | `Apache-2.0` | 2026-10 |
| [Claude Context](https://github.com/zilliztech/claude-context) | 把整个代码库做成向量索引给编码代理用，大仓库检索快 | 12.6k | `MIT` | 2026-07 |
| [Desktop Commander MCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) | 给 Claude 桌面端加终端与文件系统控制，MCP 入门首选 | 10.1k | `MIT` | 2026-10 |

<sub>[回到目录](#目录)</sub>

## 自托管与内网

_代码不能出门时的选项。_

| 项目 | 一句话说明 | Stars | 许可证 | 更新 |
|:--|:--|--:|:--|--:|
| [Ollama](https://github.com/ollama/ollama) | 一条命令在本地跑开源模型，配 Continue 或 Tabby 就能全离线写代码 | 184k | `MIT` | 2026-10 |
| [Tabby](https://github.com/TabbyML/tabby) | 可自托管的代码补全服务，模型与数据都不出内网 | 33.9k | `自定义` | 2026-06 |
| [Copilot for Xcode](https://github.com/intitni/CopilotForXcode) | Xcode 里的补全与对话，macOS 开发者的 Copilot 替代 | 8.2k | `MIT` | 2026-04 |

<sub>[回到目录](#目录)</sub>

## 规范与成本控制

_让 AI 少返工、少烧 token 的两条路：先写规格，再压缩上下文。_

| 项目 | 一句话说明 | Stars | 许可证 | 更新 |
|:--|:--|--:|:--|--:|
| [rtk](https://github.com/rtk-ai/rtk) | 代理层压缩开发命令的输出，常用于省 60-90% token | 84.4k | `Apache-2.0` | 2026-10 |
| [OpenSpec](https://github.com/Fission-AI/OpenSpec) | 先写规格再让 AI 实现，把“改坏了”的概率压下来 | 72.9k | `MIT` | 2026-10 |
| [codeburn](https://github.com/getagentseal/codeburn) | 本地统计 37 种 AI 编程工具的 token 与花费 | 11.6k | `MIT` | 2026-10 |
| [CCPM](https://github.com/automazeio/ccpm) | 用 GitHub Issues 驱动 agent 的项目管理流程，任务不会跑丢 | 8.4k | `MIT` | 2026-10 |

<sub>[回到目录](#目录)</sub>

## 协作与消息接入

_把本地 agent 接到手机和聊天窗口，出门也能推进任务。_

| 项目 | 一句话说明 | Stars | 许可证 | 更新 |
|:--|:--|--:|:--|--:|
| [AionUi](https://github.com/iOfficeAI/AionUi) | 桌面端多 agent 协作界面，一个窗口同时盯几个 CLI agent | 33.7k | `Apache-2.0` | 2026-10 |
| [cc-connect](https://github.com/chenhg5/cc-connect) | 把本地 coding agent 接到消息平台，手机上也能派活（许可证待确认） | 16.1k | `自定义` | 2026-10 |

<sub>[回到目录](#目录)</sub>

## 为什么值得看

AI 编程工具的同质化很严重，真正拉开差距的是三件事：**能不能自己跑起来验证**、**上下文怎么取**、**出错能不能回滚**。所以这份清单按“代理 / 上下文 / 规范”分组，而不是按模型厂商分组。

## 收录标准

- 有明确用途，README 能看懂、能跑起来；不收录只发概念或演示视频的项目。
- 许可证明确，仓库未归档；长期不更新的项目会标注并移出主表。
- 同一定位只留一个首选，同类项目放进同一小节横向对比，不做堆砌。
- Stars 只作参考，主要看维护频率、issue 响应和文档质量。
- 每条说明写清“解决什么问题、适合谁”，不搬运项目自述。

## 参与贡献

发现更好的项目、链接失效或说明有误？欢迎开 issue 或直接提交 PR，格式与要求见 [CONTRIBUTING.md](CONTRIBUTING.md)。收录后会在下一次生成时自动带上真实 Stars 与许可证。

## 关于这份清单

- 表里的 Stars、许可证、最近提交都是生成时从 GitHub API 拉取的，不是手写数字，所以不会过期。
- 每次增删项目只改一份精选数据，再跑生成脚本，中英文两个版本与 Stars 同时更新。
- 如果这份清单帮你少翻了十几个仓库，点个 **Star** 是最直接的支持：[⭐ Star awesome-ai-coding](https://github.com/AwesomeRepoHub/awesome-ai-coding/stargazers)

## 许可

内容采用 [MIT](LICENSE) 许可，可自由转载，注明来源即可。项目本身的版权与许可归各作者所有。

---

<sub>本文件由脚本从精选数据与 GitHub API 自动生成，请勿直接编辑；增删条目见 [CONTRIBUTING.md](CONTRIBUTING.md)。</sub>

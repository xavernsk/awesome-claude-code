<!--lint disable remark-lint:awesome-badge-->

#

<!-- [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re) -->

<pre style="display: inline-block; text-align: left;">
 █████┐ ██┐    ██┐███████┐███████┐ ██████┐ ███┐   ███┐███████┐
██┌──██┐██│    ██│██┌────┘██┌────┘██┌───██┐████┐ ████│██┌────┘
███████│██│ █┐ ██│█████┐  ███████┐██│   ██│██┌████┌██│█████┐
██┌──██│██│███┐██│██┌──┘  └────██│██│   ██│██│└██┌┘██│██┌──┘
██│  ██│└███┌███┌┘███████┐███████│└██████┌┘██│ └─┘ ██│███████┐
└─┘  └─┘ └──┘└──┘ └──────┘└──────┘ └─────┘ └─┘     └─┘└──────┘

 ────────────────────────────────────────────────────────────────────────────────────

 ██████┐██┐      █████┐ ██┐   ██┐██████┐ ███████┐     ██████┐ ██████┐ ██████┐ ███████┐
██┌────┘██│     ██┌──██┐██│   ██│██┌──██┐██┌────┘    ██┌────┘██┌───██┐██┌──██┐██┌────┘
██│     ██│     ███████│██│   ██│██│  ██│█████┐      ██│     ██│   ██│██│  ██│█████┐
██│     ██│     ██┌──██│██│   ██│██│  ██│██┌──┘      ██│     ██│   ██│██│  ██│██┌──┘
└██████┐███████┐██│  ██│└██████┌┘██████┌┘███████┐    └██████┐└██████┌┘██████┌┘███████┐
 └─────┘└──────┘└─┘  └─┘ └─────┘ └─────┘ └──────┘     └─────┘ └─────┘ └─────┘ └──────┘
</pre>

<!--lint enable remark-lint:awesome-badge-->

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

# [很棒的 Claude 代码](https://github.com/hesreallyhim/awesome-claude-code) 🤝 [很棒的 Claude 代码代理](https://github.com/hesreallyhim/awesome-claude-code-agents)

<!--lint enable remark-lint:awesome-badge-->

<!--lint disable double-link-->

这是一个精选的斜杠命令、`CLAUDE.md` 文件、CLI 工具以及其他资源和指南的列表，用于增强您的 [Claude 代码](https://docs.anthropic.com/en/docs/claude-code) 工作流程、生产力和氛围。

<!--lint enable double-link-->

Claude Code 是一款前沿的基于 CLI 的编码助手和代理，您可以在终端或 IDE 中访问它。它是一个快速发展的工具，提供了许多强大的功能，并允许以多种不同的方式进行大量配置。用户正在积极探索最佳实践和工作流程。希望这个仓库能帮助社区分享知识，并了解如何充分利用 Claude Code。

### 公告

- 2025-07-30 - 快速更新：仍在努力解决提交流程问题（对于收到重复的“恭喜！”问题的任何人，我们深表歉意）。如果您最终与任何程序化提交工具作斗争，只需提交包含所有必要数据的内容，一旦获得批准，我就会处理。其他说明：（i）我认为建立一个“Claude 代码排行榜”会非常酷/有趣，所以请随时在[讨论](https://github.com/hesreallyhim/awesome-claude-code/discussions/81)中发表您的看法；（ii）我仍在努力弄清楚如何处理 **子代理**，并且我已经联系了其他一些已经开始类似仓库的人；（iii）增加了一个小部分，随着新提交的到来，该部分将进行更新。

## 新增内容

- [`CC Notify`](https://github.com/dazuiba/CCNotify) by [dazuiba](https://github.com/dazuiba)
- [`tweakcc`](https://github.com/Piebald-AI/tweakcc) by [Piebald-AI](https://github.com/Piebald-AI)
- [`cchooks`](https://github.com/GowayLee/cchooks) by [GowayLee](https://github.com/GowayLee)

<br>

## 目录

▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[工作流程和知识指南](#工作流程和知识指南-)
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[工具](#工具-)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[IDE 集成](#ide-集成)
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[挂钩](#挂钩-)
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[斜杠命令](#斜杠命令-)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[版本控制和 Git](#版本控制和-git)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[代码分析和测试](#代码分析和测试)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[上下文加载和启动](#上下文加载和启动)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[文档和变更日志](#文档和变更日志)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[CI / 部署](#ci--部署)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[项目和任务管理](#项目和任务管理)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[杂项](#杂项)
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[CLAUDE.md 文件](#claudemd-文件-)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[特定语言](#特定语言)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[特定领域](#特定领域)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[项目脚手架和 MCP](#项目脚手架和-mcp)
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[官方文档](#官方文档-)

<br>

## 工作流程和知识指南 🧠

> **工作流程**是一组紧密耦合的 Claude Code 原生资源，可促进特定项目。

[`博客平台说明`](https://github.com/cloudartisan/cloudartisan.github.io/tree/main/.claude/commands) &nbsp; by &nbsp; [cloudartisan](https://github.com/cloudartisan)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;CC-BY-SA-4.0
提供了一套结构良好的命令，用于发布和维护博客平台，包括用于创建帖子、管理类别和处理媒体文件的命令。

[`ClaudeLog`](https://claudelog.com) &nbsp; by &nbsp; [InventorBlack](https://www.reddit.com/user/inventor_black/)
一个全面的知识库，详细分解了高级[机制](https://claudelog.com/mechanics/you-are-the-main-thread/)，包括 [CLAUDE.md 最佳实践](https://claudelog.com/mechanics/claude-md-supremacy)、[计划模式](https://claudelog.com/mechanics/plan-mode)等实用技术指南、[超思维](https://claudelog.com/faqs/what-is-ultrathink/)、[子代理](https://claudelog.com/mechanics/task-agent-tools/)、[代理优先设计](https://claudelog.com/mechanics/agent-first-design/)和[配置指南](https://claudelog.com/configuration)。

[`上下文启动`](https://github.com/disler/just-prompt/tree/main/.claude/commands) &nbsp; by &nbsp; [disler](https://github.com/disler)
通过针对不同项目场景和开发环境的专门命令，提供了一种系统的方法来为 Claude Code 启动全面的项目上下文。

[`n8n_agent`](https://github.com/kingler/n8n_agent/tree/main/.claude/commands) &nbsp; by &nbsp; [kingler](https://github.com/kingler)
令人惊叹的全面评论集，涵盖代码分析、质量保证、设计、文档、项目结构、项目管理、优化等等。

[`项目引导和任务管理`](https://github.com/steadycursor/steadystart/tree/main/.claude/commands) &nbsp; by &nbsp; [steadycursor](https://github.com/steadycursor)
提供了一套结构化的命令，用于引导和管理新项目，包括用于创建和编辑自定义斜杠命令的元命令。

[`项目管理、实施、规划和发布`](https://github.com/scopecraft/command/tree/main/.claude/commands) &nbsp; by &nbsp; [scopecraft](https://github.com/scopecraft)
真正全面的命令集，涵盖 SDLC 的所有方面。

[`项目工作流系统`](https://github.com/harperreed/dotfiles/tree/master/.claude/commands) &nbsp; by &nbsp; [harperreed](https://github.com/harperreed)
一套提供全面项目管理工作流系统的命令，包括任务管理、代码审查和部署流程。

[`使用 Claude 交付真实代码`](https://diwank.space/field-notes-from-shipping-real-code-with-claude) &nbsp; by &nbsp; [Diwank](https://github.com/creatorrr)
一篇详细的博客文章，解释了作者使用 Claude Code 交付产品的过程，包括 CLAUDE.md 文件和其他有趣的资源。

[`Simone`](https://github.com/Helmi/claude-simone) &nbsp; by &nbsp; [Helmi](https://github.com/Helmi)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
一个更广泛的 Claude Code 项目管理工作流程，不仅包含一组命令，还包含一个文件、指南和流程系统，以促进项目规划和执行。

[`斜杠命令超大列表`](https://github.com/wcygan/dotfiles/tree/d8ab6b9f5a7a81007b7f5fa3025d4f83ce12cc02/claude/commands) &nbsp; by &nbsp; [wcygan](https://github.com/wcygan)
一个非常惊人的斜杠命令列表（在撰写本文时有 88 个！），范围从代理编排、代码审查、项目管理、安全、文档、自我评估，几乎涵盖了您能想到的任何事情。

<br>

## 工具 🧰

> **工具**表示构建在 Claude Code 之上的应用程序，并且包含比斜杠命令和 `CLAUDE.md` 文件更多的组件。

[`CC Usage`](https://github.com/ryoppippi/ccusage) &nbsp; by &nbsp; [ryoppippi](https://github.com/ryoppippi)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
方便的 CLI 工具，用于管理和分析 Claude Code 的使用情况，基于对本地 Claude Code 日志的分析。提供了一个漂亮的仪表板，显示成本信息、令牌消耗等。

[`ccexp`](https://github.com/nyatinte/ccexp) &nbsp; by &nbsp; [nyatinte](https://github.com/nyatinte)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
交互式 CLI 工具，用于发现和管理 Claude Code 配置文件和斜杠命令，具有漂亮的终端用户界面。

[`cclogviewer`](https://github.com/Brads3290/cclogviewer) &nbsp; by &nbsp; [Brad S.](https://github.com/Brads3290)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
一个不起眼但方便的实用程序，用于在漂亮的 HTML 用户界面中查看 Claude Code `.jsonl` 对话文件。

[`Claude Code Flow`](https://github.com/ruvnet/claude-code-flow) &nbsp; by &nbsp; [ruvnet](https://github.com/ruvnet)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
此模式充当代码优先的编排层，使 Claude 能够跨递归代理周期自主编写、编辑、测试和优化代码。

[`Claude Code Usage Monitor`](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor) &nbsp; by &nbsp; [Maciek-roboblog](https://github.com/Maciek-roboblog)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
一个基于终端的实时工具，用于监控 Claude Code 令牌的使用情况。它显示实时令牌消耗、消耗率和令牌耗尽预测。功能包括可视化进度条、会话感知分析以及对多个订阅计划的支持。

[`Claude Composer`](https://github.com/possibilities/claude-composer) &nbsp; by &nbsp; [Mike Bannister](https://github.com/possibilities)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Unlicense
一个为 Claude Code 添加小增强功能的工具。

[`Claude Hub`](https://github.com/claude-did-this/claude-hub) &nbsp; by &nbsp; [Claude Did This](https://github.com/claude-did-this)
一个 webhook 服务，可将 Claude Code 连接到 GitHub 存储库，从而直接通过拉取请求和问题提供 AI 驱动的代码帮助。这种集成使 Claude 能够分析存储库、回答技术问题，并通过简单的 @提及帮助开发人员理解和改进他们的代码库。

[`Claude Squad`](https://github.com/smtg-ai/claude-squad) &nbsp; by &nbsp; [smtg-ai](https://github.com/smtg-ai)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;AGPL-3.0
Claude Squad 是一个终端应用程序，可在单独的工作区中管理多个 Claude Code、Codex（以及包括 Aider 在内的其他本地代理），让您可以同时处理多个任务。

[`Claude Swarm`](https://github.com/parruda/claude-swarm) &nbsp; by &nbsp; [parruda](https://github.com/parruda)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
启动一个连接到 Claude Code 代理群的 Claude Code 会话。

[`Claude Task Master`](https://github.com/eyaltoledano/claude-task-master) &nbsp; by &nbsp; [eyaltoledano](https://github.com/eyaltoledano)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
一个用于 AI 驱动开发的任务管理系统，与 Claude 配合使用，旨在与 Cursor AI 无缝协作。

[`Claude Task Runner`](https://github.com/grahama1970/claude-task-runner) &nbsp; by &nbsp; [grahama1970](https://github.com/grahama1970)
一个专门的工具，用于管理上下文隔离和使用 Claude Code 进行集中任务执行，解决了在使用 Claude 处理复杂的多步骤项目时上下文长度限制和任务焦点的关键挑战。

[`claude-code-tools`](https://github.com/pchalasani/claude-code-tools) &nbsp; by &nbsp; [Prasad Chalasani](https://github.com/pchalasani)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
一系列很棒的工具，包括 tmux 集成、更好的会话管理、增强安全性的挂钩——一套做得非常好的 Claude Code 增强器，尤其适合 tmux 用户。

[`Container Use`](https://github.com/dagger/container-use) &nbsp; by &nbsp; [dagger](https://github.com/dagger)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
编码代理的开发环境。使多个代理能够安全、独立地使用您首选的堆栈。

[`TSK - AI 代理任务管理器和沙箱`](https://github.com/dtormoen/tsk) &nbsp; by &nbsp; [dtormoen](https://github.com/dtormoen)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
一个 Rust CLI 工具，可让您将开发任务委托给在沙盒 Docker 环境中运行的 AI 代理。多个代理并行工作，返回 git 分支供人工审查。

[`tweakcc`](https://github.com/Piebald-AI/tweakcc) &nbsp; by &nbsp; [Piebald-AI](https://github.com/Piebald-AI)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
用于自定义 Claude Code 样式的命令行工具。

[`viberank`](https://github.com/sculptdotfun/viberank) &nbsp; by &nbsp; [nikshepsvn](https://github.com/nikshepsvn)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
一个社区驱动的排行榜工具，使开发人员能够根据其 Claude Code 使用情况统计信息进行可视化、跟踪和竞争。它具有强大的数据分析、GitHub OAuth、数据验证和用户友好的 CLI/Web 提交方法。

### IDE 集成

[`Claude Code Chat`](https://marketplace.visualstudio.com/items?itemName=AndrePimenta.claude-code-chat) &nbsp; by &nbsp; [andrepimenta](https://github.com/andrepimenta)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;&copy;
一个优雅且用户友好的 VS Code 的 Claude Code 聊天界面。

[`claude-code-ide.el`](https://github.com/manzaltu/claude-code-ide.el) &nbsp; by &nbsp; [manzaltu](https://github.com/manzaltu)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;GPL-3.0
claude-code-ide.el 将 Claude Code 与 Emacs 集成，就像 Anthropic 的 VS Code/IntelliJ 扩展一样。它显示基于 ediff 的代码建议，提取 LSP/flymake/flycheck 诊断信息，并跟踪缓冲区上下文。它为符号引用/定义、项目元数据和 tree-sitter AST 查询添加了可扩展的 MCP 工具支持。

[`claude-code.el`](https://github.com/stevemolitor/claude-code.el) &nbsp; by &nbsp; [stevemolitor](https://github.com/stevemolitor)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
一个用于 Claude Code CLI 的 Emacs 界面。

[`claude-code.nvim`](https://github.com/greggh/claude-code.nvim) &nbsp; by &nbsp; [greggh](https://github.com/greggh)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Claude Code AI 助手和 Neovim 之间的无缝集成。

[`crystal`](https://github.com/stravu/crystal) &nbsp; by &nbsp; [stravu](https://github.com/stravu)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
一个功能齐全的桌面应用程序，用于编排、监控和与 Claude Code 代理交互。

<br>

## 挂钩 🪝

> **挂钩**是 Claude Code 的一个全新 API，允许用户在 Claude 的代理生命周期的不同点激活命令和运行脚本。

**[实验性]** - 本节中列出的资源尚未经过全面审查，可能无法按预期工作，因为 Claude Code 挂钩具有前沿性。尽管如此，我还是希望将它们至少作为灵感来源并探索这个未知领域。您的体验可能会有所不同！

[`CC Notify`](https://github.com/dazuiba/CCNotify) &nbsp; by &nbsp; [dazuiba](https://github.com/dazuiba)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
CCNotify 为 Claude Code 提供桌面通知，提醒您需要输入或任务完成，并提供一键跳转回 VS Code 和任务持续时间显示。

[`cchooks`](https://github.com/GowayLee/cchooks) &nbsp; by &nbsp; [GowayLee](https://github.com/GowayLee)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
一个轻量级的 Python SDK，具有简洁的 API 和良好的文档；简化了编写挂钩并将其集成到代码库中的过程，在 JSON 配置文件之上提供了一个很好的抽象。

[`claude-code-hooks-sdk`](https://github.com/beyondcode/claude-hooks-sdk) &nbsp; by &nbsp; [beyondcode](https://github.com/beyondcode)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
一个受 Laravel 启发的 PHP SDK，用于使用简洁、流畅的 API 构建 Claude Code 挂钩响应。此 SDK 使使用富有表现力、可链接的界面轻松创建结构化的 JSON 响应成为可能。

[`claude-hooks`](https://github.com/johnlindquist/claude-hooks) &nbsp; by &nbsp; [John Lindquist](https://github.com/johnlindquist)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
一个基于 TypeScript 的系统，用于使用功能强大且灵活的界面配置和自定义 Claude Code 挂钩。

[`Linting、测试和通知（在 go 中）`](https://github.com/Veraticus/nix-config/tree/main/home-manager/claude-code/hooks) &nbsp; by &nbsp; [Josh Symonds](https://github.com/Veraticus)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
一套不错的挂钩，用于强制执行代码质量（linting、测试、通知），并具有不错的配置设置。

[`TDD Guard`](https://github.com/nizos/tdd-guard) &nbsp; by &nbsp; [Nizar Selander](https://github.com/nizos)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
一个由挂钩驱动的系统，可实时监控文件操作并阻止违反 TDD 原则的更改。

<br>

## 斜杠命令 🔪

### 版本控制和 Git

[`/bug-fix`](https://github.com/danielscholl/mvn-mcp-server/blob/main/.claude/commands/bug-fix.md) &nbsp; by &nbsp; [danielscholl](https://github.com/danielscholl)
通过首先创建 GitHub 问题，然后创建一个功能分支来实施和彻底测试解决方案，然后再合并，从而简化了错误修复。

[`/commit`](https://github.com/evmts/tevm-monorepo/blob/main/.claude/commands/commit.md) &nbsp; by &nbsp; [evmts](https://github.com/evmts)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
使用带有适当表情符号的常规提交格式创建 git 提交，遵循项目标准并创建描述性消息来解释更改的目的。

[`/commit-fast`](https://github.com/steadycursor/steadystart/blob/main/.claude/commands/2-commit-fast.md) &nbsp; by &nbsp; [steadycursor](https://github.com/steadycursor)
通过选择第一个建议的消息来自动化 git 提交过程，生成具有一致格式的结构化提交，同时跳过手动确认并删除 Claude 共同贡献者页脚。

[`/create-pr`](https://github.com/toyamarinyon/giselle/blob/main/.claude/commands/create-pr.md) &nbsp; by &nbsp; [toyamarinyon](https://github.com/toyamarinyon)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
通过处理整个工作流程来简化拉取请求的创建：创建新分支、提交更改、使用 Biome 格式化修改后的文件以及提交 PR。

[`/create-pull-request`](https://github.com/liam-hq/liam/blob/main/.claude/commands/create-pull-request.md) &nbsp; by &nbsp; [liam-hq](https://github.com/liam-hq)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
提供使用 GitHub CLI 创建 PR 的全面指南，强制执行标题约定，遵循模板结构，并提供具体的命令示例和最佳实践。

[`/create-worktrees`](https://github.com/evmts/tevm-monorepo/blob/main/.claude/commands/create-worktrees.md) &nbsp; by &nbsp; [evmts](https://github.com/evmts)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
为所有打开的 PR 或特定分支创建 git 工作树，处理带斜杠的分支，清理过时的工作树，并支持为开发创建自定义分支。

[`/fix-github-issue`](https://github.com/jeremymailen/kotlinter-gradle/blob/master/.claude/commands/fix-github-issue.md) &nbsp; by &nbsp; [jeremymailen](https://github.com/jeremymailen)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
使用 GitHub CLI 的结构化方法分析和修复 GitHub 问题，以获取问题详细信息，实施必要的代码更改，运行测试并创建正确的提交消息。

[`/fix-issue`](https://github.com/metabase/metabase/blob/master/.claude/commands/fix-issue.md) &nbsp; by &nbsp; [metabase](https://github.com/metabase)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
通过将问题编号作为参数，分析上下文，实施解决方案以及测试/验证修复程序以实现正确集成来解决 GitHub 问题。

[`/fix-pr`](https://github.com/metabase/metabase/blob/master/.claude/commands/fix-pr.md) &nbsp; by &nbsp; [metabase](https://github.com/metabase)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
通过自动检索反馈、解决审阅者关注的问题、进行有针对性的代码改进以及简化审阅过程来获取和修复未解决的 PR 评论。

[`/husky`](https://github.com/evmts/tevm-monorepo/blob/main/.claude/commands/husky.md) &nbsp; by &nbsp; [evmts](https://github.com/evmts)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
通过配置预提交挂钩、建立提交消息标准、与 linting 工具集成以及确保提交时的代码质量来设置和管理 Husky Git 挂钩。

[`/pr-review`](https://github.com/arkavo-org/opentdf-rs/blob/main/.claude/commands/pr-review.md) &nbsp; by &nbsp; [arkavo-org](https://github.com/arkavo-org)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
在合并到主代码库之前，审查拉取请求更改以提供反馈、检查问题并提出改进建议。

[`/update-branch-name`](https://github.com/giselles-ai/giselle/blob/main/.claude/commands/update-branch-name.md) &nbsp; by &nbsp; [giselles-ai](https://github.com/giselles-ai)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
使用正确的前缀和格式更新分支名称，强制执行命名约定，支持语义前缀以及管理远程分支更新。

### 代码分析和测试

[`/check`](https://github.com/rygwdn/slack-tools/blob/main/.claude/commands/check.md) &nbsp; by &nbsp; [rygwdn](https://github.com/rygwdn)
执行全面的代码质量和安全检查，具有静态分析集成、安全漏洞扫描、代码样式强制执行和详细报告。

[`/clean`](https://github.com/Graphlet-AI/eridu/blob/main/.claude/commands/clean.md) &nbsp; by &nbsp; [Graphlet-AI](https://github.com/Graphlet-AI)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
通过修复 black 格式问题、使用 isort 组织导入、解决 flake8 linting 问题以及纠正 mypy 类型错误来解决代码格式和质量问题。

[`/code_analysis`](https://github.com/kingler/n8n_agent/blob/main/.claude/commands/code_analysis.md) &nbsp; by &nbsp; [kingler](https://github.com/kingler)
提供一个高级代码分析命令菜单，用于深入检查，包括知识图生成、优化建议和质量评估。

[`/optimize`](https://github.com/to4iki/ai-project-rules/blob/main/.claude/commands/optimize.md) &nbsp; by &nbsp; [to4iki](https://github.com/to4iki)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
分析代码性能以识别瓶颈，提出具体的优化建议并提供实施指导，以提高应用程序性能。

[`/repro-issue`](https://github.com/rzykov/metabase/blob/master/.claude/commands/repro-issue.md) &nbsp; by &nbsp; [rzykov](https://github.com/rzykov)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
为 GitHub 问题创建可重现的测试用例，确保测试可靠地失败，并为开发人员记录清晰的重现步骤。

[`/tdd`](https://github.com/zscott/pane/blob/main/.claude/commands/tdd.md) &nbsp; by &nbsp; [zscott](https://github.com/zscott)
使用测试驱动开发原则指导开发，强制执行红-绿-重构纪律，与 git 工作流集成以及管理 PR 创建。

### 上下文加载和启动

[`/context-prime`](https://github.com/elizaOS/elizaos.github.io/blob/main/.claude/commands/context-prime.md) &nbsp; by &nbsp; [elizaOS](https://github.com/elizaOS)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
通过加载存储库结构、设置开发上下文、建立项目目标和定义协作参数，为 Claude 提供全面的项目理解。

[`/initref`](https://github.com/okuvshynov/cubestat/blob/main/.claude/commands/initref.md) &nbsp; by &nbsp; [okuvshynov](https://github.com/okuvshynov)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
使用标准文档模板、API 参考设置、文档约定和占位符内容生成来初始化参考文档结构。

[`/load-llms-txt`](https://github.com/ethpandaops/xatu-data/blob/master/.claude/commands/load-llms-txt.md) &nbsp; by &nbsp; [ethpandaops](https://github.com/ethpandaops)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
将 LLM 配置文件加载到上下文中，导入特定术语、模型配置并为 AI 讨论建立基线术语。

[`/load_coo_context`](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/load_coo_context.md) &nbsp; by &nbsp; [Mjvolk3](https://github.com/Mjvolk3)
引用稀疏矩阵运算的特定文件，解释转换用法，与以前的方法进行比较，并为开发设置数据格式化上下文。

[`/load_dango_pipeline`](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/load_dango_pipeline.md) &nbsp; by &nbsp; [Mjvolk3](https://github.com/Mjvolk3)
通过引用管道文件、建立工作上下文以及使用相关文档为管道工作做准备来设置模型训练的上下文。

[`/prime`](https://github.com/yzyydev/AI-Engineering-Structure/blob/main/.claude/commands/prime.md) &nbsp; by &nbsp; [yzyydev](https://github.com/yzyydev)
通过查看目录结构和读取关键文件来设置初始项目上下文，使用目录可视化和关键文档焦点创建标准化的上下文。

[`/rsi`](https://github.com/ddisisto/si/blob/main/.claude/commands/rsi.md) &nbsp; by &nbsp; [ddisisto](https://github.com/ddisisto)
读取所有命令和关键项目文件以优化 AI 辅助开发，方法是简化流程、加载命令上下文以及为更好的开发工作流程进行设置。

### 文档和变更日志

[`/add-to-changelog`](https://github.com/berrydev-ai/blockdoc-python/blob/main/.claude/commands/add-to-changelog.md) &nbsp; by &nbsp; [berrydev-ai](https://github.com/berrydev-ai)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
在保持格式一致性的同时向变更日志文件添加新条目，正确记录更改并遵循已建立的项目标准进行版本跟踪。

[`/create-docs`](https://github.com/jerseycheese/Narraitor/tree/feature/issue-227-ai-suggestions/.claude/commands/analyze-issue.md) &nbsp; by &nbsp; [jerseycheese](https://github.com/jerseycheese)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
分析代码结构和目的以创建全面的文档，详细说明输入/输出、行为、用户交互流程以及带有错误处理的边缘情况。

[`/docs`](https://github.com/slunsford/coffee-analytics/blob/main/.claude/commands/docs.md) &nbsp; by &nbsp; [slunsford](https://github.com/slunsford)
生成遵循项目结构的全面文档，使用一致的格式记录 API 和使用模式，以便用户更好地理解。

[`/explain-issue-fix`](https://github.com/hackdays-io/toban-contribution-viewer/blob/main/.claude/commands/explain-issue-fix.md) &nbsp; by &nbsp; [hackdays-io](https://github.com/hackdays-io)
记录 GitHub 问题的解决方案方法，解释技术决策，详细说明克服的挑战，并提供实施上下文以便更好地理解。

[`/update-docs`](https://github.com/Consiliency/Flutter-Structurizr/blob/main/.claude/commands/update-docs.md) &nbsp; by &nbsp; [Consiliency](https://github.com/Consiliency)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
审查当前文档状态，更新实施进度，审查阶段文档，并在整个项目中保持文档一致性。

### CI / 部署

[`/release`](https://github.com/kelp/webdown/blob/main/.claude/commands/release.md) &nbsp; by &nbsp; [kelp](https://github.com/kelp)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
通过更新变更日志、审查 README 更改、评估版本增量以及记录发布更改来管理软件发布，以便更好地进行版本跟踪。

[`/run-ci`](https://github.com/hackdays-io/toban-contribution-viewer/blob/main/.claude/commands/run-ci.md) &nbsp; by &nbsp; [hackdays-io](https://github.com/hackdays-io)
激活虚拟环境，运行与 CI 兼容的检查脚本，迭代修复错误，并确保所有测试在完成前通过。

### 项目和任务管理

[`/create-command`](https://github.com/scopecraft/command/blob/main/.claude/commands/create-command.md) &nbsp; by &nbsp; [scopecraft](https://github.com/scopecraft)
通过分析需求、按类别模板化命令、强制执行命令标准以及创建支持文档来指导 Claude 创建具有正确结构的新自定义命令。

[`/create-jtbd`](https://github.com/taddyorg/inkverse/blob/main/.claude/commands/create-jtbd.md) &nbsp; by &nbsp; [taddyorg](https://github.com/taddyorg)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;AGPL-3.0
创建“待办工作”框架，以结构化格式概述用户需求，重点关注特定用户问题并按工作类别进行组织以进行产品开发。

[`/create-prd`](https://github.com/taddyorg/inkverse/blob/main/.claude/commands/create-prd.md) &nbsp; by &nbsp; [taddyorg](https://github.com/taddyorg)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;AGPL-3.0
生成全面的产品需求文档，概述详细的规格、需求和功能，遵循标准化的文档结构和格式。

[`/create-prp`](https://github.com/Wirasm/claudecode-utils/blob/main/.claude/commands/create-prp.md) &nbsp; by &nbsp; [Wirasm](https://github.com/Wirasm)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
通过阅读 PRP 方法、遵循模板结构、创建全面的需求以及为开发构建产品定义来创建产品需求计划。

[`/project_hello_w_name`](https://github.com/disler/just-prompt/blob/main/.claude/commands/project_hello_w_name.md) &nbsp; by &nbsp; [disler](https://github.com/disler)
创建可自定义的问候组件，带有名称输入，演示参数传递、组件可重用性、状态管理和用户输入处理。

[`/todo`](https://github.com/chrisleyva/todo-slash-command/blob/main/todo.md) &nbsp; by &nbsp; [chrisleyva](https://github.com/chrisleyva)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
一个方便的命令，可在不离开 Claude Code 界面的情况下快速管理项目待办事项，具有截止日期、排序、任务优先级和全面的待办事项列表管理功能。

### 杂项

[`/five`](https://github.com/TuckerTucker/tkr-portfolio/blob/main/.claude/commands/five.md) &nbsp; by &nbsp; [TuckerTucker](https://github.com/TuckerTucker)
应用“五个为什么”方法进行根本原因分析，识别潜在问题，并为复杂问题创建解决方案。

[`/fixing_go_in_graph`](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/fixing_go_in_graph.md) &nbsp; by &nbsp; [Mjvolk3](https://github.com/Mjvolk3)
专注于图形数据库中的基因本体论注释集成，处理多个数据源，解决图形表示问题，并确保正确的数据合并。

[`/mermaid`](https://github.com/GaloyMoney/lana-bank/blob/main/.claude/commands/mermaid.md) &nbsp; by &nbsp; [GaloyMoney](https://github.com/GaloyMoney)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
从 SQL 模式文件生成 Mermaid 图，创建具有表属性的实体关系图，验证图编译，并确保完整的实体覆盖。

[`/review_dcell_model`](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/review_dcell_model.md) &nbsp; by &nbsp; [Mjvolk3](https://github.com/Mjvolk3)
审查旧的 Dcell 实现文件，与较新的 Dango 模型进行比较，记录随时间的变化，并分析重构方法以实现更好的代码组织。

[`/use-stepper`](https://github.com/zuplo/docs/blob/main/.claude/commands/use-stepper.md) &nbsp; by &nbsp; [zuplo](https://github.com/zuplo)
重新格式化文档以使用 React Stepper 组件，转换标题格式，应用正确的缩进，并保持 markdown 与 admonition 格式的兼容性。

<br>

## CLAUDE.md 文件 📂

> **`CLAUDE.md`** 文件是包含重要指南和特定上下文信息或说明的文件，可帮助 Claude Code 更好地了解您的项目和编码标准。

### 特定语言

[`AI IntelliJ 插件`](https://github.com/didalgolab/ai-intellij-plugin/blob/main/CLAUDE.md) &nbsp; by &nbsp; [didalgolab](https://github.com/didalgolab)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
为 IntelliJ 插件开发提供全面的 Gradle 命令，具有特定于平台的编码模式、详细的包结构指南和明确的国际化标准。

[`AWS MCP 服务器`](https://github.com/alexei-led/aws-mcp-server/blob/main/CLAUDE.md) &nbsp; by &nbsp; [alexei-led](https://github.com/alexei-led)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
具有多个 Python 环境设置选项，以及详细的代码风格指南、全面的错误处理建议和 AWS CLI 交互的安全注意事项。

[`DroidconKotlin`](https://github.com/touchlab/DroidconKotlin/blob/main/CLAUDE.md) &nbsp; by &nbsp; [touchlab](https://github.com/touchlab)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
为跨平台 Kotlin 多平台开发提供全面的 Gradle 命令，具有清晰的模块结构和依赖注入的实用指南。

[`EDSL`](https://github.com/expectedparrot/edsl/blob/main/CLAUDE.md) &nbsp; by &nbsp; [expectedparrot](https://github.com/expectedparrot)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
提供详细的构建和测试命令，严格执行代码风格，全面的测试要求，以及使用 Black 和 mypy 的标准化开发工作流程。

[`Giselle`](https://github.com/giselles-ai/giselle/blob/main/CLAUDE.md) &nbsp; by &nbsp; [giselles-ai](https://github.com/giselles-ai)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
提供使用 pnpm 和 Vitest 的详细构建和测试命令，具有严格的代码格式要求和全面的命名约定，以确保代码一致性。

[`HASH`](https://github.com/hashintel/hash/blob/main/CLAUDE.md) &nbsp; by &nbsp; [hashintel](https://github.com/hashintel)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
具有全面的存储库结构分解，重点强调编码标准、详细的 Rust 文档指南和系统的 PR 审查流程。

[`Inkline`](https://github.com/inkline/inkline/blob/main/CLAUDE.md) &nbsp; by &nbsp; [inkline](https://github.com/inkline)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
使用 pnpm 构建开发工作流程，重点关注 TypeScript 和 Vue 3 Composition API、详细的组件创建过程和全面的测试建议。

[`JSBeeb`](https://github.com/mattgodbolt/jsbeeb/blob/main/CLAUDE.md) &nbsp; by &nbsp; [mattgodbolt](https://github.com/mattgodbolt)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;GPL-3.0
提供 JavaScript BBC Micro 模拟器的开发指南，包括构建和测试说明、架构文档和调试工作流程。

[`Lamoom Python`](https://github.com/LamoomAI/lamoom-python/blob/main/CLAUDE.md) &nbsp; by &nbsp; [LamoomAI](https://github.com/LamoomAI)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
作为生产提示工程库的参考，具有 AI 模型负载均衡、API 文档和带示例的使用模式。

[`LangGraphJS`](https://github.com/langchain-ai/langgraphjs/blob/main/CLAUDE.md) &nbsp; by &nbsp; [langchain-ai](https://github.com/langchain-ai)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
提供全面的构建和测试命令，以及详细的 TypeScript 风格指南、分层库架构和使用 yarn 工作区的 monorepo 结构。

[`Metabase`](https://github.com/metabase/metabase/blob/master/CLAUDE.md) &nbsp; by &nbsp; [metabase](https://github.com/metabase)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
详细介绍了在 Clojure/ClojureScript 中进行 REPL 驱动开发的工作流程，重点是增量开发、测试和功能实现的分步方法。

[`SG 汽车趋势后端`](https://github.com/sgcarstrends/backend/blob/main/CLAUDE.md) &nbsp; by &nbsp; [sgcarstrends](https://github.com/sgcarstrends)
为 TypeScript monorepo 项目提供全面的结构，以及用于开发、测试、部署和 AWS/Cloudflare 集成的详细命令。

[`SPy`](https://github.com/spylang/spy/blob/main/CLAUDE.md) &nbsp; by &nbsp; [spylang](https://github.com/spylang)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
强制执行严格的编码约定，具有全面的测试指南、多种代码编译选项和用于有针对性过滤的特定于后端的测试装饰器。

[`TPL`](https://github.com/KarpelesLab/tpl/blob/master/CLAUDE.md) &nbsp; by &nbsp; [KarpelesLab](https://github.com/KarpelesLab)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
详细介绍了 Go 项目约定，以及全面的错误处理建议、表驱动测试方法指南和最新 Go 功能的现代化建议。

### 特定领域

[`AVS Vibe 开发人员指南`](https://github.com/Layr-Labs/avs-vibe-developer-guide/blob/master/CLAUDE.md) &nbsp; by &nbsp; [Layr-Labs](https://github.com/Layr-Labs)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
构建 AI 辅助的 EigenLayer AVS 开发工作流程，具有一致的提示文件命名约定和已建立的区块链概念术语标准。

[`Comm`](https://github.com/CommE2E/comm/blob/master/CLAUDE.md) &nbsp; by &nbsp; [CommE2E](https://github.com/CommE2E)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;BSD-3-Clause
作为 E2E 加密消息传递应用程序的开发参考，具有代码组织架构、安全实施细节和测试程序。

[`课程生成器`](https://github.com/badass-courses/course-builder/blob/main/CLAUDE.md) &nbsp; by &nbsp; [badass-courses](https://github.com/badass-courses)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
通过多样化的技术堆栈集成和使用 Turborepo 的 monorepo 架构，为协作课程创建启用实时多人游戏功能。

[`光标工具`](https://github.com/eastlondoner/cursor-tools/blob/main/CLAUDE.md) &nbsp; by &nbsp; [eastlondoner](https://github.com/eastlondoner)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
创建一个多功能的 AI 命令界面，支持多个提供商和模型，具有灵活的命令选项和通过“Stagehand”功能实现的浏览器自动化。

[`吉他`](https://github.com/soramimi/Guitar/blob/master/CLAUDE.md) &nbsp; by &nbsp; [soramimi](https://github.com/soramimi)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;GPL-2.0
作为 Guitar Git GUI 客户端的开发指南，提供适用于各种平台的构建命令、贡献代码风格指南和项目结构说明。

[`网络编年史`](https://github.com/Fimeg/NetworkChronicles/blob/legacy-v1/CLAUDE.md) &nbsp; by &nbsp; [Fimeg](https://github.com/Fimeg)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
为 AI 驱动的游戏角色提供详细的实施计划，包括 LLM 集成的技术规范、角色指南和服务发现机制。

[`笔记伴侣`](https://github.com/different-ai/note-companion/blob/master/CLAUDE.md) &nbsp; by &nbsp; [different-ai](https://github.com/different-ai)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
为 Obsidian 插件提供详细的样式隔离技术，使用带有自定义前缀的 Tailwind 来防止样式冲突和实用的故障排除步骤。

[`Pareto Mac`](https://github.com/ParetoSecurity/pareto-mac/blob/main/CLAUDE.md) &nbsp; by &nbsp; [ParetoSecurity](https://github.com/ParetoSecurity)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;GPL-3.0
作为 Mac 安全审计工具的开发指南，提供构建说明、贡献指南、测试程序和工作流程文档。

[`SteadyStart`](https://github.com/steadycursor/steadystart/blob/main/CLAUDE.md) &nbsp; by &nbsp; [steadycursor](https://github.com/steadycursor)
关于样式、权限、Claude 的“角色”、通信和 Claude Code 会话文档的清晰直接的说明，以便其他团队成员了解最新情况。

### 项目脚手架和 MCP

[`基本内存`](https://github.com/basicmachines-co/basic-memory/blob/main/CLAUDE.md) &nbsp; by &nbsp; [basicmachines-co](https://github.com/basicmachines-co)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;AGPL-3.0
提出了一个创新的人机协作框架，该框架具有用于双向 LLM-markdown 通信的模型上下文协议和用于复杂项目的灵活知识结构。

[`claude-code-mcp-enhanced`](https://github.com/grahama1970/claude-code-mcp-enhanced/blob/main/CLAUDE.md) &nbsp; by &nbsp; [grahama1970](https://github.com/grahama1970)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
为 Claude 作为编码代理提供详细而有力的说明，并提供测试指南、代码示例和合规性检查。

[`Perplexity MCP`](https://github.com/Family-IT-Guy/perplexity-mcp/blob/main/CLAUDE.md) &nbsp; by &nbsp; [Family-IT-Guy](https://github.com/Family-IT-Guy)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;ISC
提供清晰的分步安装说明，以及多种配置选项、详细的故障排除指南和 MCP 协议架构的简明概述。

<br>

## 官方文档 🏛️

> Anthropic 关于 Claude Code 的一些出色文档和资源的链接

<!--lint disable double-link-->

[`Anthropic 文档`](https://docs.anthropic.com/en/docs/claude-code) &nbsp; by &nbsp; [Anthropic](https://github.com/anthropics)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;&copy;
Claude Code 的官方文档，包括安装说明、使用指南、API 参考、教程、示例以及大量我不会单独列出的信息。与 Claude Code 一样，文档也经常更新。

[`Anthropic 快速入门`](https://github.com/anthropics/anthropic-quickstarts/blob/main/CLAUDE.md) &nbsp; by &nbsp; [Anthropic](https://github.com/anthropics)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
为三个不同的 AI 驱动的演示项目提供全面的开发指南，具有标准化的工作流程、严格的代码风格指南和容器化说明。

[`Claude Code GitHub Actions`](https://github.com/anthropics/claude-code-action/tree/main/examples) &nbsp; by &nbsp; [Anthropic](https://github.com/anthropics)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Claude Code 的官方 GitHub Actions 集成，包含在 CI/CD 管道中自动化 AI 驱动工作流程的示例和文档。

## 贡献 🌻

### 🚀 **[在此处提交新资源！](https://github.com/hesreallyhim/awesome-claude-code/issues/new?template=submit-resource.yml)**

很简单！只需单击上面的链接并填写表格即可。无需 Git 知识——我们的自动化系统会为您处理一切。

**我们特别欢迎：**

- 遵循最佳实践甚至可能在生产中使用的经过验证的有效资源
- 突破 Claude Code 功能界限的创新、创意或实验性工作流程
- 基于 Claude Code 构建的其他库和工具
- Claude Code 在传统“编码助手”背景之外的应用（CI/CD、测试、文档、开发运维等）

有关完整的提交流程和审查过程，请参阅 [CONTRIBUTING.md](CONTRIBUTING.md)。

有关存储库本身的建议，请[提出一般性问题](https://github.com/hesreallyhim/awesome-claude-code/issues/new)。

本项目在[贡献者行为准则](code-of-conduct.md)下发布。参与即表示您同意遵守其条款。

### 关于许可证的说明

因为简单地列出超链接不符合重新分发的条件，所以原始来源的许可证与其包含无关。但是，为了后代和方便起见，我们确实托管了所有许可证允许的资源的副本。因此，请包含有关资源许可证的信息。此外，请注意：_如果您不在 GitHub 存储库中包含许可证，则默认情况下它受完全版权保护，不允许重新分发_。因此，如果您打算创建一个开源项目，那么从众多可用的开源许可证中选择一个是至关重要的。这只是一个提醒，没有许可证，您的项目就不是开源的（它只是源代码可用）——当然，它仍然可以包含在此列表中，但此通知旨在告知读者有关 GitHub 和许可证文件的默认规则。有关更多详细信息，请参阅[此处](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository)。

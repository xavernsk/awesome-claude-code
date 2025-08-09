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

# [素晴らしいクロードコード](https://github.com/hesreallyhim/awesome-claude-code) 🤝 [素晴らしいクロードコードエージェント](https://github.com/hesreallyhim/awesome-claude-code-agents)

<!--lint enable remark-lint:awesome-badge-->

<!--lint disable double-link-->

これは、[クロードコード](https://docs.anthropic.com/en/docs/claude-code)のワークフロー、生産性、雰囲気を向上させるためのスラッシュコマンド、`CLAUDE.md`ファイル、CLIツール、その他のリソースとガイドの厳選されたリストです。

<!--lint enable double-link-->

クロードコードは、ターミナルやIDEでアクセスできる最先端のCLIベースのコーディングアシスタントおよびエージェントです。これは急速に進化しているツールであり、多くの強力な機能を提供し、さまざまな方法で多くの構成を可能にします。ユーザーは現在、ベストプラクティスとワークフローを積極的に開発しています。このリポジトリが、コミュニティが知識を共有し、クロードコードを最大限に活用する方法を理解するのに役立つことを願っています。

### お知らせ

- 2025-07-30 - 簡単な更新：提出フローの調整にまだ取り組んでいます（重複した「おめでとうございます！」の問題を受け取った方には申し訳ありません）。プログラムによる提出ツールで問題が発生した場合は、必要なデータがすべて含まれているものを提出していただければ、承認され次第対応いたします。その他の注意事項：（i）「クロードコードリーダーボード」を設置するのはとてもクールで楽しいと思うので、[ディスカッション](https://github.com/hesreallyhim/awesome-claude-code/discussions/81)でご意見をお聞かせください。（ii）**サブエージェント**についてどうするかまだ検討中であり、同様のリポジトリを立ち上げた他の何人かの方々と連絡を取りました。（iii）新しい提出物が入ってくるたびに更新される小さなセクションを追加しました。

## 新規追加

- [`CC Notify`](https://github.com/dazuiba/CCNotify) by [dazuiba](https://github.com/dazuiba)
- [`tweakcc`](https://github.com/Piebald-AI/tweakcc) by [Piebald-AI](https://github.com/Piebald-AI)
- [`cchooks`](https://github.com/GowayLee/cchooks) by [GowayLee](https://github.com/GowayLee)

<br>

## 目次

▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ワークフローとナレッジガイド](#ワークフローとナレッジガイド-)
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ツール](#ツール-)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[IDE統合](#ide統合)
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[フック](#フック-)
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[スラッシュコマンド](#スラッシュコマンド-)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[バージョン管理とGit](#バージョン管理とgit)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[コード分析とテスト](#コード分析とテスト)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[コンテキストの読み込みとプライミング](#コンテキストの読み込みとプライミング)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ドキュメントと変更履歴](#ドキュメントと変更履歴)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[CI/CD](#cicd)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[プロジェクトとタスク管理](#プロジェクトとタスク管理)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[その他](#その他)
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[CLAUDE.mdファイル](#claudemdファイル-)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[言語固有](#言語固有)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[ドメイン固有](#ドメイン固有)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[プロジェクトの足場とMCP](#プロジェクトの足場とmcp)
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[公式ドキュメント](#公式ドキュメント-)

<br>

## ワークフローとナレッジガイド 🧠

> **ワークフロー**とは、特定のプロジェクトを容易にする、密接に結合されたクロードコードネイティブリソースのセットです。

[`ブログプラットフォームの説明`](https://github.com/cloudartisan/cloudartisan.github.io/tree/main/.claude/commands) &nbsp; by &nbsp; [cloudartisan](https://github.com/cloudartisan)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;CC-BY-SA-4.0
投稿の作成、カテゴリの管理、メディアファイルの処理などのコマンドを含む、ブログプラットフォームを公開および維持するための適切に構造化されたコマンドセットを提供します。

[`ClaudeLog`](https://claudelog.com) &nbsp; by &nbsp; [InventorBlack](https://www.reddit.com/user/inventor_black/)
高度な[メカニクス](https://claudelog.com/mechanics/you-are-the-main-thread/)の詳細な内訳を含む包括的なナレッジベース。[CLAUDE.mdのベストプラクティス](https://claudelog.com/mechanics/claude-md-supremacy)、[プランモード](https://claudelog.com/mechanics/plan-mode)などの実践的なテクニックガイド、[ウルトラシンク](https://claudelog.com/faqs/what-is-ultrathink/)、[サブエージェント](https://claudelog.com/mechanics/task-agent-tools/)、[エージェントファーストデザイン](https://claudelog.com/mechanics/agent-first-design/)、[構成ガイド](https://claudelog.com/configuration)など。

[`コンテキストプライミング`](https://github.com/disler/just-prompt/tree/main/.claude/commands) &nbsp; by &nbsp; [disler](https://github.com/disler)
さまざまなプロジェクトシナリオと開発コンテキストに対応する特殊なコマンドを通じて、包括的なプロジェクトコンテキストでクロードコードをプライミングするための体系的なアプローチを提供します。

[`n8n_agent`](https://github.com/kingler/n8n_agent/tree/main/.claude/commands) &nbsp; by &nbsp; [kingler](https://github.com/kingler)
コード分析、QA、設計、ドキュメント、プロジェクト構造、プロジェクト管理、最適化などに関する驚くほど包括的なコメントセット。

[`プロジェクトのブートストラップとタスク管理`](https://github.com/steadycursor/steadystart/tree/main/.claude/commands) &nbsp; by &nbsp; [steadycursor](https://github.com/steadycursor)
カスタムスラッシュコマンドを作成および編集するためのメタコマンドを含む、新しいプロジェクトをブートストラップおよび管理するための構造化されたコマンドセットを提供します。

[`プロジェクト管理、実装、計画、リリース`](https://github.com/scopecraft/command/tree/main/.claude/commands) &nbsp; by &nbsp; [scopecraft](https://github.com/scopecraft)
SDLCのすべての側面に対応する非常に包括的なコマンドセット。

[`プロジェクトワークフローシステム`](https://github.com/harperreed/dotfiles/tree/master/.claude/commands) &nbsp; by &nbsp; [harperreed](https://github.com/harperreed)
タスク管理、コードレビュー、展開プロセスなど、プロジェクトを管理するための包括的なワークフローシステムを提供するコマンドセット。

[`クロードで実際のコードを出荷する`](https://diwank.space/field-notes-from-shipping-real-code-with-claude) &nbsp; by &nbsp; [Diwank](https://github.com/creatorrr)
CLAUDE.mdファイルやその他の興味深いリソースを含む、クロードコードで製品を出荷するための著者のプロセスを説明する詳細なブログ投稿。

[`Simone`](https://github.com/Helmi/claude-simone) &nbsp; by &nbsp; [Helmi](https://github.com/Helmi)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
コマンドセットだけでなく、プロジェクトの計画と実行を容易にするためのドキュメント、ガイドライン、プロセスのシステムを含む、クロードコードのより広範なプロジェクト管理ワークフロー。

[`スラッシュコマンドメガリスト`](https://github.com/wcygan/dotfiles/tree/d8ab6b9f5a7a81007b7f5fa3025d4f83ce12cc02/claude/commands) &nbsp; by &nbsp; [wcygan](https://github.com/wcygan)
エージェントのオーケストレーション、コードレビュー、プロジェクト管理、セキュリティ、ドキュメント、自己評価など、夢に見るほとんどすべてのスラッシュコマンドのかなり素晴らしいリスト（この記事の執筆時点で88個！）。

<br>

## ツール 🧰

> **ツール**とは、クロードコード上に構築され、スラッシュコマンドや`CLAUDE.md`ファイルよりも多くのコンポーネントで構成されるアプリケーションを指します。

[`CC Usage`](https://github.com/ryoppippi/ccusage) &nbsp; by &nbsp; [ryoppippi](https://github.com/ryoppippi)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
ローカルのクロードコードログの分析に基づいて、クロードコードの使用状況を管理および分析するための便利なCLIツール。コスト情報、トークン消費などに関する優れたダッシュボードを提供します。

[`ccexp`](https://github.com/nyatinte/ccexp) &nbsp; by &nbsp; [nyatinte](https://github.com/nyatinte)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
美しいターミナルUIを備えた、クロードコード構成ファイルとスラッシュコマンドを検出および管理するためのインタラクティブなCLIツール。

[`cclogviewer`](https://github.com/Brads3290/cclogviewer) &nbsp; by &nbsp; [Brad S.](https://github.com/Brads3290)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
クロードコードの`.jsonl`会話ファイルをきれいなHTML UIで表示するための、ささやかだが便利なユーティリティ。

[`クロードコードフロー`](https://github.com/ruvnet/claude-code-flow) &nbsp; by &nbsp; [ruvnet](https://github.com/ruvnet)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
このモードは、コードファーストのオーケストレーションレイヤーとして機能し、クロードが再帰的なエージェントサイクル全体で自律的にコードを記述、編集、テスト、最適化できるようにします。

[`クロードコード使用状況モニター`](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor) &nbsp; by &nbsp; [Maciek-roboblog](https://github.com/Maciek-roboblog)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
クロードコードのトークン使用状況を監視するためのリアルタイムのターミナルベースのツール。ライブのトークン消費、バーンレート、トークン枯渇の予測を表示します。機能には、視覚的なプログレスバー、セッション対応の分析、複数のサブスクリプションプランのサポートが含まれます。

[`クロードコンポーザー`](https://github.com/possibilities/claude-composer) &nbsp; by &nbsp; [Mike Bannister](https://github.com/possibilities)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Unlicense
クロードコードに小さな機能強化を追加するツール。

[`クロードハブ`](https://github.com/claude-did-this/claude-hub) &nbsp; by &nbsp; [Claude Did This](https://github.com/claude-did-this)
クロードコードをGitHubリポジトリに接続するWebhookサービスで、プルリクエストやイシューを通じてAIを活用したコード支援を直接可能にします。この統合により、クロードはリポジトリを分析し、技術的な質問に答え、簡単な@メンションを通じて開発者がコードベースを理解し、改善するのを支援します。

[`クロード分隊`](https://github.com/smtg-ai/claude-squad) &nbsp; by &nbsp; [smtg-ai](https://github.com/smtg-ai)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;AGPL-3.0
クロード分隊は、複数のクロードコード、Codex（およびAiderを含む他のローカルエージェント）を別々のワークスペースで管理するターミナルアプリで、複数のタスクを同時に処理できます。

[`クロードスウォーム`](https://github.com/parruda/claude-swarm) &nbsp; by &nbsp; [parruda](https://github.com/parruda)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
クロードコードエージェントの群れに接続されたクロードコードセッションを起動します。

[`クロードタスクマスター`](https://github.com/eyaltoledano/claude-task-master) &nbsp; by &nbsp; [eyaltoledano](https://github.com/eyaltoledano)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
クロードを使用したAI主導の開発のためのタスク管理システムで、Cursor AIとシームレスに連携するように設計されています。

[`クロードタスクランナー`](https://github.com/grahama1970/claude-task-runner) &nbsp; by &nbsp; [grahama1970](https://github.com/grahama1970)
クロードコードでコンテキストの分離と集中したタスク実行を管理するための特殊なツールで、複雑な多段階のプロジェクトでクロードを使用する際のコンテキスト長の制限とタスクの焦点という重大な課題を解決します。

[`claude-code-tools`](https://github.com/pchalasani/claude-code-tools) &nbsp; by &nbsp; [Prasad Chalasani](https://github.com/pchalasani)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
tmux統合、より優れたセッション管理、セキュリティを強化するフックなど、素晴らしいツールのコレクション - 特にtmuxユーザー向けの、非常によくできたクロードコードエンハンサーのセット。

[`コンテナの使用`](https://github.com/dagger/container-use) &nbsp; by &nbsp; [dagger](https://github.com/dagger)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
コーディングエージェントの開発環境。複数のエージェントが、好みのスタックで安全かつ独立して作業できるようにします。

[`TSK - AIエージェントタスクマネージャーとサンドボックス`](https://github.com/dtormoen/tsk) &nbsp; by &nbsp; [dtormoen](https://github.com/dtormoen)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
サンドボックス化されたDocker環境で実行されているAIエージェントに開発タスクを委任できるRust CLIツール。複数のエージェントが並行して作業し、人間によるレビューのためにgitブランチを返します。

[`tweakcc`](https://github.com/Piebald-AI/tweakcc) &nbsp; by &nbsp; [Piebald-AI](https://github.com/Piebald-AI)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
クロードコードのスタイルをカスタマイズするためのコマンドラインツール。

[`viberank`](https://github.com/sculptdotfun/viberank) &nbsp; by &nbsp; [nikshepsvn](https://github.com/nikshepsvn)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
開発者がクロードコードの使用状況統計に基づいて視覚化、追跡、競争できるようにする、コミュニティ主導のリーダーボードツール。堅牢なデータ分析、GitHub OAuth、データ検証、ユーザーフレンドリーなCLI/Web提出方法を備えています。

### IDE統合

[`クロードコードチャット`](https://marketplace.visualstudio.com/items?itemName=AndrePimenta.claude-code-chat) &nbsp; by &nbsp; [andrepimenta](https://github.com/andrepimenta)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;&copy;
VS Code用のエレガントでユーザーフレンドリーなクロードコードチャットインターフェイス。

[`claude-code-ide.el`](https://github.com/manzaltu/claude-code-ide.el) &nbsp; by &nbsp; [manzaltu](https://github.com/manzaltu)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;GPL-3.0
claude-code-ide.elは、AnthropicのVS Code/IntelliJ拡張機能のように、クロードコードをEmacsと統合します。ediffベースのコード提案を表示し、LSP/flymake/flycheck診断を取得し、バッファコンテキストを追跡します。シンボル参照/定義、プロジェクトメタデータ、tree-sitter ASTクエリ用の拡張可能なMCPツールサポートを追加します。

[`claude-code.el`](https://github.com/stevemolitor/claude-code.el) &nbsp; by &nbsp; [stevemolitor](https://github.com/stevemolitor)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
クロードコードCLI用のEmacsインターフェイス。

[`claude-code.nvim`](https://github.com/greggh/claude-code.nvim) &nbsp; by &nbsp; [greggh](https://github.com/greggh)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
クロードコードAIアシスタントとNeovimのシームレスな統合。

[`クリスタル`](https://github.com/stravu/crystal) &nbsp; by &nbsp; [stravu](https://github.com/stravu)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
クロードコードエージェントをオーケストレーション、監視、操作するための本格的なデスクトップアプリケーション。

<br>

## フック 🪝

> **フック**は、クロードの代理ライフサイクルのさまざまな時点でユーザーがコマンドをアクティブ化し、スクリプトを実行できるようにする、クロードコードのまったく新しいAPIです。

**[実験的]** - このセクションに記載されているリソースは完全には検証されておらず、クロードコードフックの最先端の性質を考えると、期待どおりに機能しない可能性があります。それにもかかわらず、少なくともインスピレーションの源として、そしてこの未知の領域を探求するために、それらを含めたいと思いました。あなたの経験は異なるかもしれません！

[`CC Notify`](https://github.com/dazuiba/CCNotify) &nbsp; by &nbsp; [dazuiba](https://github.com/dazuiba)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
CC Notifyは、クロードコードのデスクトップ通知を提供し、入力の必要性やタスクの完了を警告し、ワンクリックでVS Codeに戻り、タスクの期間を表示します。

[`cchooks`](https://github.com/GowayLee/cchooks) &nbsp; by &nbsp; [GowayLee](https://github.com/GowayLee)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
クリーンなAPIと優れたドキュメントを備えた軽量のPython SDK。フックの作成とコードベースへの統合のプロセスを簡素化し、JSON構成ファイルに対する優れた抽象化を提供します。

[`claude-code-hooks-sdk`](https://github.com/beyondcode/claude-hooks-sdk) &nbsp; by &nbsp; [beyondcode](https://github.com/beyondcode)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
クリーンで流暢なAPIを使用してクロードコードフック応答を構築するためのLaravelに触発されたPHP SDK。このSDKを使用すると、表現力豊かで連鎖可能なインターフェイスを使用して、クロードコードフック用の構造化されたJSON応答を簡単に作成できます。

[`claude-hooks`](https://github.com/johnlindquist/claude-hooks) &nbsp; by &nbsp; [John Lindquist](https://github.com/johnlindquist)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
強力で柔軟なインターフェイスを使用してクロードコードフックを構成およびカスタマイズするためのTypeScriptベースのシステム。

[`Linting、テスト、通知（Go）`](https://github.com/Veraticus/nix-config/tree/main/home-manager/claude-code/hooks) &nbsp; by &nbsp; [Josh Symonds](https://github.com/Veraticus)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
コード品質（リンティング、テスト、通知）を強制するための優れたフックセット。優れた構成設定も備えています。

[`TDDガード`](https://github.com/nizos/tdd-guard) &nbsp; by &nbsp; [Nizar Selander](https://github.com/nizos)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
ファイル操作をリアルタイムで監視し、TDD原則に違反する変更をブロックするフック駆動のシステム。

<br>

## スラッシュコマンド 🔪

### バージョン管理とGit

[`/bug-fix`](https://github.com/danielscholl/mvn-mcp-server/blob/main/.claude/commands/bug-fix.md) &nbsp; by &nbsp; [danielscholl](https://github.com/danielscholl)
最初にGitHubイシューを作成し、次に機能ブランチを作成してソリューションを実装し、マージする前に徹底的にテストすることで、バグ修正を合理化します。

[`/commit`](https://github.com/evmts/tevm-monorepo/blob/main/.claude/commands/commit.md) &nbsp; by &nbsp; [evmts](https://github.com/evmts)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
適切な絵文字を使用して従来のコミット形式でgitコミットを作成し、プロジェクト標準に従い、変更の目的を説明する説明的なメッセージを作成します。

[`/commit-fast`](https://github.com/steadycursor/steadystart/blob/main/.claude/commands/2-commit-fast.md) &nbsp; by &nbsp; [steadycursor](https://github.com/steadycursor)
最初の提案されたメッセージを選択してgitコミットプロセスを自動化し、手動確認をスキップしてクロード共同コントリビューターフッターを削除しながら、一貫したフォーマットで構造化されたコミットを生成します。

[`/create-pr`](https://github.com/toyamarinyon/giselle/blob/main/.claude/commands/create-pr.md) &nbsp; by &nbsp; [toyamarinyon](https://github.com/toyamarinyon)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
新しいブランチの作成、変更のコミット、Biomeによる変更されたファイルのフォーマット、PRの送信など、ワークフロー全体を処理することで、プルリクエストの作成を合理化します。

[`/create-pull-request`](https://github.com/liam-hq/liam/blob/main/.claude/commands/create-pull-request.md) &nbsp; by &nbsp; [liam-hq](https://github.com/liam-hq)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
GitHub CLIを使用したPR作成に関する包括的なガイダンスを提供し、タイトルの規則を強制し、テンプレート構造に従い、ベストプラクティスを含む具体的なコマンド例を提供します。

[`/create-worktrees`](https://github.com/evmts/tevm-monorepo/blob/main/.claude/commands/create-worktrees.md) &nbsp; by &nbsp; [evmts](https://github.com/evmts)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
すべてのオープンPRまたは特定のブランチのgitワークツリーを作成し、スラッシュ付きのブランチを処理し、古いワークツリーをクリーンアップし、開発用のカスタムブランチの作成をサポートします。

[`/fix-github-issue`](https://github.com/jeremymailen/kotlinter-gradle/blob/master/.claude/commands/fix-github-issue.md) &nbsp; by &nbsp; [jeremymailen](https://github.com/jeremymailen)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
GitHub CLIを使用して構造化されたアプローチでGitHubの問題を分析および修正し、問題の詳細を把握し、必要なコード変更を実装し、テストを実行し、適切なコミットメッセージを作成します。

[`/fix-issue`](https://github.com/metabase/metabase/blob/master/.claude/commands/fix-issue.md) &nbsp; by &nbsp; [metabase](https://github.com/metabase)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
問題番号をパラメータとして受け取り、コンテキストを分析し、ソリューションを実装し、適切な統合のために修正をテスト/検証することで、GitHubの問題に対処します。

[`/fix-pr`](https://github.com/metabase/metabase/blob/master/.claude/commands/fix-pr.md) &nbsp; by &nbsp; [metabase](https://github.com/metabase)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
未解決のPRコメントを取得して修正し、自動的にフィードバックを取得し、レビューアの懸念に対処し、対象を絞ったコード改善を行い、レビュープロセスを合理化します。

[`/husky`](https://github.com/evmts/tevm-monorepo/blob/main/.claude/commands/husky.md) &nbsp; by &nbsp; [evmts](https://github.com/evmts)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
プレコミットフックを構成し、コミットメッセージ標準を確立し、リンティングツールと統合し、コミット時のコード品質を確保することで、Husky Gitフックをセットアップおよび管理します。

[`/pr-review`](https://github.com/arkavo-org/opentdf-rs/blob/main/.claude/commands/pr-review.md) &nbsp; by &nbsp; [arkavo-org](https://github.com/arkavo-org)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
メインのコードベースにマージする前に、プルリクエストの変更をレビューしてフィードバックを提供し、問題を確認し、改善を提案します。

[`/update-branch-name`](https://github.com/giselles-ai/giselle/blob/main/.claude/commands/update-branch-name.md) &nbsp; by &nbsp; [giselles-ai](https://github.com/giselles-ai)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
適切なプレフィックスとフォーマットでブランチ名を更新し、命名規則を強制し、セマンティックプレフィックスをサポートし、リモートブランチの更新を管理します。

### コード分析とテスト

[`/check`](https://github.com/rygwdn/slack-tools/blob/main/.claude/commands/check.md) &nbsp; by &nbsp; [rygwdn](https://github.com/rygwdn)
静的分析統合、セキュリティ脆弱性スキャン、コードスタイル強制、詳細なレポート機能を備えた、包括的なコード品質とセキュリティチェックを実行します。

[`/clean`](https://github.com/Graphlet-AI/eridu/blob/main/.claude/commands/clean.md) &nbsp; by &nbsp; [Graphlet-AI](https://github.com/Graphlet-AI)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
ブラックフォーマットの問題を修正し、isortでインポートを整理し、flake8リンティングの問題を解決し、mypyタイプエラーを修正することで、コードのフォーマットと品質の問題に対処します。

[`/code_analysis`](https://github.com/kingler/n8n_agent/blob/main/.claude/commands/code_analysis.md) &nbsp; by &nbsp; [kingler](https://github.com/kingler)
ナレッジグラフの生成、最適化の提案、品質評価など、詳細な調査のための高度なコード分析コマンドのメニューを提供します。

[`/optimize`](https://github.com/to4iki/ai-project-rules/blob/main/.claude/commands/optimize.md) &nbsp; by &nbsp; [to4iki](https://github.com/to4iki)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
コードのパフォーマンスを分析してボトルネックを特定し、アプリケーションのパフォーマンスを向上させるための実装ガイダンスとともに具体的な最適化を提案します。

[`/repro-issue`](https://github.com/rzykov/metabase/blob/master/.claude/commands/repro-issue.md) &nbsp; by &nbsp; [rzykov](https://github.com/rzykov)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
GitHubの問題に対して再現可能なテストケースを作成し、テストが確実に失敗するようにし、開発者向けに明確な再現手順を文書化します。

[`/tdd`](https://github.com/zscott/pane/blob/main/.claude/commands/tdd.md) &nbsp; by &nbsp; [zscott](https://github.com/zscott)
テスト駆動開発の原則を使用して開発をガイドし、赤-緑-リファクタリングの規律を強制し、gitワークフローと統合し、PRの作成を管理します。

### コンテキストの読み込みとプライミング

[`/context-prime`](https://github.com/elizaOS/elizaos.github.io/blob/main/.claude/commands/context-prime.md) &nbsp; by &nbsp; [elizaOS](https://github.com/elizaOS)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
リポジトリ構造を読み込み、開発コンテキストを設定し、プロジェクトの目標を確立し、コラボレーションパラメータを定義することで、クロードに包括的なプロジェクト理解をプライミングします。

[`/initref`](https://github.com/okuvshynov/cubestat/blob/main/.claude/commands/initref.md) &nbsp; by &nbsp; [okuvshynov](https://github.com/okuvshynov)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
標準のドキュメントテンプレート、APIリファレンス設定、ドキュメント規則、プレースホルダーコンテンツ生成を使用して、リファレンスドキュメント構造を初期化します。

[`/load-llms-txt`](https://github.com/ethpandaops/xatu-data/blob/master/.claude/commands/load-llms-txt.md) &nbsp; by &nbsp; [ethpandaops](https://github.com/ethpandaops)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
LLM構成ファイルをコンテキストにロードし、特定の用語、モデル構成をインポートし、AIディスカッションのベースライン用語を確立します。

[`/load_coo_context`](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/load_coo_context.md) &nbsp; by &nbsp; [Mjvolk3](https://github.com/Mjvolk3)
スパース行列演算用の特定のファイルを参照し、変換の使用法を説明し、以前のアプローチと比較し、開発用のデータフォーマットコンテキストを設定します。

[`/load_dango_pipeline`](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/load_dango_pipeline.md) &nbsp; by &nbsp; [Mjvolk3](https://github.com/Mjvolk3)
パイプラインファイルを参照し、作業コンテキストを確立し、関連ドキュメントでパイプライン作業の準備をすることで、モデルトレーニングのコンテキストを設定します。

[`/prime`](https://github.com/yzyydev/AI-Engineering-Structure/blob/main/.claude/commands/prime.md) &nbsp; by &nbsp; [yzyydev](https://github.com/yzyydev)
ディレクトリ構造を表示し、キーファイルを読み取ることで初期プロジェクトコンテキストを設定し、ディレクトリの視覚化とキードキュメントに焦点を当てた標準化されたコンテキストを作成します。

[`/rsi`](https://github.com/ddisisto/si/blob/main/.claude/commands/rsi.md) &nbsp; by &nbsp; [ddisisto](https://github.com/ddisisto)
すべてのコマンドと主要なプロジェクトファイルを読み取って、プロセスを合理化し、コマンドコンテキストをロードし、より良い開発ワークフローを設定することで、AI支援開発を最適化します。

### ドキュメントと変更履歴

[`/add-to-changelog`](https://github.com/berrydev-ai/blockdoc-python/blob/main/.claude/commands/add-to-changelog.md) &nbsp; by &nbsp; [berrydev-ai](https://github.com/berrydev-ai)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
フォーマットの一貫性を維持しながら変更履歴ファイルに新しいエントリを追加し、変更を適切に文書化し、バージョン追跡のために確立されたプロジェクト標準に従います。

[`/create-docs`](https://github.com/jerseycheese/Narraitor/tree/feature/issue-227-ai-suggestions/.claude/commands/analyze-issue.md) &nbsp; by &nbsp; [jerseycheese](https://github.com/jerseycheese)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
コードの構造と目的を分析して、入出力、動作、ユーザーインタラクションフロー、およびエラー処理を伴うエッジケースを詳述する包括的なドキュメントを作成します。

[`/docs`](https://github.com/slunsford/coffee-analytics/blob/main/.claude/commands/docs.md) &nbsp; by &nbsp; [slunsford](https://github.com/slunsford)
プロジェクト構造に従う包括的なドキュメントを生成し、ユーザーの理解を深めるために一貫したフォーマットでAPIと使用パターンを文書化します。

[`/explain-issue-fix`](https://github.com/hackdays-io/toban-contribution-viewer/blob/main/.claude/commands/explain-issue-fix.md) &nbsp; by &nbsp; [hackdays-io](https://github.com/hackdays-io)
GitHubの問題に対する解決策のアプローチを文書化し、技術的な決定を説明し、克服した課題を詳述し、より良い理解のために実装のコンテキストを提供します。

[`/update-docs`](https://github.com/Consiliency/Flutter-Structurizr/blob/main/.claude/commands/update-docs.md) &nbsp; by &nbsp; [Consiliency](https://github.com/Consiliency)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
現在のドキュメントのステータスを確認し、実装の進捗状況を更新し、フェーズドキュメントを確認し、プロジェクト全体でドキュメントの一貫性を維持します。

### CI/CD

[`/release`](https://github.com/kelp/webdown/blob/main/.claude/commands/release.md) &nbsp; by &nbsp; [kelp](https://github.com/kelp)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
変更履歴の更新、READMEの変更の確認、バージョンの増分の評価、およびより良いバージョン追跡のためのリリース変更の文書化によって、ソフトウェアリリースを管理します。

[`/run-ci`](https://github.com/hackdays-io/toban-contribution-viewer/blob/main/.claude/commands/run-ci.md) &nbsp; by &nbsp; [hackdays-io](https://github.com/hackdays-io)
仮想環境をアクティブにし、CI互換のチェックスクリプトを実行し、エラーを繰り返し修正し、完了前にすべてのテストが合格することを確認します。

### プロジェクトとタスク管理

[`/create-command`](https://github.com/scopecraft/command/blob/main/.claude/commands/create-command.md) &nbsp; by &nbsp; [scopecraft](https://github.com/scopecraft)
要件を分析し、カテゴリ別にコマンドをテンプレート化し、コマンド標準を強制し、サポートドキュメントを作成することで、適切な構造を持つ新しいカスタムコマンドの作成をクロードにガイドします。

[`/create-jtbd`](https://github.com/taddyorg/inkverse/blob/main/.claude/commands/create-jtbd.md) &nbsp; by &nbsp; [taddyorg](https://github.com/taddyorg)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;AGPL-3.0
構造化された形式でユーザーのニーズを概説するジョブツービードンフレームワークを作成し、特定のユーザーの問題に焦点を当て、製品開発のためにジョブカテゴリ別に整理します。

[`/create-prd`](https://github.com/taddyorg/inkverse/blob/main/.claude/commands/create-prd.md) &nbsp; by &nbsp; [taddyorg](https://github.com/taddyorg)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;AGPL-3.0
標準化されたドキュメント構造と形式に従って、詳細な仕様、要件、機能を概説する包括的な製品要件ドキュメントを生成します。

[`/create-prp`](https://github.com/Wirasm/claudecode-utils/blob/main/.claude/commands/create-prp.md) &nbsp; by &nbsp; [Wirasm](https://github.com/Wirasm)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
PRP方法論を読み、テンプレート構造に従い、包括的な要件を作成し、開発のための製品定義を構造化することで、製品要件計画を作成します。

[`/project_hello_w_name`](https://github.com/disler/just-prompt/blob/main/.claude/commands/project_hello_w_name.md) &nbsp; by &nbsp; [disler](https://github.com/disler)
名前入力を伴うカスタマイズ可能な挨拶コンポーネントを作成し、引数の受け渡し、コンポーネントの再利用性、状態管理、ユーザー入力の処理を示します。

[`/todo`](https://github.com/chrisleyva/todo-slash-command/blob/main/todo.md) &nbsp; by &nbsp; [chrisleyva](https://github.com/chrisleyva)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
クロードコードインターフェイスを離れることなく、期日、並べ替え、タスクの優先順位付け、および包括的なToDoリスト管理を備えた、プロジェクトのToDo項目をすばやく管理するための便利なコマンド。

### その他

[`/five`](https://github.com/TuckerTucker/tkr-portfolio/blob/main/.claude/commands/five.md) &nbsp; by &nbsp; [TuckerTucker](https://github.com/TuckerTucker)
「5つのなぜ」方法論を適用して根本原因分析を実行し、根本的な問題を特定し、複雑な問題に対する解決策アプローチを作成します。

[`/fixing_go_in_graph`](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/fixing_go_in_graph.md) &nbsp; by &nbsp; [Mjvolk3](https://github.com/Mjvolk3)
グラフデータベースにおける遺伝子オントロジーアノテーションの統合に焦点を当て、複数のデータソースを処理し、グラフ表現の問題に対処し、正しいデータ組み込みを保証します。

[`/mermaid`](https://github.com/GaloyMoney/lana-bank/blob/main/.claude/commands/mermaid.md) &nbsp; by &nbsp; [GaloyMoney](https://github.com/GaloyMoney)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
SQLスキーマファイルからマーメイド図を生成し、テーブルプロパティを持つエンティティ関係図を作成し、図のコンパイルを検証し、完全なエンティティカバレッジを保証します。

[`/review_dcell_model`](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/review_dcell_model.md) &nbsp; by &nbsp; [Mjvolk3](https://github.com/Mjvolk3)
古いDcell実装ファイルをレビューし、新しいDangoモデルと比較し、経時的な変更を記録し、より良いコード編成のためのリファクタリングアプローチを分析します。

[`/use-stepper`](https://github.com/zuplo/docs/blob/main/.claude/commands/use-stepper.md) &nbsp; by &nbsp; [zuplo](https://github.com/zuplo)
React Stepperコンポーネントを使用するようにドキュメントを再フォーマットし、見出しのフォーマットを変換し、適切なインデントを適用し、admonitionフォーマットとのマークダウン互換性を維持します。

<br>

## CLAUDE.mdファイル 📂

> **`CLAUDE.md`**ファイルは、クロードコードがプロジェクトとコーディング標準をよりよく理解するのに役立つ重要なガイドラインとコンテキスト固有の情報または指示を含むファイルです。

### 言語固有

[`AI IntelliJプラグイン`](https://github.com/didalgolab/ai-intellij-plugin/blob/main/CLAUDE.md) &nbsp; by &nbsp; [didalgolab](https://github.com/didalgolab)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
プラットフォーム固有のコーディングパターン、詳細なパッケージ構造ガイドライン、明確な国際化標準を備えたIntelliJプラグイン開発のための包括的なGradleコマンドを提供します。

[`AWS MCPサーバー`](https://github.com/alexei-led/aws-mcp-server/blob/main/CLAUDE.md) &nbsp; by &nbsp; [alexei-led](https://github.com/alexei-led)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
詳細なコードスタイルガイドライン、包括的なエラー処理の推奨事項、AWS CLIインタラクションのセキュリティに関する考慮事項を備えた複数のPython環境設定オプションを備えています。

[`DroidconKotlin`](https://github.com/touchlab/DroidconKotlin/blob/main/CLAUDE.md) &nbsp; by &nbsp; [touchlab](https://github.com/touchlab)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
明確なモジュール構造と依存性注入に関する実践的なガイダンスを備えた、クロスプラットフォームのKotlin Multiplatform開発のための包括的なGradleコマンドを提供します。

[`EDSL`](https://github.com/expectedparrot/edsl/blob/main/CLAUDE.md) &nbsp; by &nbsp; [expectedparrot](https://github.com/expectedparrot)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
厳格なコードスタイル強制、包括的なテスト要件、およびBlackとmypyを使用した標準化された開発ワークフローを備えた詳細なビルドおよびテストコマンドを提供します。

[`Giselle`](https://github.com/giselles-ai/giselle/blob/main/CLAUDE.md) &nbsp; by &nbsp; [giselles-ai](https://github.com/giselles-ai)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
pnpmとVitestを使用した詳細なビルドおよびテストコマンドを提供し、厳格なコードフォーマット要件とコードの一貫性のための包括的な命名規則を備えています。

[`HASH`](https://github.com/hashintel/hash/blob/main/CLAUDE.md) &nbsp; by &nbsp; [hashintel](https://github.com/hashintel)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
コーディング標準に重点を置いた包括的なリポジトリ構造の内訳、詳細なRustドキュメントガイドライン、および体系的なPRレビュープロセスを備えています。

[`Inkline`](https://github.com/inkline/inkline/blob/main/CLAUDE.md) &nbsp; by &nbsp; [inkline](https://github.com/inkline)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
TypeScriptとVue 3 Composition APIに重点を置いたpnpmを使用した開発ワークフロー、詳細なコンポーネント作成プロセス、および包括的なテストの推奨事項を構造化します。

[`JSBeeb`](https://github.com/mattgodbolt/jsbeeb/blob/main/CLAUDE.md) &nbsp; by &nbsp; [mattgodbolt](https://github.com/mattgodbolt)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;GPL-3.0
ビルドとテストの手順、アーキテクチャのドキュメント、デバッグのワークフローを備えたJavaScript BBC Microエミュレータの開発ガイドを提供します。

[`Lamoom Python`](https://github.com/LamoomAI/lamoom-python/blob/main/CLAUDE.md) &nbsp; by &nbsp; [LamoomAI](https://github.com/LamoomAI)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
AIモデルの負荷分散、APIドキュメント、および例を含む使用パターンを備えた、本番プロンプトエンジニアリングライブラリのリファレンスとして機能します。

[`LangGraphJS`](https://github.com/langchain-ai/langgraphjs/blob/main/CLAUDE.md) &nbsp; by &nbsp; [langchain-ai](https://github.com/langchain-ai)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
詳細なTypeScriptスタイルガイドライン、階層化されたライブラリアーキテクチャ、およびyarnワークスペースを使用したモノレポ構造を備えた包括的なビルドおよびテストコマンドを提供します。

[`Metabase`](https://github.com/metabase/metabase/blob/master/CLAUDE.md) &nbsp; by &nbsp; [metabase](https://github.com/metabase)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
Clojure/ClojureScriptでのREPL駆動開発のワークフローを詳述し、インクリメンタル開発、テスト、および機能実装のための段階的なアプローチに重点を置いています。

[`SG Cars Trends Backend`](https://github.com/sgcarstrends/backend/blob/main/CLAUDE.md) &nbsp; by &nbsp; [sgcarstrends](https://github.com/sgcarstrends)
開発、テスト、展開、およびAWS/Cloudflare統合のための詳細なコマンドを備えたTypeScriptモノレポプロジェクトの包括的な構造を提供します。

[`SPy`](https://github.com/spylang/spy/blob/main/CLAUDE.md) &nbsp; by &nbsp; [spylang](https://github.com/spylang)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
包括的なテストガイドライン、複数のコードコンパイルオプション、および対象を絞ったフィルタリングのためのバックエンド固有のテストデコレータを使用して、厳格なコーディング規則を強制します。

[`TPL`](https://github.com/KarpelesLab/tpl/blob/master/CLAUDE.md) &nbsp; by &nbsp; [KarpelesLab](https://github.com/KarpelesLab)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
包括的なエラー処理の推奨事項、テーブル駆動のテストアプローチガイドライン、および最新のGo機能の近代化の提案を含むGoプロジェクトの規則を詳述します。

### ドメイン固有

[`AVS Vibe開発者ガイド`](https://github.com/Layr-Labs/avs-vibe-developer-guide/blob/master/CLAUDE.md) &nbsp; by &nbsp; [Layr-Labs](https://github.com/Layr-Labs)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
プロンプトファイルの一貫した命名規則とブロックチェーンの概念に関する確立された用語標準を使用して、AI支援のEigenLayer AVS開発ワークフローを構造化します。

[`Comm`](https://github.com/CommE2E/comm/blob/master/CLAUDE.md) &nbsp; by &nbsp; [CommE2E](https://github.com/CommE2E)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;BSD-3-Clause
コード編成アーキテクチャ、セキュリティ実装の詳細、およびテスト手順を備えたE2E暗号化メッセージングアプリケーションの開発リファレンスとして機能します。

[`コースビルダー`](https://github.com/badass-courses/course-builder/blob/main/CLAUDE.md) &nbsp; by &nbsp; [badass-courses](https://github.com/badass-courses)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
多様な技術スタックの統合とTurborepoを使用したモノレポアーキテクチャにより、共同コース作成のためのリアルタイムマルチプレイヤー機能を有効にします。

[`カーソルツール`](https://github.com/eastlondoner/cursor-tools/blob/main/CLAUDE.md) &nbsp; by &nbsp; [eastlondoner](https://github.com/eastlondoner)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
柔軟なコマンドオプションと「ステージハンド」機能によるブラウザ自動化を備えた、複数のプロバイダーとモデルをサポートする汎用性の高いAIコマンドインターフェイスを作成します。

[`ギター`](https://github.com/soramimi/Guitar/blob/master/CLAUDE.md) &nbsp; by &nbsp; [soramimi](https://github.com/soramimi)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;GPL-2.0
さまざまなプラットフォーム用のビルドコマンド、貢献のためのコードスタイルガイドライン、およびプロジェクト構造の説明を備えたGuitar Git GUIクライアントの開発ガイドとして機能します。

[`ネットワーククロニクル`](https://github.com/Fimeg/NetworkChronicles/blob/legacy-v1/CLAUDE.md) &nbsp; by &nbsp; [Fimeg](https://github.com/Fimeg)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
LLM統合の技術仕様、キャラクターガイドライン、およびサービス検出メカニズムを備えた、AI駆動のゲームキャラクターの詳細な実装計画を提示します。

[`ノートコンパニオン`](https://github.com/different-ai/note-companion/blob/master/CLAUDE.md) &nbsp; by &nbsp; [different-ai](https://github.com/different-ai)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
カスタムプレフィックスを使用してスタイルの競合を防ぐためのTailwindを使用したObsidianプラグインの詳細なスタイル分離手法と、実践的なトラブルシューティング手順を提供します。

[`Pareto Mac`](https://github.com/ParetoSecurity/pareto-mac/blob/main/CLAUDE.md) &nbsp; by &nbsp; [ParetoSecurity](https://github.com/ParetoSecurity)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;GPL-3.0
ビルド手順、貢献ガイドライン、テスト手順、およびワークフロードキュメントを備えたMacセキュリティ監査ツールの開発ガイドとして機能します。

[`SteadyStart`](https://github.com/steadycursor/steadystart/blob/main/CLAUDE.md) &nbsp; by &nbsp; [steadycursor](https://github.com/steadycursor)
スタイル、権限、クロードの「役割」、コミュニケーション、および他のチームメンバーが最新情報を入手できるようにするためのクロードコードセッションのドキュメントに関する明確で直接的な指示。

### プロジェクトの足場とMCP

[`基本メモリ`](https://github.com/basicmachines-co/basic-memory/blob/main/CLAUDE.md) &nbsp; by &nbsp; [basicmachines-co](https://github.com/basicmachines-co)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;AGPL-3.0
双方向LLM-markdown通信用のモデルコンテキストプロトコルと、複雑なプロジェクト用の柔軟な知識構造を備えた、革新的なAI-人間コラボレーションフレームワークを提示します。

[`claude-code-mcp-enhanced`](https://github.com/grahama1970/claude-code-mcp-enhanced/blob/main/CLAUDE.md) &nbsp; by &nbsp; [grahama1970](https://github.com/grahama1970)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
テストガイダンス、コード例、およびコンプライアンスチェックとともに、クロードがコーディングエージェントとして従うべき詳細で強調的な指示を提供します。

[`Perplexity MCP`](https://github.com/Family-IT-Guy/perplexity-mcp/blob/main/CLAUDE.md) &nbsp; by &nbsp; [Family-IT-Guy](https://github.com/Family-IT-Guy)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;ISC
複数の構成オプション、詳細なトラブルシューティングガイダンス、およびMCPプロトコルの簡潔なアーキテクチャ概要を備えた、明確なステップバイステップのインストール手順を提供します。

<br>

## 公式ドキュメント 🏛️

> クロードコードに関するAnthropicの素晴らしいドキュメントとリソースへのリンク

<!--lint disable double-link-->

[`Anthropicドキュメント`](https://docs.anthropic.com/en/docs/claude-code) &nbsp; by &nbsp; [Anthropic](https://github.com/anthropics)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;&copy;
インストール手順、使用ガイドライン、APIリファレンス、チュートリアル、例、個別にリストしない多くの情報を含む、クロードコードの公式ドキュメント。クロードコードと同様に、ドキュメントは頻繁に更新されます。

[`Anthropicクイックスタート`](https://github.com/anthropics/anthropic-quickstarts/blob/main/CLAUDE.md) &nbsp; by &nbsp; [Anthropic](https://github.com/anthropics)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
標準化されたワークフロー、厳格なコードスタイルガイドライン、およびコンテナ化手順を備えた、3つの異なるAI搭載デモプロジェクトの包括的な開発ガイドを提供します。

[`クロードコードGitHubアクション`](https://github.com/anthropics/claude-code-action/tree/main/examples) &nbsp; by &nbsp; [Anthropic](https://github.com/anthropics)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
CI/CDパイプラインでAIを活用したワークフローを自動化するための例とドキュメントを備えた、クロードコードの公式GitHubアクション統合。

## 貢献 🌻

### 🚀 **[ここで新しいリソースを送信してください！](https://github.com/hesreallyhim/awesome-claude-code/issues/new?template=submit-resource.yml)**

簡単です！上のリンクをクリックしてフォームに記入するだけです。Gitの知識は必要ありません。当社の自動化システムがすべてを処理します。

**特に歓迎します：**

- ベストプラクティスに従い、本番環境で使用されている可能性のある、実績のある効果的なリソース
- クロードコードの機能の限界を押し広げる、革新的、創造的、または実験的なワークフロー
- クロードコード上に構築された追加のライブラリとツール
- 従来の「コーディングアシスタント」のコンテキスト外でのクロードコードのアプリケーション（CI/CD、テスト、ドキュメント、開発運用など）

完全な提出ガイドとレビュープロセスについては、[CONTRIBUTING.md](CONTRIBUTING.md)を参照してください。

リポジトリ自体に関する提案については、[一般的な問題を開いてください](https://github.com/hesreallyhim/awesome-claude-code/issues/new)。

このプロジェクトは、[貢献者行動規範](code-of-conduct.md)とともにリリースされています。参加することにより、その条件に従うことに同意したことになります。

### ライセンスに関する注意

ハイパーリンクをリストするだけでは再配布とは見なされないため、元のソースのライセンスはその包含とは無関係です。ただし、後世のためと便宜のために、ライセンスが許可するすべてのリソースのコピーをホストしています。したがって、リソースのライセンスに関する情報を含めてください。さらに、注意してください：_GitHubリポジトリにライセンスを含めない場合、デフォルトで完全に著作権で保護されており、再配布は許可されていません_。したがって、オープンソースプロジェクトを作成する予定がある場合は、利用可能な多くのオープンソースライセンスから1つを選択することが重要です。これは、ライセンスがないとプロジェクトがオープンソースではない（単にソースコードが利用可能であるだけ）ことを思い出させるためのものです。もちろん、このリストに含めることはできますが、この通知は、読者にGitHubとライセンスファイルに関するデフォルトのルールを知らせるためのものです。詳細については、[こちら](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository)を参照してください。

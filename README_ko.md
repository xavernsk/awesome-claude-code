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

# [멋진 클로드 코드](https://github.com/hesreallyhim/awesome-claude-code) 🤝 [멋진 클로드 코드 에이전트](https://github.com/hesreallyhim/awesome-claude-code-agents)

<!--lint enable remark-lint:awesome-badge-->

<!--lint disable double-link-->

이것은 [클로드 코드](https://docs.anthropic.com/en/docs/claude-code) 워크플로, 생산성 및 분위기를 향상시키기 위한 슬래시 명령, `CLAUDE.md` 파일, CLI 도구 및 기타 리소스와 가이드의 선별된 목록입니다.

<!--lint enable double-link-->

클로드 코드는 터미널이나 IDE에서 액세스할 수 있는 최첨단 CLI 기반 코딩 도우미 및 에이전트입니다. 빠르게 발전하는 도구로서 다양한 강력한 기능을 제공하며 다양한 방식으로 많은 구성을 허용합니다. 사용자는 현재 모범 사례와 워크플로를 적극적으로 개발하고 있습니다. 이 저장소가 커뮤니티가 지식을 공유하고 클로드 코드를 최대한 활용하는 방법을 이해하는 데 도움이 되기를 바랍니다.

### 공지

- 2025-07-30 - 빠른 업데이트: 제출 흐름을 해결하기 위해 여전히 노력하고 있습니다(중복된 "축하합니다!" 문제를 받은 모든 분들께 죄송합니다). 프로그래밍 방식 제출 도구와 씨름하게 되면 필요한 모든 데이터가 포함된 내용을 제출해 주시면 승인되는 대로 처리하겠습니다. 기타 참고 사항: (i) "클로드 코드 리더보드"를 설정하면 정말 멋지고 재미있을 것 같으니 [토론](https://github.com/hesreallyhim/awesome-claude-code/discussions/81)에서 의견을 자유롭게 공유해 주세요. (ii) **하위 에이전트**에 대해 어떻게 해야 할지 아직 고민 중이며, 비슷한 저장소를 시작한 다른 분들께 연락을 드렸습니다. (iii) 새로운 제출물이 들어오는 대로 업데이트될 작은 섹션을 추가했습니다.

## 새로운 추가 사항

- [`CC Notify`](https://github.com/dazuiba/CCNotify) by [dazuiba](https://github.com/dazuiba)
- [`tweakcc`](https://github.com/Piebald-AI/tweakcc) by [Piebald-AI](https://github.com/Piebald-AI)
- [`cchooks`](https://github.com/GowayLee/cchooks) by [GowayLee](https://github.com/GowayLee)

<br>

## 목차

▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[워크플로 및 지식 가이드](#워크플로-및-지식-가이드-)
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[도구](#도구-)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[IDE 통합](#ide-통합)
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[후크](#후크-)
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[슬래시 명령](#슬래시-명령-)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[버전 관리 및 Git](#버전-관리-및-git)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[코드 분석 및 테스트](#코드-분석-및-테스트)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[컨텍스트 로딩 및 프라이밍](#컨텍스트-로딩-및-프라이밍)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[문서 및 변경 로그](#문서-및-변경-로그)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[CI/CD](#cicd)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[프로젝트 및 작업 관리](#프로젝트-및-작업-관리)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[기타](#기타)
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[CLAUDE.md 파일](#claudemd-파일-)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[언어별](#언어별)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[도메인별](#도메인별)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[프로젝트 스캐폴딩 및 MCP](#프로젝트-스캐폴딩-및-mcp)
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[공식 문서](#공식-문서-)

<br>

## 워크플로 및 지식 가이드 🧠

> **워크플로**는 특정 프로젝트를 용이하게 하는 긴밀하게 결합된 클로드 코드 네이티브 리소스 집합입니다.

[`블로깅 플랫폼 지침`](https://github.com/cloudartisan/cloudartisan.github.io/tree/main/.claude/commands) &nbsp; by &nbsp; [cloudartisan](https://github.com/cloudartisan)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;CC-BY-SA-4.0
게시물 작성, 카테고리 관리 및 미디어 파일 처리를 위한 명령을 포함하여 블로깅 플랫폼을 게시하고 유지 관리하기 위한 잘 구조화된 명령 집합을 제공합니다.

[`ClaudeLog`](https://claudelog.com) &nbsp; by &nbsp; [InventorBlack](https://www.reddit.com/user/inventor_black/)
고급 [메커니즘](https://claudelog.com/mechanics/you-are-the-main-thread/)에 대한 자세한 분석을 제공하는 포괄적인 지식 기반, [CLAUDE.md 모범 사례](https://claudelog.com/mechanics/claude-md-supremacy), [계획 모드](https://claudelog.com/mechanics/plan-mode)와 같은 실용적인 기술 가이드, [울트라싱크](https://claudelog.com/faqs/what-is-ultrathink/), [하위 에이전트](https://claudelog.com/mechanics/task-agent-tools/), [에이전트 우선 설계](https://claudelog.com/mechanics/agent-first-design/) 및 [구성 가이드](https://claudelog.com/configuration)를 포함합니다.

[`컨텍스트 프라이밍`](https://github.com/disler/just-prompt/tree/main/.claude/commands) &nbsp; by &nbsp; [disler](https://github.com/disler)
다양한 프로젝트 시나리오 및 개발 컨텍스트에 대한 특수 명령을 통해 포괄적인 프로젝트 컨텍스트로 클로드 코드를 프라이밍하는 체계적인 접근 방식을 제공합니다.

[`n8n_agent`](https://github.com/kingler/n8n_agent/tree/main/.claude/commands) &nbsp; by &nbsp; [kingler](https://github.com/kingler)
코드 분석, QA, 설계, 문서, 프로젝트 구조, 프로젝트 관리, 최적화 등에 대한 놀랍도록 포괄적인 주석 집합입니다.

[`프로젝트 부트스트래핑 및 작업 관리`](https://github.com/steadycursor/steadystart/tree/main/.claude/commands) &nbsp; by &nbsp; [steadycursor](https://github.com/steadycursor)
사용자 지정 슬래시 명령을 만들고 편집하기 위한 메타 명령을 포함하여 새 프로젝트를 부트스트래핑하고 관리하기 위한 구조화된 명령 집합을 제공합니다.

[`프로젝트 관리, 구현, 계획 및 릴리스`](https://github.com/scopecraft/command/tree/main/.claude/commands) &nbsp; by &nbsp; [scopecraft](https://github.com/scopecraft)
SDLC의 모든 측면에 대한 정말 포괄적인 명령 집합입니다.

[`프로젝트 워크플로 시스템`](https://github.com/harperreed/dotfiles/tree/master/.claude/commands) &nbsp; by &nbsp; [harperreed](https://github.com/harperreed)
작업 관리, 코드 검토 및 배포 프로세스를 포함하여 프로젝트를 관리하기 위한 포괄적인 워크플로 시스템을 제공하는 명령 집합입니다.

[`클로드로 실제 코드 배송하기`](https://diwank.space/field-notes-from-shipping-real-code-with-claude) &nbsp; by &nbsp; [Diwank](https://github.com/creatorrr)
CLAUDE.md 파일 및 기타 흥미로운 리소스를 포함하여 클로드 코드로 제품을 배송하는 저자의 프로세스를 설명하는 자세한 블로그 게시물입니다.

[`Simone`](https://github.com/Helmi/claude-simone) &nbsp; by &nbsp; [Helmi](https://github.com/Helmi)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
명령 집합뿐만 아니라 프로젝트 계획 및 실행을 용이하게 하는 문서, 지침 및 프로세스 시스템을 포함하는 클로드 코드에 대한 더 광범위한 프로젝트 관리 워크플로입니다.

[`슬래시 명령 메가리스트`](https://github.com/wcygan/dotfiles/tree/d8ab6b9f5a7a81007b7f5fa3025d4f83ce12cc02/claude/commands) &nbsp; by &nbsp; [wcygan](https://github.com/wcygan)
에이전트 오케스트레이션, 코드 검토, 프로젝트 관리, 보안, 문서, 자체 평가 등 상상할 수 있는 거의 모든 것을 망라하는 매우 놀라운 슬래시 명령 목록(이 게시물 작성 시 88개!)입니다.

<br>

## 도구 🧰

> **도구**는 클로드 코드 위에 구축되고 슬래시 명령 및 `CLAUDE.md` 파일보다 더 많은 구성 요소로 구성된 응용 프로그램을 나타냅니다.

[`CC Usage`](https://github.com/ryoppippi/ccusage) &nbsp; by &nbsp; [ryoppippi](https://github.com/ryoppippi)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
로컬 클로드 코드 로그 분석을 기반으로 클로드 코드 사용량을 관리하고 분석하기 위한 편리한 CLI 도구입니다. 비용 정보, 토큰 소비 등에 관한 멋진 대시보드를 제공합니다.

[`ccexp`](https://github.com/nyatinte/ccexp) &nbsp; by &nbsp; [nyatinte](https://github.com/nyatinte)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
아름다운 터미널 UI로 클로드 코드 구성 파일 및 슬래시 명령을 검색하고 관리하기 위한 대화형 CLI 도구입니다.

[`cclogviewer`](https://github.com/Brads3290/cclogviewer) &nbsp; by &nbsp; [Brad S.](https://github.com/Brads3290)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
클로드 코드 `.jsonl` 대화 파일을 예쁜 HTML UI로 보기 위한 소박하지만 편리한 유틸리티입니다.

[`클로드 코드 흐름`](https://github.com/ruvnet/claude-code-flow) &nbsp; by &nbsp; [ruvnet](https://github.com/ruvnet)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
이 모드는 코드 우선 오케스트레이션 계층 역할을 하여 클로드가 재귀 에이전트 주기를 통해 자율적으로 코드를 작성, 편집, 테스트 및 최적화할 수 있도록 합니다.

[`클로드 코드 사용량 모니터`](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor) &nbsp; by &nbsp; [Maciek-roboblog](https://github.com/Maciek-roboblog)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
클로드 코드 토큰 사용량을 모니터링하기 위한 실시간 터미널 기반 도구입니다. 실시간 토큰 소비, 소진율 및 토큰 고갈 예측을 보여줍니다. 기능에는 시각적 진행률 표시줄, 세션 인식 분석 및 여러 구독 계획 지원이 포함됩니다.

[`클로드 작곡가`](https://github.com/possibilities/claude-composer) &nbsp; by &nbsp; [Mike Bannister](https://github.com/possibilities)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Unlicense
클로드 코드에 작은 향상 기능을 추가하는 도구입니다.

[`클로드 허브`](https://github.com/claude-did-this/claude-hub) &nbsp; by &nbsp; [Claude Did This](https://github.com/claude-did-this)
클로드 코드를 GitHub 저장소에 연결하는 웹훅 서비스로, 풀 리퀘스트 및 문제를 통해 직접 AI 기반 코드 지원을 가능하게 합니다. 이 통합을 통해 클로드는 저장소를 분석하고 기술적인 질문에 답하며 개발자가 간단한 @멘션을 통해 코드베이스를 이해하고 개선하도록 도울 수 있습니다.

[`클로드 스쿼드`](https://github.com/smtg-ai/claude-squad) &nbsp; by &nbsp; [smtg-ai](https://github.com/smtg-ai)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;AGPL-3.0
클로드 스쿼드는 여러 클로드 코드, 코덱스(및 에이더를 포함한 기타 로컬 에이전트)를 별도의 작업 공간에서 관리하는 터미널 앱으로, 여러 작업을 동시에 수행할 수 있습니다.

[`클로드 스웜`](https://github.com/parruda/claude-swarm) &nbsp; by &nbsp; [parruda](https://github.com/parruda)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
클로드 코드 에이전트 무리에 연결된 클로드 코드 세션을 시작합니다.

[`클로드 작업 마스터`](https://github.com/eyaltoledano/claude-task-master) &nbsp; by &nbsp; [eyaltoledano](https://github.com/eyaltoledano)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
클로드를 사용한 AI 기반 개발을 위한 작업 관리 시스템으로, 커서 AI와 원활하게 작동하도록 설계되었습니다.

[`클로드 작업 실행기`](https://github.com/grahama1970/claude-task-runner) &nbsp; by &nbsp; [grahama1970](https://github.com/grahama1970)
클로드 코드를 사용하여 컨텍스트 격리 및 집중적인 작업 실행을 관리하기 위한 특수 도구로, 복잡한 다단계 프로젝트에서 클로드를 사용할 때 컨텍스트 길이 제한 및 작업 집중의 중요한 문제를 해결합니다.

[`claude-code-tools`](https://github.com/pchalasani/claude-code-tools) &nbsp; by &nbsp; [Prasad Chalasani](https://github.com/pchalasani)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
tmux 통합, 더 나은 세션 관리, 보안을 강화하는 후크 등 멋진 도구 모음 - 특히 tmux 사용자를 위한 매우 잘 만들어진 클로드 코드 향상 기능 세트입니다.

[`컨테이너 사용`](https://github.com/dagger/container-use) &nbsp; by &nbsp; [dagger](https://github.com/dagger)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
코딩 에이전트를 위한 개발 환경입니다. 여러 에이전트가 선호하는 스택으로 안전하고 독립적으로 작업할 수 있도록 합니다.

[`TSK - AI 에이전트 작업 관리자 및 샌드박스`](https://github.com/dtormoen/tsk) &nbsp; by &nbsp; [dtormoen](https://github.com/dtormoen)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
샌드박스된 Docker 환경에서 실행되는 AI 에이전트에게 개발 작업을 위임할 수 있는 Rust CLI 도구입니다. 여러 에이전트가 병렬로 작업하여 인간 검토를 위해 git 브랜치를 반환합니다.

[`tweakcc`](https://github.com/Piebald-AI/tweakcc) &nbsp; by &nbsp; [Piebald-AI](https://github.com/Piebald-AI)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
클로드 코드 스타일을 사용자 지정하기 위한 명령줄 도구입니다.

[`viberank`](https://github.com/sculptdotfun/viberank) &nbsp; by &nbsp; [nikshepsvn](https://github.com/nikshepsvn)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
개발자가 클로드 코드 사용 통계를 기반으로 시각화, 추적 및 경쟁할 수 있도록 하는 커뮤니티 기반 리더보드 도구입니다. 강력한 데이터 분석, GitHub OAuth, 데이터 유효성 검사 및 사용자 친화적인 CLI/웹 제출 방법을 제공합니다.

### IDE 통합

[`클로드 코드 채팅`](https://marketplace.visualstudio.com/items?itemName=AndrePimenta.claude-code-chat) &nbsp; by &nbsp; [andrepimenta](https://github.com/andrepimenta)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;&copy;
VS Code를 위한 우아하고 사용자 친화적인 클로드 코드 채팅 인터페이스입니다.

[`claude-code-ide.el`](https://github.com/manzaltu/claude-code-ide.el) &nbsp; by &nbsp; [manzaltu](https://github.com/manzaltu)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;GPL-3.0
claude-code-ide.el은 Anthropic의 VS Code/IntelliJ 확장 프로그램처럼 클로드 코드를 Emacs와 통합합니다. ediff 기반 코드 제안을 표시하고 LSP/flymake/flycheck 진단을 가져오고 버퍼 컨텍스트를 추적합니다. 기호 참조/정의, 프로젝트 메타데이터 및 트리 시터 AST 쿼리에 대한 확장 가능한 MCP 도구 지원을 추가합니다.

[`claude-code.el`](https://github.com/stevemolitor/claude-code.el) &nbsp; by &nbsp; [stevemolitor](https://github.com/stevemolitor)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
클로드 코드 CLI용 Emacs 인터페이스입니다.

[`claude-code.nvim`](https://github.com/greggh/claude-code.nvim) &nbsp; by &nbsp; [greggh](https://github.com/greggh)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
클로드 코드 AI 도우미와 Neovim 간의 원활한 통합입니다.

[`크리스탈`](https://github.com/stravu/crystal) &nbsp; by &nbsp; [stravu](https://github.com/stravu)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
클로드 코드 에이전트를 오케스트레이션, 모니터링 및 상호 작용하기 위한 완전한 기능을 갖춘 데스크톱 응용 프로그램입니다.

<br>

## 후크 🪝

> **후크**는 클로드의 에이전트 수명 주기의 여러 지점에서 사용자가 명령을 활성화하고 스크립트를 실행할 수 있도록 하는 클로드 코드의 새로운 API입니다.

**[실험적]** - 이 섹션에 나열된 리소스는 완전히 검증되지 않았으며 클로드 코드 후크의 최첨단 특성을 고려할 때 예상대로 작동하지 않을 수 있습니다. 그럼에도 불구하고 최소한 영감의 원천으로, 그리고 이 미지의 영역을 탐험하기 위해 포함하고 싶었습니다. 귀하의 경험은 다를 수 있습니다!

[`CC Notify`](https://github.com/dazuiba/CCNotify) &nbsp; by &nbsp; [dazuiba](https://github.com/dazuiba)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
CCNotify는 클로드 코드에 대한 데스크톱 알림을 제공하여 입력 필요 또는 작업 완료를 알리고 VS Code로 한 번의 클릭으로 돌아가고 작업 기간을 표시합니다.

[`cchooks`](https://github.com/GowayLee/cchooks) &nbsp; by &nbsp; [GowayLee](https://github.com/GowayLee)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
깨끗한 API와 좋은 문서를 갖춘 경량 Python SDK; 후크를 작성하고 코드베이스에 통합하는 프로세스를 단순화하여 JSON 구성 파일에 대한 좋은 추상화를 제공합니다.

[`claude-code-hooks-sdk`](https://github.com/beyondcode/claude-hooks-sdk) &nbsp; by &nbsp; [beyondcode](https://github.com/beyondcode)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
깨끗하고 유창한 API로 클로드 코드 후크 응답을 구축하기 위한 Laravel에서 영감을 받은 PHP SDK입니다. 이 SDK를 사용하면 표현력이 풍부하고 연결 가능한 인터페이스를 사용하여 클로드 코드 후크에 대한 구조화된 JSON 응답을 쉽게 만들 수 있습니다.

[`claude-hooks`](https://github.com/johnlindquist/claude-hooks) &nbsp; by &nbsp; [John Lindquist](https://github.com/johnlindquist)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
강력하고 유연한 인터페이스로 클로드 코드 후크를 구성하고 사용자 지정하기 위한 TypeScript 기반 시스템입니다.

[`Linting, 테스트 및 알림(go)`](https://github.com/Veraticus/nix-config/tree/main/home-manager/claude-code/hooks) &nbsp; by &nbsp; [Josh Symonds](https://github.com/Veraticus)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
코드 품질(linting, 테스트, 알림)을 적용하기 위한 멋진 후크 세트와 멋진 구성 설정도 있습니다.

[`TDD 가드`](https://github.com/nizos/tdd-guard) &nbsp; by &nbsp; [Nizar Selander](https://github.com/nizos)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
실시간으로 파일 작업을 모니터링하고 TDD 원칙을 위반하는 변경을 차단하는 후크 기반 시스템입니다.

<br>

## 슬래시 명령 🔪

### 버전 관리 및 Git

[`/bug-fix`](https://github.com/danielscholl/mvn-mcp-server/blob/main/.claude/commands/bug-fix.md) &nbsp; by &nbsp; [danielscholl](https://github.com/danielscholl)
먼저 GitHub 문제를 만든 다음 기능 브랜치를 만들어 솔루션을 구현하고 병합하기 전에 철저히 테스트하여 버그 수정을 간소화합니다.

[`/commit`](https://github.com/evmts/tevm-monorepo/blob/main/.claude/commands/commit.md) &nbsp; by &nbsp; [evmts](https://github.com/evmts)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
적절한 이모티콘과 함께 기존 커밋 형식을 사용하여 git 커밋을 만들고 프로젝트 표준을 따르고 변경 목적을 설명하는 설명적인 메시지를 만듭니다.

[`/commit-fast`](https://github.com/steadycursor/steadystart/blob/main/.claude/commands/2-commit-fast.md) &nbsp; by &nbsp; [steadycursor](https://github.com/steadycursor)
첫 번째 제안된 메시지를 선택하여 git 커밋 프로세스를 자동화하고 수동 확인을 건너뛰고 클로드 공동 기여자 바닥글을 제거하면서 일관된 형식으로 구조화된 커밋을 생성합니다.

[`/create-pr`](https://github.com/toyamarinyon/giselle/blob/main/.claude/commands/create-pr.md) &nbsp; by &nbsp; [toyamarinyon](https://github.com/toyamarinyon)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
새 브랜치 만들기, 변경 사항 커밋, Biome으로 수정된 파일 서식 지정 및 PR 제출과 같은 전체 워크플로를 처리하여 풀 리퀘스트 생성을 간소화합니다.

[`/create-pull-request`](https://github.com/liam-hq/liam/blob/main/.claude/commands/create-pull-request.md) &nbsp; by &nbsp; [liam-hq](https://github.com/liam-hq)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
GitHub CLI를 사용하여 PR 생성에 대한 포괄적인 지침을 제공하고 제목 규칙을 적용하고 템플릿 구조를 따르고 모범 사례와 함께 구체적인 명령 예제를 제공합니다.

[`/create-worktrees`](https://github.com/evmts/tevm-monorepo/blob/main/.claude/commands/create-worktrees.md) &nbsp; by &nbsp; [evmts](https://github.com/evmts)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
모든 열린 PR 또는 특정 브랜치에 대한 git 작업 트리를 만들고 슬래시가 있는 브랜치를 처리하고 오래된 작업 트리를 정리하고 개발을 위한 사용자 지정 브랜치 생성을 지원합니다.

[`/fix-github-issue`](https://github.com/jeremymailen/kotlinter-gradle/blob/master/.claude/commands/fix-github-issue.md) &nbsp; by &nbsp; [jeremymailen](https://github.com/jeremymailen)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
GitHub CLI를 사용하여 구조화된 접근 방식으로 GitHub 문제를 분석하고 수정하여 문제 세부 정보를 확인하고 필요한 코드 변경을 구현하고 테스트를 실행하고 적절한 커밋 메시지를 만듭니다.

[`/fix-issue`](https://github.com/metabase/metabase/blob/master/.claude/commands/fix-issue.md) &nbsp; by &nbsp; [metabase](https://github.com/metabase)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
문제 번호를 매개변수로 사용하여 GitHub 문제를 해결하고 컨텍스트를 분석하고 솔루션을 구현하고 적절한 통합을 위해 수정 사항을 테스트/검증합니다.

[`/fix-pr`](https://github.com/metabase/metabase/blob/master/.claude/commands/fix-pr.md) &nbsp; by &nbsp; [metabase](https://github.com/metabase)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
자동으로 피드백을 검색하고 검토자의 우려 사항을 해결하고 대상 코드 개선을 수행하고 검토 프로세스를 간소화하여 해결되지 않은 PR 주석을 가져오고 수정합니다.

[`/husky`](https://github.com/evmts/tevm-monorepo/blob/main/.claude/commands/husky.md) &nbsp; by &nbsp; [evmts](https://github.com/evmts)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
사전 커밋 후크를 구성하고 커밋 메시지 표준을 설정하고 린팅 도구와 통합하고 커밋 시 코드 품질을 보장하여 Husky Git 후크를 설정하고 관리합니다.

[`/pr-review`](https://github.com/arkavo-org/opentdf-rs/blob/main/.claude/commands/pr-review.md) &nbsp; by &nbsp; [arkavo-org](https://github.com/arkavo-org)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
기본 코드베이스에 병합하기 전에 피드백을 제공하고 문제를 확인하고 개선 사항을 제안하기 위해 풀 리퀘스트 변경 사항을 검토합니다.

[`/update-branch-name`](https://github.com/giselles-ai/giselle/blob/main/.claude/commands/update-branch-name.md) &nbsp; by &nbsp; [giselles-ai](https://github.com/giselles-ai)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
적절한 접두사 및 형식으로 브랜치 이름을 업데이트하고 명명 규칙을 적용하고 의미 체계 접두사를 지원하고 원격 브랜치 업데이트를 관리합니다.

### 코드 분석 및 테스트

[`/check`](https://github.com/rygwdn/slack-tools/blob/main/.claude/commands/check.md) &nbsp; by &nbsp; [rygwdn](https://github.com/rygwdn)
정적 분석 통합, 보안 취약점 검색, 코드 스타일 적용 및 자세한 보고 기능을 갖춘 포괄적인 코드 품질 및 보안 검사를 수행합니다.

[`/clean`](https://github.com/Graphlet-AI/eridu/blob/main/.claude/commands/clean.md) &nbsp; by &nbsp; [Graphlet-AI](https://github.com/Graphlet-AI)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
블랙 서식 문제를 수정하고 isort로 가져오기를 구성하고 flake8 린팅 문제를 해결하고 mypy 유형 오류를 수정하여 코드 서식 및 품질 문제를 해결합니다.

[`/code_analysis`](https://github.com/kingler/n8n_agent/blob/main/.claude/commands/code_analysis.md) &nbsp; by &nbsp; [kingler](https://github.com/kingler)
지식 그래프 생성, 최적화 제안 및 품질 평가를 포함하여 심층 검사를 위한 고급 코드 분석 명령 메뉴를 제공합니다.

[`/optimize`](https://github.com/to4iki/ai-project-rules/blob/main/.claude/commands/optimize.md) &nbsp; by &nbsp; [to4iki](https://github.com/to4iki)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
코드 성능을 분석하여 병목 현상을 식별하고 응용 프로그램 성능 향상을 위한 구현 지침과 함께 구체적인 최적화를 제안합니다.

[`/repro-issue`](https://github.com/rzykov/metabase/blob/master/.claude/commands/repro-issue.md) &nbsp; by &nbsp; [rzykov](https://github.com/rzykov)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
GitHub 문제에 대한 재현 가능한 테스트 사례를 만들고 테스트가 안정적으로 실패하도록 보장하고 개발자를 위한 명확한 재현 단계를 문서화합니다.

[`/tdd`](https://github.com/zscott/pane/blob/main/.claude/commands/tdd.md) &nbsp; by &nbsp; [zscott](https://github.com/zscott)
테스트 주도 개발 원칙을 사용하여 개발을 안내하고 빨강-녹색-리팩터링 원칙을 적용하고 git 워크플로와 통합하고 PR 생성을 관리합니다.

### 컨텍스트 로딩 및 프라이밍

[`/context-prime`](https://github.com/elizaOS/elizaos.github.io/blob/main/.claude/commands/context-prime.md) &nbsp; by &nbsp; [elizaOS](https://github.com/elizaOS)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
저장소 구조를 로드하고 개발 컨텍스트를 설정하고 프로젝트 목표를 설정하고 협업 매개변수를 정의하여 포괄적인 프로젝트 이해로 클로드를 준비합니다.

[`/initref`](https://github.com/okuvshynov/cubestat/blob/main/.claude/commands/initref.md) &nbsp; by &nbsp; [okuvshynov](https://github.com/okuvshynov)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
표준 문서 템플릿, API 참조 설정, 문서 규칙 및 자리 표시자 콘텐츠 생성으로 참조 문서 구조를 초기화합니다.

[`/load-llms-txt`](https://github.com/ethpandaops/xatu-data/blob/master/.claude/commands/load-llms-txt.md) &nbsp; by &nbsp; [ethpandaops](https://github.com/ethpandaops)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
LLM 구성 파일을 컨텍스트에 로드하고 특정 용어, 모델 구성을 가져오고 AI 토론을 위한 기준 용어를 설정합니다.

[`/load_coo_context`](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/load_coo_context.md) &nbsp; by &nbsp; [Mjvolk3](https://github.com/Mjvolk3)
희소 행렬 연산을 위한 특정 파일을 참조하고 변환 사용법을 설명하고 이전 접근 방식과 비교하고 개발을 위한 데이터 서식 컨텍스트를 설정합니다.

[`/load_dango_pipeline`](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/load_dango_pipeline.md) &nbsp; by &nbsp; [Mjvolk3](https://github.com/Mjvolk3)
파이프라인 파일을 참조하고 작업 컨텍스트를 설정하고 관련 문서로 파이프라인 작업을 준비하여 모델 교육을 위한 컨텍스트를 설정합니다.

[`/prime`](https://github.com/yzyydev/AI-Engineering-Structure/blob/main/.claude/commands/prime.md) &nbsp; by &nbsp; [yzyydev](https://github.com/yzyydev)
디렉터리 구조를 보고 주요 파일을 읽어 초기 프로젝트 컨텍스트를 설정하고 디렉터리 시각화 및 주요 문서 중심으로 표준화된 컨텍스트를 만듭니다.

[`/rsi`](https://github.com/ddisisto/si/blob/main/.claude/commands/rsi.md) &nbsp; by &nbsp; [ddisisto](https://github.com/ddisisto)
모든 명령과 주요 프로젝트 파일을 읽어 프로세스를 간소화하고 명령 컨텍스트를 로드하고 더 나은 개발 워크플로를 설정하여 AI 지원 개발을 최적화합니다.

### 문서 및 변경 로그

[`/add-to-changelog`](https://github.com/berrydev-ai/blockdoc-python/blob/main/.claude/commands/add-to-changelog.md) &nbsp; by &nbsp; [berrydev-ai](https://github.com/berrydev-ai)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
형식 일관성을 유지하면서 변경 로그 파일에 새 항목을 추가하고 변경 사항을 올바르게 문서화하고 버전 추적을 위해 설정된 프로젝트 표준을 따릅니다.

[`/create-docs`](https://github.com/jerseycheese/Narraitor/tree/feature/issue-227-ai-suggestions/.claude/commands/analyze-issue.md) &nbsp; by &nbsp; [jerseycheese](https://github.com/jerseycheese)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
코드 구조와 목적을 분석하여 입력/출력, 동작, 사용자 상호 작용 흐름 및 오류 처리가 있는 에지 사례를 자세히 설명하는 포괄적인 문서를 만듭니다.

[`/docs`](https://github.com/slunsford/coffee-analytics/blob/main/.claude/commands/docs.md) &nbsp; by &nbsp; [slunsford](https://github.com/slunsford)
프로젝트 구조를 따르는 포괄적인 문서를 생성하고 더 나은 사용자 이해를 위해 일관된 형식으로 API 및 사용 패턴을 문서화합니다.

[`/explain-issue-fix`](https://github.com/hackdays-io/toban-contribution-viewer/blob/main/.claude/commands/explain-issue-fix.md) &nbsp; by &nbsp; [hackdays-io](https://github.com/hackdays-io)
GitHub 문제에 대한 솔루션 접근 방식을 문서화하고 기술적 결정을 설명하고 극복한 과제를 자세히 설명하고 더 나은 이해를 위해 구현 컨텍스트를 제공합니다.

[`/update-docs`](https://github.com/Consiliency/Flutter-Structurizr/blob/main/.claude/commands/update-docs.md) &nbsp; by &nbsp; [Consiliency](https://github.com/Consiliency)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
현재 문서 상태를 검토하고 구현 진행 상황을 업데이트하고 단계 문서를 검토하고 프로젝트 전체에서 문서 일관성을 유지합니다.

### CI/CD

[`/release`](https://github.com/kelp/webdown/blob/main/.claude/commands/release.md) &nbsp; by &nbsp; [kelp](https://github.com/kelp)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
변경 로그를 업데이트하고 README 변경 사항을 검토하고 버전 증분을 평가하고 더 나은 버전 추적을 위해 릴리스 변경 사항을 문서화하여 소프트웨어 릴리스를 관리합니다.

[`/run-ci`](https://github.com/hackdays-io/toban-contribution-viewer/blob/main/.claude/commands/run-ci.md) &nbsp; by &nbsp; [hackdays-io](https://github.com/hackdays-io)
가상 환경을 활성화하고 CI 호환 검사 스크립트를 실행하고 반복적으로 오류를 수정하고 완료 전에 모든 테스트가 통과하는지 확인합니다.

### 프로젝트 및 작업 관리

[`/create-command`](https://github.com/scopecraft/command/blob/main/.claude/commands/create-command.md) &nbsp; by &nbsp; [scopecraft](https://github.com/scopecraft)
요구 사항을 분석하고 범주별로 명령을 템플릿화하고 명령 표준을 적용하고 지원 문서를 만들어 적절한 구조로 새 사용자 지정 명령을 만드는 과정을 클로드에게 안내합니다.

[`/create-jtbd`](https://github.com/taddyorg/inkverse/blob/main/.claude/commands/create-jtbd.md) &nbsp; by &nbsp; [taddyorg](https://github.com/taddyorg)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;AGPL-3.0
구조화된 형식으로 사용자 요구 사항을 설명하는 Jobs-to-be-Done 프레임워크를 만들고 특정 사용자 문제에 초점을 맞추고 제품 개발을 위해 작업 범주별로 구성합니다.

[`/create-prd`](https://github.com/taddyorg/inkverse/blob/main/.claude/commands/create-prd.md) &nbsp; by &nbsp; [taddyorg](https://github.com/taddyorg)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;AGPL-3.0
표준화된 문서 구조 및 형식에 따라 자세한 사양, 요구 사항 및 기능을 설명하는 포괄적인 제품 요구 사항 문서를 생성합니다.

[`/create-prp`](https://github.com/Wirasm/claudecode-utils/blob/main/.claude/commands/create-prp.md) &nbsp; by &nbsp; [Wirasm](https://github.com/Wirasm)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
PRP 방법론을 읽고 템플릿 구조를 따르고 포괄적인 요구 사항을 만들고 개발을 위한 제품 정의를 구조화하여 제품 요구 사항 계획을 만듭니다.

[`/project_hello_w_name`](https://github.com/disler/just-prompt/blob/main/.claude/commands/project_hello_w_name.md) &nbsp; by &nbsp; [disler](https://github.com/disler)
이름 입력을 사용하여 사용자 지정 가능한 인사말 구성 요소를 만들고 인수 전달, 구성 요소 재사용성, 상태 관리 및 사용자 입력 처리를 보여줍니다.

[`/todo`](https://github.com/chrisleyva/todo-slash-command/blob/main/todo.md) &nbsp; by &nbsp; [chrisleyva](https://github.com/chrisleyva)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
마감일, 정렬, 작업 우선 순위 지정 및 포괄적인 할 일 목록 관리를 특징으로 하는 클로드 코드 인터페이스를 떠나지 않고 프로젝트 할 일 항목을 신속하게 관리하는 편리한 명령입니다.

### 기타

[`/five`](https://github.com/TuckerTucker/tkr-portfolio/blob/main/.claude/commands/five.md) &nbsp; by &nbsp; [TuckerTucker](https://github.com/TuckerTucker)
"5가지 이유" 방법론을 적용하여 근본 원인 분석을 수행하고 근본적인 문제를 식별하고 복잡한 문제에 대한 해결책을 만듭니다.

[`/fixing_go_in_graph`](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/fixing_go_in_graph.md) &nbsp; by &nbsp; [Mjvolk3](https://github.com/Mjvolk3)
그래프 데이터베이스의 유전자 온톨로지 주석 통합에 중점을 두고 여러 데이터 소스를 처리하고 그래프 표현 문제를 해결하며 올바른 데이터 통합을 보장합니다.

[`/mermaid`](https://github.com/GaloyMoney/lana-bank/blob/main/.claude/commands/mermaid.md) &nbsp; by &nbsp; [GaloyMoney](https://github.com/GaloyMoney)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
SQL 스키마 파일에서 Mermaid 다이어그램을 생성하고 테이블 속성이 있는 엔터티 관계 다이어그램을 만들고 다이어그램 컴파일을 확인하고 전체 엔터티 범위를 보장합니다.

[`/review_dcell_model`](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/review_dcell_model.md) &nbsp; by &nbsp; [Mjvolk3](https://github.com/Mjvolk3)
이전 Dcell 구현 파일을 검토하고 최신 Dango 모델과 비교하고 시간 경과에 따른 변경 사항을 기록하고 더 나은 코드 구성을 위한 리팩토링 접근 방식을 분석합니다.

[`/use-stepper`](https://github.com/zuplo/docs/blob/main/.claude/commands/use-stepper.md) &nbsp; by &nbsp; [zuplo](https://github.com/zuplo)
React Stepper 구성 요소를 사용하도록 문서를 다시 포맷하고 제목 형식을 변환하고 적절한 들여쓰기를 적용하고 경고 형식과의 마크다운 호환성을 유지합니다.

<br>

## CLAUDE.md 파일 📂

> **`CLAUDE.md`** 파일은 클로드 코드가 프로젝트와 코딩 표준을 더 잘 이해하는 데 도움이 되는 중요한 지침과 컨텍스트별 정보 또는 지침이 포함된 파일입니다.

### 언어별

[`AI IntelliJ 플러그인`](https://github.com/didalgolab/ai-intellij-plugin/blob/main/CLAUDE.md) &nbsp; by &nbsp; [didalgolab](https://github.com/didalgolab)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
플랫폼별 코딩 패턴, 자세한 패키지 구조 지침 및 명확한 국제화 표준을 갖춘 IntelliJ 플러그인 개발을 위한 포괄적인 Gradle 명령을 제공합니다.

[`AWS MCP 서버`](https://github.com/alexei-led/aws-mcp-server/blob/main/CLAUDE.md) &nbsp; by &nbsp; [alexei-led](https://github.com/alexei-led)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
자세한 코드 스타일 지침, 포괄적인 오류 처리 권장 사항 및 AWS CLI 상호 작용에 대한 보안 고려 사항과 함께 여러 Python 환경 설정 옵션을 제공합니다.

[`DroidconKotlin`](https://github.com/touchlab/DroidconKotlin/blob/main/CLAUDE.md) &nbsp; by &nbsp; [touchlab](https://github.com/touchlab)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
명확한 모듈 구조와 종속성 주입에 대한 실용적인 지침을 갖춘 크로스 플랫폼 Kotlin Multiplatform 개발을 위한 포괄적인 Gradle 명령을 제공합니다.

[`EDSL`](https://github.com/expectedparrot/edsl/blob/main/CLAUDE.md) &nbsp; by &nbsp; [expectedparrot](https://github.com/expectedparrot)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
엄격한 코드 스타일 적용, 포괄적인 테스트 요구 사항 및 Black 및 mypy를 사용한 표준화된 개발 워크플로를 갖춘 자세한 빌드 및 테스트 명령을 제공합니다.

[`Giselle`](https://github.com/giselles-ai/giselle/blob/main/CLAUDE.md) &nbsp; by &nbsp; [giselles-ai](https://github.com/giselles-ai)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
pnpm 및 Vitest를 사용한 자세한 빌드 및 테스트 명령을 제공하며 엄격한 코드 서식 요구 사항과 코드 일관성을 위한 포괄적인 명명 규칙을 갖추고 있습니다.

[`HASH`](https://github.com/hashintel/hash/blob/main/CLAUDE.md) &nbsp; by &nbsp; [hashintel](https://github.com/hashintel)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
코딩 표준에 대한 강력한 강조, 자세한 Rust 문서 지침 및 체계적인 PR 검토 프로세스를 갖춘 포괄적인 저장소 구조 분석을 제공합니다.

[`Inkline`](https://github.com/inkline/inkline/blob/main/CLAUDE.md) &nbsp; by &nbsp; [inkline](https://github.com/inkline)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
TypeScript 및 Vue 3 Composition API에 중점을 둔 pnpm을 사용한 개발 워크플로, 자세한 구성 요소 생성 프로세스 및 포괄적인 테스트 권장 사항을 구성합니다.

[`JSBeeb`](https://github.com/mattgodbolt/jsbeeb/blob/main/CLAUDE.md) &nbsp; by &nbsp; [mattgodbolt](https://github.com/mattgodbolt)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;GPL-3.0
빌드 및 테스트 지침, 아키텍처 문서 및 디버깅 워크플로가 포함된 JavaScript BBC Micro 에뮬레이터 개발 가이드를 제공합니다.

[`Lamoom Python`](https://github.com/LamoomAI/lamoom-python/blob/main/CLAUDE.md) &nbsp; by &nbsp; [LamoomAI](https://github.com/LamoomAI)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
AI 모델의 로드 밸런싱, API 문서 및 예제가 포함된 사용 패턴을 갖춘 프로덕션 프롬프트 엔지니어링 라이브러리에 대한 참조 역할을 합니다.

[`LangGraphJS`](https://github.com/langchain-ai/langgraphjs/blob/main/CLAUDE.md) &nbsp; by &nbsp; [langchain-ai](https://github.com/langchain-ai)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
자세한 TypeScript 스타일 지침, 계층화된 라이브러리 아키텍처 및 yarn 작업 공간을 사용한 모노레포 구조를 갖춘 포괄적인 빌드 및 테스트 명령을 제공합니다.

[`Metabase`](https://github.com/metabase/metabase/blob/master/CLAUDE.md) &nbsp; by &nbsp; [metabase](https://github.com/metabase)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
증분 개발, 테스트 및 기능 구현을 위한 단계별 접근 방식에 중점을 둔 Clojure/ClojureScript의 REPL 기반 개발 워크플로를 자세히 설명합니다.

[`SG 자동차 트렌드 백엔드`](https://github.com/sgcarstrends/backend/blob/main/CLAUDE.md) &nbsp; by &nbsp; [sgcarstrends](https://github.com/sgcarstrends)
개발, 테스트, 배포 및 AWS/Cloudflare 통합을 위한 자세한 명령이 포함된 TypeScript 모노레포 프로젝트에 대한 포괄적인 구조를 제공합니다.

[`SPy`](https://github.com/spylang/spy/blob/main/CLAUDE.md) &nbsp; by &nbsp; [spylang](https://github.com/spylang)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
포괄적인 테스트 지침, 여러 코드 컴파일 옵션 및 대상 필터링을 위한 백엔드별 테스트 데코레이터로 엄격한 코딩 규칙을 적용합니다.

[`TPL`](https://github.com/KarpelesLab/tpl/blob/master/CLAUDE.md) &nbsp; by &nbsp; [KarpelesLab](https://github.com/KarpelesLab)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
포괄적인 오류 처리 권장 사항, 테이블 기반 테스트 접근 방식 지침 및 최신 Go 기능에 대한 현대화 제안과 함께 Go 프로젝트 규칙을 자세히 설명합니다.

### 도메인별

[`AVS Vibe 개발자 가이드`](https://github.com/Layr-Labs/avs-vibe-developer-guide/blob/master/CLAUDE.md) &nbsp; by &nbsp; [Layr-Labs](https://github.com/Layr-Labs)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
프롬프트 파일에 대한 일관된 명명 규칙과 블록체인 개념에 대한 확립된 용어 표준을 사용하여 AI 지원 EigenLayer AVS 개발 워크플로를 구성합니다.

[`Comm`](https://github.com/CommE2E/comm/blob/master/CLAUDE.md) &nbsp; by &nbsp; [CommE2E](https://github.com/CommE2E)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;BSD-3-Clause
코드 구성 아키텍처, 보안 구현 세부 정보 및 테스트 절차를 갖춘 E2E 암호화 메시징 응용 프로그램에 대한 개발 참조 역할을 합니다.

[`코스 빌더`](https://github.com/badass-courses/course-builder/blob/main/CLAUDE.md) &nbsp; by &nbsp; [badass-courses](https://github.com/badass-courses)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
다양한 기술 스택 통합 및 Turborepo를 사용한 모노레포 아키텍처를 통해 공동 코스 생성을 위한 실시간 멀티플레이어 기능을 활성화합니다.

[`커서 도구`](https://github.com/eastlondoner/cursor-tools/blob/main/CLAUDE.md) &nbsp; by &nbsp; [eastlondoner](https://github.com/eastlondoner)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
유연한 명령 옵션과 "Stagehand" 기능을 통한 브라우저 자동화를 통해 여러 공급자 및 모델을 지원하는 다목적 AI 명령 인터페이스를 만듭니다.

[`기타`](https://github.com/soramimi/Guitar/blob/master/CLAUDE.md) &nbsp; by &nbsp; [soramimi](https://github.com/soramimi)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;GPL-2.0
다양한 플랫폼에 대한 빌드 명령, 기여를 위한 코드 스타일 지침 및 프로젝트 구조 설명을 갖춘 Guitar Git GUI 클라이언트 개발 가이드 역할을 합니다.

[`네트워크 연대기`](https://github.com/Fimeg/NetworkChronicles/blob/legacy-v1/CLAUDE.md) &nbsp; by &nbsp; [Fimeg](https://github.com/Fimeg)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
LLM 통합에 대한 기술 사양, 캐릭터 지침 및 서비스 검색 메커니즘을 갖춘 AI 기반 게임 캐릭터에 대한 자세한 구현 계획을 제시합니다.

[`노트 컴패니언`](https://github.com/different-ai/note-companion/blob/master/CLAUDE.md) &nbsp; by &nbsp; [different-ai](https://github.com/different-ai)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
스타일 충돌을 방지하기 위해 사용자 지정 접두사가 있는 Tailwind를 사용하는 Obsidian 플러그인에 대한 자세한 스타일 격리 기술과 실용적인 문제 해결 단계를 제공합니다.

[`파레토 맥`](https://github.com/ParetoSecurity/pareto-mac/blob/main/CLAUDE.md) &nbsp; by &nbsp; [ParetoSecurity](https://github.com/ParetoSecurity)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;GPL-3.0
빌드 지침, 기여 지침, 테스트 절차 및 워크플로 문서가 포함된 Mac 보안 감사 도구 개발 가이드 역할을 합니다.

[`SteadyStart`](https://github.com/steadycursor/steadystart/blob/main/CLAUDE.md) &nbsp; by &nbsp; [steadycursor](https://github.com/steadycursor)
스타일, 권한, 클로드의 "역할", 커뮤니케이션 및 다른 팀원이 최신 정보를 얻을 수 있도록 클로드 코드 세션 문서에 대한 명확하고 직접적인 지침입니다.

### 프로젝트 스캐폴딩 및 MCP

[`기본 메모리`](https://github.com/basicmachines-co/basic-memory/blob/main/CLAUDE.md) &nbsp; by &nbsp; [basicmachines-co](https://github.com/basicmachines-co)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;AGPL-3.0
양방향 LLM-마크다운 통신을 위한 모델 컨텍스트 프로토콜과 복잡한 프로젝트를 위한 유연한 지식 구조를 갖춘 혁신적인 AI-인간 협업 프레임워크를 제시합니다.

[`claude-code-mcp-enhanced`](https://github.com/grahama1970/claude-code-mcp-enhanced/blob/main/CLAUDE.md) &nbsp; by &nbsp; [grahama1970](https://github.com/grahama1970)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
테스트 지침, 코드 예제 및 규정 준수 검사와 함께 코딩 에이전트로서 클로드가 따라야 할 상세하고 강조적인 지침을 제공합니다.

[`Perplexity MCP`](https://github.com/Family-IT-Guy/perplexity-mcp/blob/main/CLAUDE.md) &nbsp; by &nbsp; [Family-IT-Guy](https://github.com/Family-IT-Guy)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;ISC
여러 구성 옵션, 자세한 문제 해결 지침 및 MCP 프로토콜 아키텍처에 대한 간결한 개요와 함께 명확한 단계별 설치 지침을 제공합니다.

<br>

## 공식 문서 🏛️

> 클로드 코드에 관한 Anthropic의 훌륭한 문서 및 리소스 링크

<!--lint disable double-link-->

[`Anthropic 문서`](https://docs.anthropic.com/en/docs/claude-code) &nbsp; by &nbsp; [Anthropic](https://github.com/anthropics)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;&copy;
설치 지침, 사용 지침, API 참조, 자습서, 예제 및 개별적으로 나열하지 않을 많은 정보를 포함하는 클로드 코드의 공식 문서입니다. 클로드 코드와 마찬가지로 문서도 자주 업데이트됩니다.

[`Anthropic 빠른 시작`](https://github.com/anthropics/anthropic-quickstarts/blob/main/CLAUDE.md) &nbsp; by &nbsp; [Anthropic](https://github.com/anthropics)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
표준화된 워크플로, 엄격한 코드 스타일 지침 및 컨테이너화 지침을 갖춘 세 가지 개별 AI 기반 데모 프로젝트에 대한 포괄적인 개발 가이드를 제공합니다.

[`클로드 코드 GitHub 작업`](https://github.com/anthropics/claude-code-action/tree/main/examples) &nbsp; by &nbsp; [Anthropic](https://github.com/anthropics)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
CI/CD 파이프라인에서 AI 기반 워크플로를 자동화하기 위한 예제 및 문서가 포함된 클로드 코드의 공식 GitHub 작업 통합입니다.

## 기여 🌻

### 🚀 **[여기에 새 리소스 제출!](https://github.com/hesreallyhim/awesome-claude-code/issues/new?template=submit-resource.yml)**

쉽습니다! 위의 링크를 클릭하고 양식을 작성하기만 하면 됩니다. Git 지식이 필요하지 않습니다. 자동화된 시스템이 모든 것을 처리합니다.

**특히 환영합니다:**

- 모범 사례를 따르고 프로덕션에서 사용될 수도 있는 입증되고 효과적인 리소스
- 클로드 코드 기능의 한계를 뛰어넘는 혁신적이고 창의적이거나 실험적인 워크플로
- 클로드 코드 위에 구축된 추가 라이브러리 및 도구
- 기존 "코딩 도우미" 컨텍스트 외부의 클로드 코드 응용 프로그램(CI/CD, 테스트, 문서, 개발 운영 등)

전체 제출 가이드 및 검토 프로세스는 [CONTRIBUTING.md](CONTRIBUTING.md)를 참조하십시오.

저장소 자체에 대한 제안 사항은 [일반 문제 열기](https://github.com/hesreallyhim/awesome-claude-code/issues/new)를 참조하십시오.

이 프로젝트는 [기여자 행동 강령](code-of-conduct.md)과 함께 릴리스됩니다. 참여함으로써 귀하는 해당 약관을 준수하는 데 동의하는 것입니다.

### 라이선스에 대한 참고 사항

하이퍼링크를 나열하는 것만으로는 재배포에 해당하지 않으므로 원본 소스의 라이선스는 포함과 관련이 없습니다. 그러나 후세와 편의를 위해 라이선스가 허용하는 모든 리소스의 사본을 호스팅합니다. 따라서 리소스의 라이선스에 대한 정보를 포함하십시오. 또한 다음 사항에 유의하십시오. _GitHub 저장소에 라이선스를 포함하지 않으면 기본적으로 저작권이 완전히 보호되며 재배포가 허용되지 않습니다_. 따라서 오픈 소스 프로젝트를 만들려는 경우 사용 가능한 많은 오픈 소스 라이선스 중 하나를 선택하는 것이 중요합니다. 이것은 라이선스가 없으면 프로젝트가 오픈 소스가 아니라는 점을 상기시켜주는 것입니다(단순히 소스 코드를 사용할 수 있을 뿐입니다). 물론 이 목록에 포함될 수 있지만 이 공지는 독자에게 GitHub 및 라이선스 파일에 대한 기본 규칙을 알리기 위한 것입니다. 자세한 내용은 [여기](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository)를 참조하십시오.

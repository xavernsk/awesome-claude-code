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

# [Fantastico Claude Code](https://github.com/hesreallyhim/awesome-claude-code) 🤝 [Fantastici Agenti Claude Code](https://github.com/hesreallyhim/awesome-claude-code-agents)

<!--lint enable remark-lint:awesome-badge-->

<!--lint disable double-link-->

Questa è una lista curata di comandi slash, file `CLAUDE.md`, strumenti CLI e altre risorse e guide per migliorare il tuo flusso di lavoro, la produttività e le vibrazioni di [Claude Code](https://docs.anthropic.com/en/docs/claude-code).

<!--lint enable double-link-->

Claude Code è un assistente e agente di codifica all'avanguardia basato su CLI a cui puoi accedere nel tuo terminale o IDE. È uno strumento in rapida evoluzione che offre una serie di potenti funzionalità e consente un'ampia configurazione, in molti modi diversi. Gli utenti stanno elaborando attivamente le migliori pratiche e i flussi di lavoro. Si spera che questo repository aiuti la comunità a condividere le conoscenze e a capire come ottenere il massimo da Claude Code.

### Annunci

- 2025-07-30 - Aggiornamento rapido: sto ancora cercando di risolvere il flusso di invio (scusate per chiunque abbia ricevuto problemi duplicati di "Congratulazioni!"). Se finite per combattere con uno qualsiasi degli strumenti di invio programmatico, inviate semplicemente qualcosa che abbia tutti i dati necessari, e me ne occuperò io una volta approvato. Altre note: (i) penso che sarebbe davvero bello/divertente creare una "Classifica di Claude Code", quindi sentitevi liberi di dare la vostra opinione nella [Discussione](https://github.com/hesreallyhim/awesome-claude-code/discussions/81); (ii) sto ancora cercando di capire cosa fare dei **SOTTOAGENTI**, e ho contattato alcune delle altre persone che hanno avviato repository simili; (iii) ho aggiunto una piccola sezione che verrà aggiornata con i nuovi invii man mano che arrivano.

## Nuove aggiunte

- [`CC Notify`](https://github.com/dazuiba/CCNotify) di [dazuiba](https://github.com/dazuiba)
- [`tweakcc`](https://github.com/Piebald-AI/tweakcc) di [Piebald-AI](https://github.com/Piebald-AI)
- [`cchooks`](https://github.com/GowayLee/cchooks) di [GowayLee](https://github.com/GowayLee)

<br>

## Contenuti

▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Flussi di lavoro e guide alla conoscenza](#flussi-di-lavoro-e-guide-alla-conoscenza-)
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Strumenti](#strumenti-)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Integrazioni IDE](#integrazioni-ide)
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Ganci](#ganci-)
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Comandi slash](#comandi-slash-)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Controllo di versione e Git](#controllo-di-versione-e-git)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Analisi e test del codice](#analisi-e-test-del-codice)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Caricamento e preparazione del contesto](#caricamento-e-preparazione-del-contesto)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Documentazione e registri delle modifiche](#documentazione-e-registri-delle-modifiche)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[CI / Distribuzione](#ci--distribuzione)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Gestione di progetti e attività](#gestione-di-progetti-e-attività)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Varie](#varie)
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[File CLAUDE.md](#file-claudemd-)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Specifico per lingua](#specifico-per-lingua)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Specifico per dominio](#specifico-per-dominio)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;▫&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Scaffolding di progetti e MCP](#scaffolding-di-progetti-e-mcp)
▪&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Documentazione ufficiale](#documentazione-ufficiale-)

<br>

## Flussi di lavoro e guide alla conoscenza 🧠

> Un **flusso di lavoro** è un insieme strettamente accoppiato di risorse native di Claude Code che facilitano progetti specifici.

[`Istruzioni per la piattaforma di blogging`](https://github.com/cloudartisan/cloudartisan.github.io/tree/main/.claude/commands) &nbsp; di &nbsp; [cloudartisan](https://github.com/cloudartisan)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;CC-BY-SA-4.0
Fornisce un insieme ben strutturato di comandi per la pubblicazione e la manutenzione di una piattaforma di blogging, inclusi comandi per la creazione di post, la gestione delle categorie e la gestione dei file multimediali.

[`ClaudeLog`](https://claudelog.com) &nbsp; di &nbsp; [InventorBlack](https://www.reddit.com/user/inventor_black/)
Una base di conoscenza completa con analisi dettagliate di [meccaniche](https://claudelog.com/mechanics/you-are-the-main-thread/) avanzate, incluse le [migliori pratiche di CLAUDE.md](https://claudelog.com/mechanics/claude-md-supremacy), guide pratiche a tecniche come la [modalità piano](https://claudelog.com/mechanics/plan-mode), l'[ultrapensiero](https://claudelog.com/faqs/what-is-ultrathink/), i [sottoagenti](https://claudelog.com/mechanics/task-agent-tools/), la [progettazione incentrata sull'agente](https://claudelog.com/mechanics/agent-first-design/) e le [guide alla configurazione](https://claudelog.com/configuration).

[`Preparazione del contesto`](https://github.com/disler/just-prompt/tree/main/.claude/commands) &nbsp; di &nbsp; [disler](https://github.com/disler)
Fornisce un approccio sistematico alla preparazione di Claude Code con un contesto di progetto completo tramite comandi specializzati per diversi scenari di progetto e contesti di sviluppo.

[`n8n_agent`](https://github.com/kingler/n8n_agent/tree/main/.claude/commands) &nbsp; di &nbsp; [kingler](https://github.com/kingler)
Incredibile set completo di commenti per l'analisi del codice, il controllo qualità, la progettazione, la documentazione, la struttura del progetto, la gestione del progetto, l'ottimizzazione e molto altro.

[`Avvio di progetti e gestione delle attività`](https://github.com/steadycursor/steadystart/tree/main/.claude/commands) &nbsp; di &nbsp; [steadycursor](https://github.com/steadycursor)
Fornisce un insieme strutturato di comandi per l'avvio e la gestione di un nuovo progetto, inclusi i meta-comandi per la creazione e la modifica di comandi slash personalizzati.

[`Gestione, implementazione, pianificazione и rilascio del progetto`](https://github.com/scopecraft/command/tree/main/.claude/commands) &nbsp; di &nbsp; [scopecraft](https://github.com/scopecraft)
Insieme di comandi davvero completo per tutti gli aspetti del ciclo di vita dello sviluppo del software.

[`Sistema di flusso di lavoro del progetto`](https://github.com/harperreed/dotfiles/tree/master/.claude/commands) &nbsp; di &nbsp; [harperreed](https://github.com/harperreed)
Un insieme di comandi che fornisce un sistema di flusso di lavoro completo per la gestione dei progetti, inclusa la gestione delle attività, la revisione del codice e i processi di distribuzione.

[`Spedizione di codice reale con Claude`](https://diwank.space/field-notes-from-shipping-real-code-with-claude) &nbsp; di &nbsp; [Diwank](https://github.com/creatorrr)
Un post dettagliato sul blog che spiega il processo dell'autore per la spedizione di un prodotto con Claude Code, inclusi i file CLAUDE.md e altre risorse interessanti.

[`Simone`](https://github.com/Helmi/claude-simone) &nbsp; di &nbsp; [Helmi](https://github.com/Helmi)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Un flusso di lavoro di gestione del progetto più ampio per Claude Code che comprende non solo un insieme di comandi, ma un sistema di documenti, linee guida e processi per facilitare la pianificazione e l'esecuzione del progetto.

[`Megalista di comandi slash`](https://github.com/wcygan/dotfiles/tree/d8ab6b9f5a7a81007b7f5fa3025d4f83ce12cc02/claude/commands) &nbsp; di &nbsp; [wcygan](https://github.com/wcygan)
Una lista piuttosto sbalorditiva (88 al momento di questo post!) di comandi slash che vanno dall'orchestrazione di agenti, alla revisione del codice, alla gestione del progetto, alla sicurezza, alla documentazione, all'autovalutazione, a quasi tutto ciò che si può sognare.

<br>

## Strumenti 🧰

> **Strumenti** denota applicazioni costruite su Claude Code e composte da più componenti rispetto ai comandi slash e ai file `CLAUDE.md`.

[`Utilizzo di CC`](https://github.com/ryoppippi/ccusage) &nbsp; di &nbsp; [ryoppippi](https://github.com/ryoppippi)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Pratico strumento CLI per la gestione e l'analisi dell'utilizzo di Claude Code, basato sull'analisi dei registri locali di Claude Code. Presenta una bella dashboard con informazioni sui costi, sul consumo di token, ecc.

[`ccexp`](https://github.com/nyatinte/ccexp) &nbsp; di &nbsp; [nyatinte](https://github.com/nyatinte)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Strumento CLI interattivo per scoprire e gestire i file di configurazione e i comandi slash di Claude Code con una bellissima interfaccia utente da terminale.

[`cclogviewer`](https://github.com/Brads3290/cclogviewer) &nbsp; di &nbsp; [Brad S.](https://github.com/Brads3290)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Un'umile ma pratica utilità per visualizzare i file di conversazione `.jsonl` di Claude Code in una graziosa interfaccia utente HTML.

[`Flusso di codice Claude`](https://github.com/ruvnet/claude-code-flow) &nbsp; di &nbsp; [ruvnet](https://github.com/ruvnet)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Questa modalità funge da livello di orchestrazione incentrato sul codice, consentendo a Claude di scrivere, modificare, testare e ottimizzare il codice in modo autonomo attraverso cicli di agenti ricorsivi.

[`Monitoraggio dell'utilizzo del codice Claude`](https://github.com/Maciek-roboblog/Claude-Code-Usage-Monitor) &nbsp; di &nbsp; [Maciek-roboblog](https://github.com/Maciek-roboblog)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Uno strumento basato su terminale in tempo reale per il monitoraggio dell'utilizzo dei token di Claude Code. Mostra il consumo di token in tempo reale, il tasso di consumo e le previsioni per l'esaurimento dei token. Le funzionalità includono barre di avanzamento visive, analisi consapevoli della sessione e supporto per più piani di abbonamento.

[`Compositore Claude`](https://github.com/possibilities/claude-composer) &nbsp; di &nbsp; [Mike Bannister](https://github.com/possibilities)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Unlicense
Uno strumento che aggiunge piccoli miglioramenti a Claude Code.

[`Hub Claude`](https://github.com/claude-did-this/claude-hub) &nbsp; di &nbsp; [Claude Did This](https://github.com/claude-did-this)
Un servizio di webhook che collega Claude Code ai repository di GitHub, consentendo l'assistenza al codice basata sull'intelligenza artificiale direttamente tramite richieste pull e problemi. Questa integrazione consente a Claude di analizzare i repository, rispondere a domande tecniche e aiutare gli sviluppatori a comprendere e migliorare la loro base di codice tramite semplici @menzioni.

[`Squadra Claude`](https://github.com/smtg-ai/claude-squad) &nbsp; di &nbsp; [smtg-ai](https://github.com/smtg-ai)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;AGPL-3.0
Claude Squad è un'app per terminale che gestisce più Claude Code, Codex (e altri agenti locali, incluso Aider) in spazi di lavoro separati, consentendoti di lavorare su più attività contemporaneamente.

[`Sciame Claude`](https://github.com/parruda/claude-swarm) &nbsp; di &nbsp; [parruda](https://github.com/parruda)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Avvia una sessione di Claude Code connessa a uno sciame di agenti di Claude Code.

[`Maestro dei compiti Claude`](https://github.com/eyaltoledano/claude-task-master) &nbsp; di &nbsp; [eyaltoledano](https://github.com/eyaltoledano)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
Un sistema di gestione delle attività per lo sviluppo basato sull'intelligenza artificiale con Claude, progettato per funzionare senza problemi con Cursor AI.

[`Esecutore di attività Claude`](https://github.com/grahama1970/claude-task-runner) &nbsp; di &nbsp; [grahama1970](https://github.com/grahama1970)
Uno strumento specializzato per gestire l'isolamento del contesto e l'esecuzione mirata delle attività con Claude Code, risolvendo la sfida critica dei limiti di lunghezza del contesto e della focalizzazione sulle attività quando si lavora con Claude su progetti complessi e multi-passo.

[`strumenti-codice-claude`](https://github.com/pchalasani/claude-code-tools) &nbsp; di &nbsp; [Prasad Chalasani](https://github.com/pchalasani)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Una raccolta di fantastici strumenti, tra cui integrazioni con tmux, una migliore gestione delle sessioni, ganci che migliorano la sicurezza: un insieme di miglioramenti di Claude Code davvero ben fatto, soprattutto per gli utenti di tmux.

[`Utilizzo del contenitore`](https://github.com/dagger/container-use) &nbsp; di &nbsp; [dagger](https://github.com/dagger)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
Ambienti di sviluppo per agenti di codifica. Consenti a più agenti di lavorare in modo sicuro e indipendente con il tuo stack preferito.

[`TSK - Gestore di attività e sandbox per agenti IA`](https://github.com/dtormoen/tsk) &nbsp; di &nbsp; [dtormoen](https://github.com/dtormoen)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Uno strumento CLI Rust che ti consente di delegare le attività di sviluppo ad agenti IA in esecuzione in ambienti Docker sandbox. Più agenti lavorano in parallelo, restituendo rami git per la revisione umana.

[`tweakcc`](https://github.com/Piebald-AI/tweakcc) &nbsp; di &nbsp; [Piebald-AI](https://github.com/Piebald-AI)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Strumento da riga di comando per personalizzare lo stile del tuo Claude Code.

[`viberank`](https://github.com/sculptdotfun/viberank) &nbsp; di &nbsp; [nikshepsvn](https://github.com/nikshepsvn)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Uno strumento di classifica guidato dalla comunità che consente agli sviluppatori di visualizzare, monitorare e competere in base alle loro statistiche di utilizzo di Claude Code. È dotato di solide analisi dei dati, OAuth di GitHub, convalida dei dati e metodi di invio CLI/web intuitivi.

### Integrazioni IDE

[`Chat di Claude Code`](https://marketplace.visualstudio.com/items?itemName=AndrePimenta.claude-code-chat) &nbsp; di &nbsp; [andrepimenta](https://github.com/andrepimenta)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;&copy;
Un'interfaccia di chat di Claude Code elegante e intuitiva per VS Code.

[`claude-code-ide.el`](https://github.com/manzaltu/claude-code-ide.el) &nbsp; di &nbsp; [manzaltu](https://github.com/manzaltu)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;GPL-3.0
claude-code-ide.el integra Claude Code con Emacs, come le estensioni di Anthropic per VS Code/IntelliJ. Mostra suggerimenti di codice basati su ediff, estrae la diagnostica LSP/flymake/flycheck e tiene traccia del contesto del buffer. Aggiunge un supporto estensibile per strumenti MCP per riferimenti/definizioni di simboli, metadati di progetto e query AST di tree-sitter.

[`claude-code.el`](https://github.com/stevemolitor/claude-code.el) &nbsp; di &nbsp; [stevemolitor](https://github.com/stevemolitor)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
Un'interfaccia Emacs per la CLI di Claude Code.

[`claude-code.nvim`](https://github.com/greggh/claude-code.nvim) &nbsp; di &nbsp; [greggh](https://github.com/greggh)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Un'integrazione perfetta tra l'assistente IA di Claude Code e Neovim.

[`cristallo`](https://github.com/stravu/crystal) &nbsp; di &nbsp; [stravu](https://github.com/stravu)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Un'applicazione desktop completa per orchestrare, monitorare e interagire con gli agenti di Claude Code.

<br>

## Ganci 🪝

> I **ganci** sono una nuovissima API per Claude Code che consente agli utenti di attivare comandi ed eseguire script in diversi punti del ciclo di vita agentico di Claude.

**[Sperimentale]** - Le risorse elencate in questa sezione non sono state completamente verificate e potrebbero non funzionare come previsto, data la natura all'avanguardia dei ganci di Claude Code. Tuttavia, ho voluto includerle almeno come fonte di ispirazione e per esplorare questo terreno sconosciuto. La tua esperienza potrebbe variare!

[`Notifica CC`](https://github.com/dazuiba/CCNotify) &nbsp; di &nbsp; [dazuiba](https://github.com/dazuiba)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
CCNotify fornisce notifiche desktop per Claude Code, avvisandoti delle necessità di input o del completamento delle attività, con salti con un clic per tornare a VS Code e la visualizzazione della durata dell'attività.

[`cchooks`](https://github.com/GowayLee/cchooks) &nbsp; di &nbsp; [GowayLee](https://github.com/GowayLee)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Un SDK Python leggero con un'API pulita e una buona documentazione; semplifica il processo di scrittura dei ganci e la loro integrazione nella tua base di codice, fornendo una buona astrazione sui file di configurazione JSON.

[`sdk-ganci-codice-claude`](https://github.com/beyondcode/claude-hooks-sdk) &nbsp; di &nbsp; [beyondcode](https://github.com/beyondcode)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Un SDK PHP ispirato a Laravel per la creazione di risposte ai ganci di Claude Code con un'API pulita e fluente. Questo SDK semplifica la creazione di risposte JSON strutturate per i ganci di Claude Code utilizzando un'interfaccia espressiva e concatenabile.

[`ganci-claude`](https://github.com/johnlindquist/claude-hooks) &nbsp; di &nbsp; [John Lindquist](https://github.com/johnlindquist)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Un sistema basato su TypeScript per la configurazione e la personalizzazione dei ganci di Claude Code con un'interfaccia potente e flessibile.

[`Linting, test e notifiche (in go)`](https://github.com/Veraticus/nix-config/tree/main/home-manager/claude-code/hooks) &nbsp; di &nbsp; [Josh Symonds](https://github.com/Veraticus)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Bel set di ganci per l'applicazione della qualità del codice (linting, test, notifiche), con anche una bella configurazione.

[`Guardia TDD`](https://github.com/nizos/tdd-guard) &nbsp; di &nbsp; [Nizar Selander](https://github.com/nizos)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Un sistema guidato da ganci che monitora le operazioni sui file in tempo reale e blocca le modifiche che violano i principi TDD.

<br>

## Comandi slash 🔪

### Controllo di versione e Git

[`/bug-fix`](https://github.com/danielscholl/mvn-mcp-server/blob/main/.claude/commands/bug-fix.md) &nbsp; di &nbsp; [danielscholl](https://github.com/danielscholl)
Semplifica la correzione dei bug creando prima un problema su GitHub, quindi un ramo di funzionalità per implementare e testare a fondo la soluzione prima di unirla.

[`/commit`](https://github.com/evmts/tevm-monorepo/blob/main/.claude/commands/commit.md) &nbsp; di &nbsp; [evmts](https://github.com/evmts)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Crea commit git utilizzando il formato di commit convenzionale con emoji appropriate, seguendo gli standard di progetto e creando messaggi descrittivi che spiegano lo scopo delle modifiche.

[`/commit-fast`](https://github.com/steadycursor/steadystart/blob/main/.claude/commands/2-commit-fast.md) &nbsp; di &nbsp; [steadycursor](https://github.com/steadycursor)
Automatizza il processo di commit di git selezionando il primo messaggio suggerito, generando commit strutturati con formattazione coerente saltando la conferma manuale e rimuovendo il piè di pagina di co-contribuzione di Claude.

[`/create-pr`](https://github.com/toyamarinyon/giselle/blob/main/.claude/commands/create-pr.md) &nbsp; di &nbsp; [toyamarinyon](https://github.com/toyamarinyon)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
Semplifica la creazione di richieste pull gestendo l'intero flusso di lavoro: creazione di un nuovo ramo, commit delle modifiche, formattazione dei file modificati con Biome e invio della PR.

[`/create-pull-request`](https://github.com/liam-hq/liam/blob/main/.claude/commands/create-pull-request.md) &nbsp; di &nbsp; [liam-hq](https://github.com/liam-hq)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
Fornisce una guida completa alla creazione di PR con la CLI di GitHub, imponendo le convenzioni sui titoli, seguendo la struttura del modello e offrendo esempi di comandi concreti con le migliori pratiche.

[`/create-worktrees`](https://github.com/evmts/tevm-monorepo/blob/main/.claude/commands/create-worktrees.md) &nbsp; di &nbsp; [evmts](https://github.com/evmts)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Crea worktree git per tutte le PR aperte o rami specifici, gestendo i rami con barre, pulendo i worktree obsoleti e supportando la creazione di rami personalizzati per lo sviluppo.

[`/fix-github-issue`](https://github.com/jeremymailen/kotlinter-gradle/blob/master/.claude/commands/fix-github-issue.md) &nbsp; di &nbsp; [jeremymailen](https://github.com/jeremymailen)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
Analizza e corregge i problemi di GitHub utilizzando un approccio strutturato con la CLI di GitHub per i dettagli del problema, implementando le modifiche al codice necessarie, eseguendo i test e creando messaggi di commit appropriati.

[`/fix-issue`](https://github.com/metabase/metabase/blob/master/.claude/commands/fix-issue.md) &nbsp; di &nbsp; [metabase](https://github.com/metabase)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
Affronta i problemi di GitHub prendendo il numero del problema come parametro, analizzando il contesto, implementando la soluzione e testando/validando la correzione per una corretta integrazione.

[`/fix-pr`](https://github.com/metabase/metabase/blob/master/.claude/commands/fix-pr.md) &nbsp; di &nbsp; [metabase](https://github.com/metabase)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
Recupera e corregge i commenti di PR non risolti recuperando automaticamente il feedback, affrontando le preoccupazioni dei revisori, apportando miglioramenti mirati al codice e semplificando il processo di revisione.

[`/husky`](https://github.com/evmts/tevm-monorepo/blob/main/.claude/commands/husky.md) &nbsp; di &nbsp; [evmts](https://github.com/evmts)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Configura e gestisce i ganci Git di Husky configurando i ganci di pre-commit, stabilendo gli standard dei messaggi di commit, integrandosi con gli strumenti di linting e garantendo la qualità del codice nei commit.

[`/pr-review`](https://github.com/arkavo-org/opentdf-rs/blob/main/.claude/commands/pr-review.md) &nbsp; di &nbsp; [arkavo-org](https://github.com/arkavo-org)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Esamina le modifiche della richiesta pull per fornire feedback, verificare la presenza di problemi e suggerire miglioramenti prima di unirle alla base di codice principale.

[`/update-branch-name`](https://github.com/giselles-ai/giselle/blob/main/.claude/commands/update-branch-name.md) &nbsp; di &nbsp; [giselles-ai](https://github.com/giselles-ai)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
Aggiorna i nomi dei rami con prefissi e formati appropriati, imponendo le convenzioni di denominazione, supportando i prefissi semantici e gestendo gli aggiornamenti dei rami remoti.

### Analisi e test del codice

[`/check`](https://github.com/rygwdn/slack-tools/blob/main/.claude/commands/check.md) &nbsp; di &nbsp; [rygwdn](https://github.com/rygwdn)
Esegue controlli completi sulla qualità e la sicurezza del codice, con integrazione dell'analisi statica, scansione delle vulnerabilità di sicurezza, applicazione dello stile del codice e reporting dettagliato.

[`/clean`](https://github.com/Graphlet-AI/eridu/blob/main/.claude/commands/clean.md) &nbsp; di &nbsp; [Graphlet-AI](https://github.com/Graphlet-AI)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
Affronta i problemi di formattazione e qualità del codice risolvendo i problemi di formattazione di black, organizzando le importazioni con isort, risolvendo i problemi di linting di flake8 e correggendo gli errori di tipo di mypy.

[`/code_analysis`](https://github.com/kingler/n8n_agent/blob/main/.claude/commands/code_analysis.md) &nbsp; di &nbsp; [kingler](https://github.com/kingler)
Fornisce un menu di comandi avanzati di analisi del codice per un'ispezione approfondita, inclusa la generazione di grafi di conoscenza, suggerimenti di ottimizzazione e valutazione della qualità.

[`/optimize`](https://github.com/to4iki/ai-project-rules/blob/main/.claude/commands/optimize.md) &nbsp; di &nbsp; [to4iki](https://github.com/to4iki)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Analizza le prestazioni del codice per identificare i colli di bottiglia, proponendo ottimizzazioni concrete con una guida all'implementazione per migliorare le prestazioni dell'applicazione.

[`/repro-issue`](https://github.com/rzykov/metabase/blob/master/.claude/commands/repro-issue.md) &nbsp; di &nbsp; [rzykov](https://github.com/rzykov)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
Crea casi di test riproducibili per i problemi di GitHub, garantendo che i test falliscano in modo affidabile e documentando chiari passaggi di riproduzione per gli sviluppatori.

[`/tdd`](https://github.com/zscott/pane/blob/main/.claude/commands/tdd.md) &nbsp; di &nbsp; [zscott](https://github.com/zscott)
Guida lo sviluppo utilizzando i principi dello sviluppo guidato dai test, imponendo la disciplina Rosso-Verde-Refactor, integrandosi con il flusso di lavoro di git e gestendo la creazione di PR.

### Caricamento e preparazione del contesto

[`/context-prime`](https://github.com/elizaOS/elizaos.github.io/blob/main/.claude/commands/context-prime.md) &nbsp; di &nbsp; [elizaOS](https://github.com/elizaOS)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Prepara Claude con una comprensione completa del progetto caricando la struttura del repository, impostando il contesto di sviluppo, stabilendo gli obiettivi del progetto e definendo i parametri di collaborazione.

[`/initref`](https://github.com/okuvshynov/cubestat/blob/main/.claude/commands/initref.md) &nbsp; di &nbsp; [okuvshynov](https://github.com/okuvshynov)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Inizializza la struttura della documentazione di riferimento con modelli di documenti standard, configurazione dei riferimenti API, convenzioni di documentazione e generazione di contenuto segnaposto.

[`/load-llms-txt`](https://github.com/ethpandaops/xatu-data/blob/master/.claude/commands/load-llms-txt.md) &nbsp; di &nbsp; [ethpandaops](https://github.com/ethpandaops)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Carica i file di configurazione LLM nel contesto, importando terminologia specifica, configurazioni del modello e stabilendo una terminologia di base per le discussioni sull'IA.

[`/load_coo_context`](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/load_coo_context.md) &nbsp; di &nbsp; [Mjvolk3](https://github.com/Mjvolk3)
Fa riferimento a file specifici per le operazioni su matrici sparse, spiega l'uso della trasformazione, confronta con approcci precedenti e imposta il contesto di formattazione dei dati per lo sviluppo.

[`/load_dango_pipeline`](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/load_dango_pipeline.md) &nbsp; di &nbsp; [Mjvolk3](https://github.com/Mjvolk3)
Imposta il contesto per l'addestramento del modello facendo riferimento ai file della pipeline, stabilendo il contesto di lavoro e preparandosi per il lavoro sulla pipeline con la documentazione pertinente.

[`/prime`](https://github.com/yzyydev/AI-Engineering-Structure/blob/main/.claude/commands/prime.md) &nbsp; di &nbsp; [yzyydev](https://github.com/yzyydev)
Imposta il contesto iniziale del progetto visualizzando la struttura della directory e leggendo i file chiave, creando un contesto standardizzato con la visualizzazione della directory e concentrandosi sulla documentazione chiave.

[`/rsi`](https://github.com/ddisisto/si/blob/main/.claude/commands/rsi.md) &nbsp; di &nbsp; [ddisisto](https://github.com/ddisisto)
Legge tutti i comandi e i file chiave del progetto per ottimizzare lo sviluppo assistito dall'IA semplificando il processo, caricando il contesto dei comandi e preparandosi per un migliore flusso di lavoro di sviluppo.

### Documentazione e registri delle modifiche

[`/add-to-changelog`](https://github.com/berrydev-ai/blockdoc-python/blob/main/.claude/commands/add-to-changelog.md) &nbsp; di &nbsp; [berrydev-ai](https://github.com/berrydev-ai)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Aggiunge nuove voci ai file del registro delle modifiche mantenendo la coerenza del formato, documentando correttamente le modifiche e seguendo gli standard di progetto stabiliti per il tracciamento delle versioni.

[`/create-docs`](https://github.com/jerseycheese/Narraitor/tree/feature/issue-227-ai-suggestions/.claude/commands/analyze-issue.md) &nbsp; di &nbsp; [jerseycheese](https://github.com/jerseycheese)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Analizza la struttura e lo scopo del codice per creare una documentazione completa che descriva input/output, comportamento, flussi di interazione dell'utente e casi limite con la gestione degli errori.

[`/docs`](https://github.com/slunsford/coffee-analytics/blob/main/.claude/commands/docs.md) &nbsp; di &nbsp; [slunsford](https://github.com/slunsford)
Genera una documentazione completa che segue la struttura del progetto, documentando le API e i modelli di utilizzo con una formattazione coerente per una migliore comprensione da parte dell'utente.

[`/explain-issue-fix`](https://github.com/hackdays-io/toban-contribution-viewer/blob/main/.claude/commands/explain-issue-fix.md) &nbsp; di &nbsp; [hackdays-io](https://github.com/hackdays-io)
Documenta gli approcci alla soluzione per i problemi di GitHub, spiegando le decisioni tecniche, descrivendo in dettaglio le sfide superate e fornendo il contesto di implementazione per una migliore comprensione.

[`/update-docs`](https://github.com/Consiliency/Flutter-Structurizr/blob/main/.claude/commands/update-docs.md) &nbsp; di &nbsp; [Consiliency](https://github.com/Consiliency)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Esamina lo stato attuale della documentazione, aggiorna i progressi dell'implementazione, esamina i documenti di fase e mantiene la coerenza della documentazione in tutto il progetto.

### CI / Distribuzione

[`/release`](https://github.com/kelp/webdown/blob/main/.claude/commands/release.md) &nbsp; di &nbsp; [kelp](https://github.com/kelp)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Gestisce i rilasci del software aggiornando i registri delle modifiche, esaminando le modifiche al README, valutando gli incrementi di versione e documentando le modifiche al rilascio per un migliore tracciamento delle versioni.

[`/run-ci`](https://github.com/hackdays-io/toban-contribution-viewer/blob/main/.claude/commands/run-ci.md) &nbsp; di &nbsp; [hackdays-io](https://github.com/hackdays-io)
Attiva ambienti virtuali, esegue script di controllo compatibili con la CI, corregge gli errori in modo iterativo e garantisce che tutti i test vengano superati prima del completamento.

### Gestione di progetti e attività

[`/create-command`](https://github.com/scopecraft/command/blob/main/.claude/commands/create-command.md) &nbsp; di &nbsp; [scopecraft](https://github.com/scopecraft)
Guida Claude nella creazione di nuovi comandi personalizzati con una struttura adeguata analizzando i requisiti, creando modelli di comandi per categoria, applicando gli standard dei comandi e creando la documentazione di supporto.

[`/create-jtbd`](https://github.com/taddyorg/inkverse/blob/main/.claude/commands/create-jtbd.md) &nbsp; di &nbsp; [taddyorg](https://github.com/taddyorg)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;AGPL-3.0
Crea framework Jobs-to-be-Done che delineano le esigenze degli utenti con un formato strutturato, concentrandosi su problemi specifici degli utenti e organizzando per categorie di lavoro per lo sviluppo del prodotto.

[`/create-prd`](https://github.com/taddyorg/inkverse/blob/main/.claude/commands/create-prd.md) &nbsp; di &nbsp; [taddyorg](https://github.com/taddyorg)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;AGPL-3.0
Genera documenti completi sui requisiti del prodotto che delineano specifiche, requisiti e funzionalità dettagliate seguendo una struttura e un formato di documento standardizzati.

[`/create-prp`](https://github.com/Wirasm/claudecode-utils/blob/main/.claude/commands/create-prp.md) &nbsp; di &nbsp; [Wirasm](https://github.com/Wirasm)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Crea piani dei requisiti del prodotto leggendo la metodologia PRP, seguendo la struttura del modello, creando requisiti completi e strutturando le definizioni del prodotto per lo sviluppo.

[`/project_hello_w_name`](https://github.com/disler/just-prompt/blob/main/.claude/commands/project_hello_w_name.md) &nbsp; di &nbsp; [disler](https://github.com/disler)
Crea componenti di saluto personalizzabili con input del nome, dimostrando il passaggio di argomenti, la riutilizzabilità dei componenti, la gestione dello stato e la gestione dell'input dell'utente.

[`/todo`](https://github.com/chrisleyva/todo-slash-command/blob/main/todo.md) &nbsp; di &nbsp; [chrisleyva](https://github.com/chrisleyva)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Un comodo comando per gestire rapidamente le cose da fare del progetto senza lasciare l'interfaccia di Claude Code, con scadenze, ordinamento, prioritizzazione delle attività e gestione completa dell'elenco delle cose da fare.

### Varie

[`/five`](https://github.com/TuckerTucker/tkr-portfolio/blob/main/.claude/commands/five.md) &nbsp; di &nbsp; [TuckerTucker](https://github.com/TuckerTucker)
Applica la metodologia dei "cinque perché" per eseguire l'analisi delle cause alla radice, identificare i problemi sottostanti e creare approcci risolutivi per problemi complessi.

[`/fixing_go_in_graph`](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/fixing_go_in_graph.md) &nbsp; di &nbsp; [Mjvolk3](https://github.com/Mjvolk3)
Si concentra sull'integrazione dell'annotazione della Gene Ontology nei database a grafo, gestendo più fonti di dati, affrontando i problemi di rappresentazione del grafo e garantendo la corretta incorporazione dei dati.

[`/mermaid`](https://github.com/GaloyMoney/lana-bank/blob/main/.claude/commands/mermaid.md) &nbsp; di &nbsp; [GaloyMoney](https://github.com/GaloyMoney)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
Genera diagrammi Mermaid da file di schema SQL, creando diagrammi entità-relazione con le proprietà delle tabelle, convalidando la compilazione del diagramma e garantendo una copertura completa delle entità.

[`/review_dcell_model`](https://github.com/Mjvolk3/torchcell/blob/main/.claude/commands/review_dcell_model.md) &nbsp; di &nbsp; [Mjvolk3](https://github.com/Mjvolk3)
Esamina i vecchi file di implementazione di Dcell, confrontandoli con il modello Dango più recente, annotando le modifiche nel tempo e analizzando gli approcci di refactoring per una migliore organizzazione del codice.

[`/use-stepper`](https://github.com/zuplo/docs/blob/main/.claude/commands/use-stepper.md) &nbsp; di &nbsp; [zuplo](https://github.com/zuplo)
Riformatta la documentazione per utilizzare il componente React Stepper, trasformando i formati delle intestazioni, applicando la corretta indentazione e mantenendo la compatibilità di markdown con la formattazione degli avvisi.

<br>

## File CLAUDE.md 📂

> I file **`CLAUDE.md`** sono file che contengono importanti linee guida e informazioni o istruzioni specifiche del contesto che aiutano Claude Code a comprendere meglio il tuo progetto e i tuoi standard di codifica.

### Specifico per lingua

[`Plugin AI di IntelliJ`](https://github.com/didalgolab/ai-intellij-plugin/blob/main/CLAUDE.md) &nbsp; di &nbsp; [didalgolab](https://github.com/didalgolab)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
Fornisce comandi Gradle completi per lo sviluppo di plugin per IntelliJ con modelli di codifica specifici della piattaforma, linee guida dettagliate sulla struttura dei pacchetti e chiari standard di internazionalizzazione.

[`Server MCP AWS`](https://github.com/alexei-led/aws-mcp-server/blob/main/CLAUDE.md) &nbsp; di &nbsp; [alexei-led](https://github.com/alexei-led)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Presenta più opzioni di configurazione dell'ambiente Python con linee guida dettagliate sullo stile del codice, raccomandazioni complete sulla gestione degli errori e considerazioni sulla sicurezza per le interazioni con la CLI di AWS.

[`DroidconKotlin`](https://github.com/touchlab/DroidconKotlin/blob/main/CLAUDE.md) &nbsp; di &nbsp; [touchlab](https://github.com/touchlab)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
Fornisce comandi Gradle completi per lo sviluppo multipiattaforma di Kotlin Multiplatform con una chiara struttura dei moduli e una guida pratica per l'iniezione delle dipendenze.

[`EDSL`](https://github.com/expectedparrot/edsl/blob/main/CLAUDE.md) &nbsp; di &nbsp; [expectedparrot](https://github.com/expectedparrot)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Offre comandi di compilazione e test dettagliati con una rigida applicazione dello stile del codice, requisiti di test completi e un flusso di lavoro di sviluppo standardizzato utilizzando Black e mypy.

[`Giselle`](https://github.com/giselles-ai/giselle/blob/main/CLAUDE.md) &nbsp; di &nbsp; [giselles-ai](https://github.com/giselles-ai)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
Fornisce comandi di compilazione e test dettagliati utilizzando pnpm e Vitest con requisiti di formattazione del codice rigorosi e convenzioni di denominazione complete per la coerenza del codice.

[`HASH`](https://github.com/hashintel/hash/blob/main/CLAUDE.md) &nbsp; di &nbsp; [hashintel](https://github.com/hashintel)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
Presenta un'analisi completa della struttura del repository con una forte enfasi sugli standard di codifica, linee guida dettagliate sulla documentazione di Rust e un processo sistematico di revisione delle PR.

[`Inkline`](https://github.com/inkline/inkline/blob/main/CLAUDE.md) &nbsp; di &nbsp; [inkline](https://github.com/inkline)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
Struttura il flusso di lavoro di sviluppo utilizzando pnpm con enfasi su TypeScript e l'API di composizione di Vue 3, un processo dettagliato di creazione dei componenti e raccomandazioni di test complete.

[`JSBeeb`](https://github.com/mattgodbolt/jsbeeb/blob/main/CLAUDE.md) &nbsp; di &nbsp; [mattgodbolt](https://github.com/mattgodbolt)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;GPL-3.0
Fornisce una guida allo sviluppo per l'emulatore BBC Micro di JavaScript con istruzioni di compilazione e test, documentazione dell'architettura e flussi di lavoro di debug.

[`Lamoom Python`](https://github.com/LamoomAI/lamoom-python/blob/main/CLAUDE.md) &nbsp; di &nbsp; [LamoomAI](https://github.com/LamoomAI)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;Apache-2.0
Serve come riferimento per la libreria di ingegneria dei prompt di produzione con bilanciamento del carico dei modelli di intelligenza artificiale, documentazione API e modelli di utilizzo con esempi.

[`LangGraphJS`](https://github.com/langchain-ai/langgraphjs/blob/main/CLAUDE.md) &nbsp; di &nbsp; [langchain-ai](https://github.com/langchain-ai)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Offre comandi di compilazione e test completi con linee guida dettagliate sullo stile di TypeScript, un'architettura di libreria a più livelli e una struttura monorepo che utilizza gli spazi di lavoro di yarn.

[`Metabase`](https://github.com/metabase/metabase/blob/master/CLAUDE.md) &nbsp; di &nbsp; [metabase](https://github.com/metabase)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;NOASSERTION
Dettaglia il flusso di lavoro per lo sviluppo guidato da REPL in Clojure/ClojureScript con enfasi sullo sviluppo incrementale, sui test e su un approccio passo-passo per l'implementazione delle funzionalità.

[`Backend delle tendenze delle auto di SG`](https://github.com/sgcarstrends/backend/blob/main/CLAUDE.md) &nbsp; di &nbsp; [sgcarstrends](https://github.com/sgcarstrends)
Fornisce una struttura completa per i progetti monorepo di TypeScript con comandi dettagliati per lo sviluppo, i test, la distribuzione e l'integrazione con AWS/Cloudflare.

[`SPy`](https://github.com/spylang/spy/blob/main/CLAUDE.md) &nbsp; di &nbsp; [spylang](https://github.com/spylang)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Applica rigide convenzioni di codifica con linee guida di test complete, più opzioni di compilazione del codice e decoratori di test specifici del backend for un filtraggio mirato.

[`TPL`](https://github.com/KarpelesLab/tpl/blob/master/CLAUDE.md) &nbsp; di &nbsp; [KarpelesLab](https://github.com/KarpelesLab)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Dettaglia le convenzioni del progetto Go con raccomandazioni complete sulla gestione degli errori, linee guida sull'approccio ai test basati su tabelle e suggerimenti di modernizzazione per le ultime funzionalità di Go.

### Specifico per dominio

[`Guida per sviluppatori AVS Vibe`](https://github.com/Layr-Labs/avs-vibe-developer-guide/blob/master/CLAUDE.md) &nbsp; di &nbsp; [Layr-Labs](https://github.com/Layr-Labs)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Struttura il flusso di lavoro di sviluppo di EigenLayer AVS assistito dall'intelligenza artificiale con convenzioni di denominazione coerenti per i file di prompt e standard di terminologia stabiliti per i concetti di blockchain.

[`Comm`](https://github.com/CommE2E/comm/blob/master/CLAUDE.md) &nbsp; di &nbsp; [CommE2E](https://github.com/CommE2E)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;BSD-3-Clause
Serve come riferimento per lo sviluppo di applicazioni di messaggistica crittografata end-to-end con architettura di organizzazione del codice, dettagli sull'implementazione della sicurezza e procedure di test.

[`Costruttore di corsi`](https://github.com/badass-courses/course-builder/blob/main/CLAUDE.md) &nbsp; di &nbsp; [badass-courses](https://github.com/badass-courses)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Abilita funzionalità multiplayer in tempo reale per la creazione collaborativa di corsi con integrazione di stack tecnologici diversi e architettura monorepo utilizzando Turborepo.

[`Strumenti del cursore`](https://github.com/eastlondoner/cursor-tools/blob/main/CLAUDE.md) &nbsp; di &nbsp; [eastlondoner](https://github.com/eastlondoner)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Crea un'interfaccia di comando AI versatile che supporta più provider e modelli con opzioni di comando flessibili e automazione del browser tramite la funzione "Stagehand".

[`Chitarra`](https://github.com/soramimi/Guitar/blob/master/CLAUDE.md) &nbsp; di &nbsp; [soramimi](https://github.com/soramimi)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;GPL-2.0
Serve come guida allo sviluppo per il client GUI di Guitar Git con comandi di compilazione per varie piattaforme, linee guida sullo stile del codice per contribuire e spiegazione della struttura del progetto.

[`Cronache di rete`](https://github.com/Fimeg/NetworkChronicles/blob/legacy-v1/CLAUDE.md) &nbsp; di &nbsp; [Fimeg](https://github.com/Fimeg)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Presenta un piano di implementazione dettagliato per i personaggi dei giochi basati sull'intelligenza artificiale con specifiche tecniche per l'integrazione di LLM, linee guida per i personaggi e meccaniche di scoperta dei servizi.

[`Compagno di note`](https://github.com/different-ai/note-companion/blob/master/CLAUDE.md) &nbsp; di &nbsp; [different-ai](https://github.com/different-ai)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Fornisce tecniche dettagliate di isolamento dello stile per i plugin di Obsidian utilizzando Tailwind con un prefisso personalizzato per prevenire conflitti di stile e pratici passaggi per la risoluzione dei problemi.

[`Pareto Mac`](https://github.com/ParetoSecurity/pareto-mac/blob/main/CLAUDE.md) &nbsp; di &nbsp; [ParetoSecurity](https://github.com/ParetoSecurity)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;GPL-3.0
Serve come guida allo sviluppo per lo strumento di controllo della sicurezza di Mac con istruzioni di compilazione, linee guida per i contributi, procedure di test e documentazione del flusso di lavoro.

[`SteadyStart`](https://github.com/steadycursor/steadystart/blob/main/CLAUDE.md) &nbsp; di &nbsp; [steadycursor](https://github.com/steadycursor)
Istruzioni chiare e dirette su stile, autorizzazioni, "ruolo" di Claude, comunicazioni e documentazione delle sessioni di Claude Code per tenere aggiornati gli altri membri del team.

### Scaffolding di progetti e MCP

[`Memoria di base`](https://github.com/basicmachines-co/basic-memory/blob/main/CLAUDE.md) &nbsp; di &nbsp; [basicmachines-co](https://github.com/basicmachines-co)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;AGPL-3.0
Presenta un innovativo framework di collaborazione uomo-IA con il Model Context Protocol per la comunicazione bidirezionale LLM-markdown e una struttura di conoscenza flessibile per progetti complessi.

[`claude-code-mcp-enhanced`](https://github.com/grahama1970/claude-code-mcp-enhanced/blob/main/CLAUDE.md) &nbsp; di &nbsp; [grahama1970](https://github.com/grahama1970)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Fornisce istruzioni dettagliate ed enfatiche che Claude deve seguire come agente di codifica, con una guida ai test, esempi di codice e controlli di conformità.

[`Perplessità MCP`](https://github.com/Family-IT-Guy/perplexity-mcp/blob/main/CLAUDE.md) &nbsp; di &nbsp; [Family-IT-Guy](https://github.com/Family-IT-Guy)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;ISC
Offre istruzioni di installazione chiare e passo-passo con più opzioni di configurazione, una guida dettagliata alla risoluzione dei problemi e una panoramica concisa dell'architettura del protocollo MCP.

<br>

## Documentazione ufficiale 🏛️

> Collegamenti ad alcune delle fantastiche documentazioni e risorse di Anthropic relative a Claude Code

<!--lint disable double-link-->

[`Documentazione di Anthropic`](https://docs.anthropic.com/en/docs/claude-code) &nbsp; di &nbsp; [Anthropic](https://github.com/anthropics)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;&copy;
La documentazione ufficiale di Claude Code, che include istruzioni di installazione, linee guida per l'uso, riferimenti API, tutorial, esempi, un sacco di informazioni che non elencherò singolarmente. Come Claude Code, la documentazione viene aggiornata di frequente.

[`Avvii rapidi di Anthropic`](https://github.com/anthropics/anthropic-quickstarts/blob/main/CLAUDE.md) &nbsp; di &nbsp; [Anthropic](https://github.com/anthropics)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Offre guide allo sviluppo complete per tre distinti progetti dimostrativi basati sull'intelligenza artificiale con flussi di lavoro standardizzati, rigide linee guida sullo stile del codice e istruzioni per la containerizzazione.

[`Azioni GitHub di Claude Code`](https://github.com/anthropics/claude-code-action/tree/main/examples) &nbsp; di &nbsp; [Anthropic](https://github.com/anthropics)  &nbsp;&nbsp;⚖️&nbsp;&nbsp;MIT
Integrazione ufficiale delle azioni di GitHub per Claude Code con esempi e documentazione per l'automazione dei flussi di lavoro basati sull'intelligenza artificiale nelle pipeline CI/CD.

## Contribuire 🌻

### 🚀 **[Invia una nuova risorsa qui!](https://github.com/hesreallyhim/awesome-claude-code/issues/new?template=submit-resource.yml)**

È facile! Basta fare clic sul link qui sopra e compilare il modulo. Non è richiesta alcuna conoscenza di Git: il nostro sistema automatizzato si occupa di tutto per te.

**Accogliamo con particolare favore:**

- Risorse comprovate ed efficaci che seguono le migliori pratiche e che potrebbero essere persino in uso in produzione
- Flussi di lavoro innovativi, creativi o sperimentali che spingono i confini delle capacità di Claude Code
- Librerie e strumenti aggiuntivi basati su Claude Code
- Applicazioni di Claude Code al di fuori del contesto tradizionale di "assistente di codifica" (CI/CD, test, documentazione, dev-ops, ecc.)

Consulta [CONTRIBUTING.md](CONTRIBUTING.md) per la guida completa all'invio e il processo di revisione.

Per suggerimenti sul repository stesso, [apri un problema generale](https://github.com/hesreallyhim/awesome-claude-code/issues/new).

Questo progetto viene rilasciato con un [Codice di condotta per i contributori](code-of-conduct.md). Partecipando, accetti di rispettarne i termini.

### Una nota sulle licenze

Poiché la semplice elencazione di un collegamento ipertestuale non si qualifica come ridistribuzione, la licenza della fonte originale non è rilevante per la sua inclusione. Tuttavia, per i posteri e per comodità, ospitiamo copie di tutte le risorse la cui licenza lo consente. Pertanto, includi le informazioni sulla licenza della risorsa. Inoltre, prendi nota: _se non includi una LICENZA nel tuo repository GitHub, per impostazione predefinita è completamente protetto da copyright e la ridistribuzione non è consentita_. Quindi, se intendi creare un progetto open source, è fondamentale scegliere una delle tante licenze open source disponibili. Questo è solo un promemoria che senza una LICENZA, il tuo progetto non è open source (è semplicemente disponibile il codice sorgente); ovviamente può comunque essere incluso in questo elenco, ma questo avviso ha lo scopo di informare i lettori sulle regole predefinite relative a GitHub e ai file di LICENZA. Consulta [qui](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/licensing-a-repository) per maggiori dettagli.

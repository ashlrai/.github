<p align="center">
  <a href="https://ashlr.ai"><img src="./assets/logos/ashlar-mark.png" alt="Ashlr.AI keystone logo" width="88" height="88"></a>
</p>

<h1 align="center">Ashlr.AI</h1>

<p align="center">
  <b>Forward-deployed software and AI engineering.</b><br>
  We embed with enterprise, government-contractor, and funded product teams to connect critical
  systems,<br>automate the work between them, and ship production software the organization can
  operate and own.
</p>

<p align="center">
  <a href="https://ashlr.ai">ashlr.ai</a> &nbsp;/&nbsp;
  <a href="https://ashlr.ai/work">Selected work</a> &nbsp;/&nbsp;
  <a href="https://ashlr.ai/developer-tools">Developer tools</a> &nbsp;/&nbsp;
  <a href="https://ashlr.ai/contact">Build with us</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/based_in-Virginia,_USA-1A2B3C?style=flat" alt="Based in Virginia, USA">
  <img src="https://img.shields.io/badge/engineering-US--based-2563EB?style=flat" alt="US-based engineering">
  <img src="https://img.shields.io/badge/open_source-MIT-2563EB?style=flat" alt="Open source under MIT">
</p>

---

The repositories here are the tools we build for ourselves, released under MIT because the same
problems show up in every engagement. Product work and client work inform each other: the tools
sharpen the systems we deliver, and real operating problems shape what we build next.

## Phantom. Give agents access. Keep your keys.

<p>
  <a href="https://github.com/ashlrai/phantom-secrets"><img src="https://img.shields.io/github/stars/ashlrai/phantom-secrets?style=flat&amp;label=GitHub%20stars&amp;color=2563eb" alt="Phantom GitHub stars"></a>
</p>

Our most-starred public project tackles a fundamental problem: agents need to use services, but real
credentials shouldn't have to live in their context. Phantom combines scoped `phm_` placeholders, a
local proxy, and MCP tools to handle supported API work while keeping real credentials out of agent
context. It works with Claude Code, Cursor, Windsurf, and Codex.

<p>
  <a href="https://phm.dev"><img src="https://raw.githubusercontent.com/ashlrai/phantom-secrets/main/apps/web/public/og-image.png" alt="Phantom's blue ghost mascot beside the message: Delegate supported API work to AI. A terminal preview shows phantom init and phantom exec." width="100%"></a>
</p>

**[Explore Phantom](https://phm.dev)** · [Source](https://github.com/ashlrai/phantom-secrets) · [Documentation](https://github.com/ashlrai/phantom-secrets/blob/main/docs/README.md)

## Ashlr Hub is where we're going.

**Our flagship: a local command center for agentic engineering.** Bring projects, coding agents, MCP
tools, and experiment evidence into one workflow. Hub is the front door to the Ashlr ecosystem—and
the local kernel behind our Ashlrverse work.

<p align="center">
  <a href="https://github.com/ashlrai/ashlr-hub">
    <img src="./assets/engineering-ecosystem.svg" alt="Ashlr Hub is our flagship command center. Phantom protects credentials, Stack connects services, ashlrcode brings agents to the terminal, and Measurably improves prompts. Independent tools with a shared engineering direction." width="100%">
  </a>
</p>

The ambition is simple: give an engineering system an objective, let it explore competing
approaches, evaluate what it produces, and learn from the results. We're building toward that
through local tools, inspectable evidence, and deliberate human control.

- **A place to operate.** A CLI and dashboard for projects, agent workflows, and tools.
- **A place to experiment.** Ashlrverse source tooling for generating, evaluating, and retaining
  competing code variants.
- **A place to connect.** Independently useful projects, brought into a shared engineering workflow.

**[Explore Hub](https://github.com/ashlrai/ashlr-hub)** · [Quickstart](https://github.com/ashlrai/ashlr-hub/blob/master/docs/QUICKSTART.md) · [Ashlrverse guide](https://github.com/ashlrai/ashlr-hub/blob/master/docs/ASHLR-UNIVERSE.md) · [Roadmap and north star](https://github.com/ashlrai/ashlr-hub/blob/master/docs/NORTH-STAR.md)

<sub>Hub's guides distinguish released capabilities, source experiments, and the larger roadmap. The
ecosystem map above describes our direction; it does not imply every integration is already
available.</sub>

## Engineering beyond the prompt.

The rest of the system, one useful tool at a time. Everything below is public and MIT-licensed.

| Tool | What it does | Where |
|---|---|---|
| **Morphkit** | From React to a native iOS project. Turn a React and TypeScript app into a SwiftUI project, with the tooling to plan the conversion and finish the generated app. | [`morphkit`](https://github.com/ashlrai/morphkit) · [morphkit.dev](https://morphkit.dev) |
| **Ashlr Plugin** | Every tool call, line-itemized. Token-efficient read, search, edit, and inspect tools for Claude Code and Codex, with visible context usage. | [`ashlr-plugin`](https://github.com/ashlrai/ashlr-plugin) · [plugin.ashlr.ai](https://plugin.ashlr.ai) |
| **BinShield** | Your npm supply chain, x-rayed. Inspect install scripts and native package binaries for risky behavior before they land in your build — as a CLI or a CI policy gate. | [`binshield`](https://github.com/ashlrai/binshield) · [binshield.dev](https://binshield.dev) |
| **WebFetch** | Images your agent can actually ship. Federated image search with license-aware ranking and source metadata, over MCP, CLI, and HTTP. | [`webfetch`](https://github.com/ashlrai/webfetch) · [getwebfetch.com](https://getwebfetch.com) |
| **Ashlr Stack** | Bring your infrastructure into the conversation. Provision services and work with your development stack through a CLI and MCP tools. Phantom handles the credentials. | [`ashlr-stack`](https://github.com/ashlrai/ashlr-stack) · [stack.ashlr.ai](https://stack.ashlr.ai) |
| **ashlrcode** | Your terminal. Your models. Your workflow. A multi-provider coding agent with MCP tools, saved sessions, plan mode, and sub-agent coordination. | [`ashlrcode`](https://github.com/ashlrai/ashlrcode) · [ashlr.ai/ashlrcode](https://ashlr.ai/ashlrcode) |

**Also in the open:** [`ashlr-core-efficiency`](https://github.com/ashlrai/ashlr-core-efficiency)
(the token-efficiency primitives behind the plugin),
[`ashlr-md`](https://github.com/ashlrai/ashlr-md) (an AI-native Markdown app for macOS),
[`locus`](https://github.com/ashlrai/locus) (an identity plane so agents never act in the wrong
tenant), and [`lexicon`](https://github.com/ashlrai/lexicon) (a personal lexicon for
voice-to-agents).

**[Browse all public repositories →](https://github.com/orgs/ashlrai/repositories?type=public)**

## Products we build, run, and sell.

| Product | | |
|---|---|---|
| **Ashlr BI** | A clearer view of your business finances. | [ashlrbi.com](https://ashlrbi.com) |
| **Koala Finance** | Your money, understood. | [trykoala.ai](https://trykoala.ai) |
| **Triage** | Your inbox, sorted. | [trytriage.ai](https://trytriage.ai) |
| **Probe** | Know more than everyone else. | [tryprobe.io](https://tryprobe.io) |
| **Measurably** | Make every prompt more deliberate. | [measurably.dev](https://measurably.dev) |

**[Explore the portfolio →](https://ashlr.ai/products)**

## Digital Masonry, in the real world.

Engagements run from executive discovery through custom build to embedded partnership, with named
delivery accountability, explicit controls, and client ownership. Three published examples:

- **[Cash Margin Partners](https://ashlr.ai/work/cash-margin-partners-platform)** — a multi-tenant
  retail platform connecting commerce, accounting, payments, forecasting, and inventory recovery.
  Five weeks from contract signature to production; the diagnostic engine launched with 269 passing
  specifications.
- **[hyrUP](https://ashlr.ai/work/hyrup-operating-intelligence)** — operating data connected into
  executive dashboards and comparative market intelligence, shaped around the questions leadership
  actually asks.
- **[JMU ETA & GCFE](https://ashlr.ai/work/jmu-eta-ai-education)** — guest instruction for two
  Entrepreneurship Through Acquisition cohorts on assessing AI opportunities and turning them into
  responsible implementation plans, taught from systems already in production.

**[See selected work →](https://ashlr.ai/work)**

## Work with us.

**Mason Wyatt**, **Mason Scofield**, and **Evan Deloria** lead AshlrAI, Inc., a Virginia
C-corporation incorporated March 2, 2026 and headquartered in Virginia, USA.

Have a hard engineering problem, an integration that keeps slipping, or a contribution in mind?
Issues and pull requests are welcome on every public repository above.

**[Talk to us](https://ashlr.ai/contact)** · [support@ashlr.ai](mailto:support@ashlr.ai) ·
[Meet the team](https://ashlr.ai/about) ·
[LinkedIn](https://www.linkedin.com/company/ashlrai/)

<p align="center"><sub>© 2026 AshlrAI, Inc. · Virginia, USA · Digital Masonry.</sub></p>

<!--
PINNED REPOSITORY STRATEGY
==========================
Pin exactly six, in this order. GitHub renders pins in the order you select them, and the first
three carry the most weight on desktop.

1. phantom-secrets  — Most-starred public repo in the org (16, verified Sep 22 2026) and the
                      clearest one-sentence problem ("stop agents leaking your API keys"). Best
                      chance of a visitor understanding what we do within five seconds.
2. ashlr-hub        — The flagship and the statement of direction. Tells a returning visitor where
                      the org is going, not just what it has shipped.
3. binshield        — Supply-chain security. This is the repo that lands with the enterprise and
                      government-contractor audience the landing page is aimed at, and it doubles as
                      a credibility signal for anyone evaluating us on security.
4. morphkit         — Tied for second-most-starred (5, level with ashlrcode) and the most visually
                      distinctive project (React → native SwiftUI). Good breadth signal: we are not
                      only an agent-tooling shop.
5. ashlr-plugin     — Proof that we ship inside the tools working engineers use daily (Claude Code,
                      Codex). Strong developer-audience resonance.
6. webfetch         — Rounds out the agent-infrastructure story (credentials → supply chain →
                      assets) and demonstrates range across languages and surfaces.

Reasoning for the ordering: lead with proof (stars + sharpest pitch), then direction (Hub), then the
enterprise-credibility repo, then breadth. Deliberately not pinned: homebrew-* taps (infrastructure,
no narrative), the .github repo itself (meta), and research repos such as codedreamer,
mechanistic-interpretability, and creatures — interesting, but they dilute a commercial first
impression. Revisit the pins whenever a repo's star count meaningfully overtakes another's, or when
Hub reaches a public milestone worth leading with.

STAR COUNTS AT LAST EDIT (gh repo list ashlrai, Sep 22 2026)
phantom-secrets 16 · morphkit 5 · ashlrcode 5 · ashlr-hub 3 · ashlr-plugin 3 · binshield 3 ·
webfetch 3 · ashlr-md 3 · creatures 3 · ashlr-stack 2 · ashlr-core-efficiency 2 · lexicon 1
-->

# Best Claude Code Skills (2026)

**42 skill collections and specialist skills, organised by the work you need to do.** Compare what each one adds, the stack it assumes, and its installation instructions. Start with the task table, then compare close alternatives before installing.

A Claude Code skill is a folder with a `SKILL.md` file that teaches the agent a reusable task. This list covers documents, software development, mobile apps, security, data, research and marketing. It also identifies collections packaged as plugins and tools that include a skill.

**Source and setup review: 28 October 2026.** Maintained by [Gabe Bouslov](https://gabebouslov.com). Repository activity is listed separately below.

Looking for an awesome Claude Code skills list or a GitHub skills directory? This library selects by task and setup, rather than by star count. For packages that combine skills with agents, hooks or connectors, see [Best Claude Code Plugins](https://github.com/gbouslov/best-claude-code-plugins).

## Choose a starting point

| Your next task | Start here | Why this one |
|---|---|---|
| Create or edit a PDF, Word document, spreadsheet or slide deck | [Anthropic Skills](https://github.com/anthropics/skills) | The vendor's document skills and examples are in one place. Check the per-skill license. |
| Improve React or Next.js performance | [Vercel Agent Skills](https://github.com/vercel-labs/agent-skills) | Targets waterfalls, bundles, rendering and component patterns. |
| Clarify a feature before building it | [Matt Pocock Skills](https://github.com/mattpocock/skills) | Focused workflows for questioning requirements, writing specs and planning work. |
| Add a consistent development and testing process | [Superpowers](https://github.com/obra/superpowers) | Connects requirements, planning, implementation and verification into a workflow. |
| Ship an Expo app | [Expo Skills](https://github.com/expo/skills) | Expo Router, SDK upgrades and EAS delivery fit the actual stack. |
| Review code for security issues | [Trail of Bits Skills](https://github.com/trailofbits/skills) | Workflows for audit context, differential review and specialised security analysis. |
| Work with an Obsidian vault | [Obsidian Skills](https://github.com/kepano/obsidian-skills) | Covers the vault's Markdown, Bases and Canvas formats. |
| Improve copy, conversion or marketing experiments | [Marketing Skills](https://github.com/coreyhaines31/marketingskills) | A focused collection of marketing jobs with product context supplied by you. |

Browse: [web development](#claude-code-skills-for-web-development) · [web and UI design](#claude-code-skills-for-web-design-and-ui-design) · [app development](#claude-code-skills-for-app-development) · [data and ML](#data-databases-and-machine-learning) · [cloud](#cloud-and-infrastructure) · [security and browsers](#security-debugging-and-browser-testing) · [developers](#claude-code-skills-for-developers) · [documents and research](#documents-research-and-creative-work) · [marketing and automation](#marketing-business-and-automation) · [install and list skills](#install-and-list-claude-code-skills).

## Claude Code skills for web development

| Collection | What it adds | Stack and setup |
|---|---|---|
| [Vercel Agent Skills](https://github.com/vercel-labs/agent-skills) | React performance, composition patterns, interface review and Vercel optimisation. Choose it when the change is in your web application's code or deployment. | React/Next.js and related web workflows. [Setup](https://github.com/vercel-labs/agent-skills/blob/main/README.md). |
| [WordPress Agent Skills](https://github.com/WordPress/agent-skills) | Routes WordPress work into block, theme, REST API, WP-CLI and permissions workflows. Useful for Gutenberg development and existing sites. | WordPress. [Setup](https://github.com/WordPress/agent-skills/blob/trunk/README.md). |
| [Sanity Agent Toolkit](https://github.com/sanity-io/agent-toolkit) | Content modelling, schemas, GROQ and Studio guidance, with separate skills and MCP options. | Sanity projects. [Setup](https://github.com/sanity-io/agent-toolkit/blob/main/README.md). |
| [Stripe AI](https://github.com/stripe/ai) | Stripe integration guidance in a repository that also contains AI SDK and MCP resources. Follow its agent-skills instructions for the reusable guidance. | Stripe integrations. [Setup](https://github.com/stripe/ai/blob/main/README.md). |
| [Resend Skills](https://github.com/resend/resend-skills) | Separate workflows for sending email, React Email, CLI work and agent inboxes. Useful when delivery and inbox behaviour are part of the application. | Resend and related email tooling; live operations need the relevant service access. [Setup](https://github.com/resend/resend-skills/blob/main/README.md). |

## Claude Code skills for web design and UI design

For an existing interface, start with Vercel's `web-design-guidelines` for a review and `composition-patterns` for React component structure. For WordPress block or theme work, use the WordPress collection above. These are different jobs: supply your reference pages, design system and target screens so the agent can apply the right guidance.

| Design task | Skill to choose | Give it a concrete brief |
|---|---|---|
| Review a web UI | Vercel `web-design-guidelines` | “Review this checkout for accessibility and interaction issues.” |
| Refactor a React component API | Vercel `composition-patterns` | “Replace these boolean props with composable components.” |
| Build a Gutenberg block or WordPress theme | WordPress Agent Skills | “Make this block match the existing site's spacing and typography.” |

Try these task briefs with your own files. Follow the linked collection's setup instructions in the web-development table.

## Claude Code skills for app development

| Collection | What it adds | Stack and setup |
|---|---|---|
| [Expo Skills](https://github.com/expo/skills) | Expo Router interfaces, SDK upgrades, builds and updates. The first stop for an Expo-specific task. | Expo and EAS. [Setup](https://github.com/expo/skills/blob/main/README.md). |
| [Callstack Agent Skills](https://github.com/callstackincubator/agent-skills) | React Native performance, navigation, testing, migration and native-library workflows. Choose it for native/mobile concerns beyond Expo delivery. | React Native; task-specific native tooling. [Setup](https://github.com/callstackincubator/agent-skills/blob/main/README.md). |
| [React Native Community Skills](https://github.com/react-native-community/skills) | Focused upgrade guidance and migration to the Strict TypeScript API. Useful for a version transition in a CLI project. | React Native CLI projects. [Setup](https://github.com/react-native-community/skills/blob/main/README.md). |
| [Flutter Agent Plugins](https://github.com/flutter/agent-plugins) | Flutter UI, architecture, widget tests, integration tests and responsive layouts. Skills are distributed with MCP configuration and rules in plugin bundles. | Flutter; follow the official host-specific installation guide. [Setup](https://github.com/flutter/agent-plugins/blob/main/README.md). |
| [Dart Skills](https://github.com/dart-lang/skills) | Language-level CLI, tests, package fixes, FFI, native assets and documentation. Useful outside Flutter UI work too. | Dart. [Setup](https://github.com/dart-lang/skills/blob/main/README.md). |
| [iOS Simulator Skill](https://github.com/conorluddy/ios-simulator-skill) | Build and simulator workflows using Xcode tools and semantic navigation. | Apple silicon Mac, macOS 15+, Xcode 26+, Python 3.12+ and idb. Install the nested skill or plugin as documented. [Setup](https://github.com/conorluddy/ios-simulator-skill/blob/main/README.md). |

## Data, databases and machine learning

| Collection | What it adds | Stack and setup |
|---|---|---|
| [Supabase Agent Skills](https://github.com/supabase/agent-skills) | Postgres performance, row-level security and Supabase authentication, SSR and migrations. | Postgres/Supabase. [Setup](https://github.com/supabase/agent-skills/blob/main/README.md). |
| [Prisma Skills](https://github.com/prisma/skills) | Prisma CLI, client API, adapters, database setup and version migration. Choose it when the question is in the ORM layer. | Version-sensitive: new ORM setup targets Prisma 8; existing 6/7 projects need their matching guidance. [Setup](https://github.com/prisma/skills/blob/main/README.md). |
| [Neon Agent Skills](https://github.com/neondatabase/agent-skills) | Neon-specific database branches, authentication and other platform workflows. | Neon Postgres. [Setup](https://github.com/neondatabase/agent-skills/blob/main/README.md). |
| [ClickHouse Agent Skills](https://github.com/ClickHouse/agent-skills) | Analytical table design, primary keys, joins, batching and chDB workflows. Choose it for analytical workloads. | ClickHouse/chDB. [Setup](https://github.com/ClickHouse/agent-skills/blob/main/README.md). |
| [Hugging Face Skills](https://github.com/huggingface/skills) | Hub models and datasets, model selection, training jobs and deployment. | Hugging Face tooling; model, compute and account needs depend on the task. [Setup](https://github.com/huggingface/skills/blob/main/README.md). |
| [Apify Agent Skills](https://github.com/apify/agent-skills) | Distinguishes running an existing Actor from building one or integrating it into an application. | Apify; service execution may be billed. [Setup](https://github.com/apify/agent-skills/blob/main/README.md). |
| [Firecrawl Skills](https://github.com/firecrawl/skills) | Web extraction, CLI use, application integration and research workflows as separate choices. | Firecrawl tooling and service access where required. [Setup](https://github.com/firecrawl/skills/blob/main/README.md). |

## Cloud and infrastructure

| Collection | What it adds | Stack and setup |
|---|---|---|
| [Cloudflare Skills](https://github.com/cloudflare/skills) | Guidance for building Workers and stateful applications, with product-specific routing and Wrangler workflows. | Cloudflare projects using Workers or Wrangler. [Setup](https://github.com/cloudflare/skills/blob/main/README.md). |
| [Microsoft Skills](https://github.com/microsoft/skills) | Azure SDK and Foundry guidance organised by language and product. The repository also contains agents, plugins and MCP configuration. | Microsoft and Azure projects; select the relevant component. [Setup](https://github.com/microsoft/skills/blob/main/README.md). |
| [HashiCorp Agent Skills](https://github.com/hashicorp/agent-skills) | Terraform and Packer guidance available as product bundles or individual skills. | Terraform or Packer projects with their matching tooling. [Setup](https://github.com/hashicorp/agent-skills/blob/main/README.md). |

## Security, debugging and browser testing

| Collection | What it adds | Stack and setup |
|---|---|---|
| [Trail of Bits Skills](https://github.com/trailofbits/skills) | Audit context, differential review, smart-contract and agentic GitHub Actions security workflows. | Specialist plugins; select the relevant analysis. [Setup](https://github.com/trailofbits/skills/blob/main/README.md). |
| [Sentry Skills](https://github.com/getsentry/skills) | Engineering code review, simplification, debugging and security workflows, including Django-specific checks. | Sentry's engineering conventions and task-specific tooling. [Setup](https://github.com/getsentry/skills/blob/main/README.md). |
| [Playwright Skill](https://github.com/lackeyjb/playwright-skill) | Writes and runs browser automation for the task at hand. Useful when the browser check needs a custom script. | Playwright and browser dependencies. [Setup](https://github.com/lackeyjb/playwright-skill/blob/main/README.md). |
| [FFUF Skill](https://github.com/jthack/ffuf_claude_skill) | Focused web fuzzing and endpoint-discovery guidance. | ffuf, a compatible host setup and a target you are authorised to test. [Setup](https://github.com/jthack/ffuf_claude_skill/blob/main/README.md). |
| [Vercel Agent Browser](https://github.com/vercel-labs/agent-browser) | A browser CLI with a bundled skill and a snapshot/element-reference interaction model. | Tool plus skill; install the browser tooling as documented. [Setup](https://github.com/vercel-labs/agent-browser/blob/main/README.md). |

## Claude Code skills for developers

| Collection | What it adds | Packaging and setup |
|---|---|---|
| [Superpowers](https://github.com/obra/superpowers) | An opinionated process from requirements and plans through implementation and verification. Choose it for a consistent way to approach whole tasks. | Workflow collection. [Setup](https://github.com/obra/superpowers/blob/main/README.md). |
| [Matt Pocock Skills](https://github.com/mattpocock/skills) | Focused questioning, specifications, tickets and design discussions. Choose a named workflow such as `grill-me` or `to-spec`. | Individual workflows; adapt issue tracking and document locations to your project. [Setup](https://github.com/mattpocock/skills/blob/main/README.md). |
| [ECC (Everything Claude Code)](https://github.com/affaan-m/ECC) | Skills alongside memory, hooks, rules and agent configuration. Choose it when you want to adopt an environment as well as reusable task guidance. | Broader configuration system; upstream offers guided setup. [Setup](https://github.com/affaan-m/ECC/blob/main/README.md). |
| [wshobson Agents](https://github.com/wshobson/agents) | Modular developer bundles combining agents, commands and skills. | Plugin bundles; select the language or task you need. [Setup](https://github.com/wshobson/agents/blob/main/README.md). |
| [Planning with Files](https://github.com/OthmanAdi/planning-with-files) | Keeps the plan, findings and progress on disk so a long task can resume after interruption. | Persistent task planning with host-specific hooks. [Setup](https://github.com/OthmanAdi/planning-with-files/blob/master/README.md). |
| [Claude-Codex Skills](https://github.com/levnikolaevich/claude-code-skills) | Discovery, architecture, delivery planning and verification, grouped into suites with explicit checks and reports. | Standalone skills and suites. [Setup](https://github.com/levnikolaevich/claude-code-skills/blob/master/README.md). |
| [Roost](https://github.com/Beakpoint-Insights/roost) | Shape an epic, implement it in slices, review the result and prepare a rollout with human checkpoints. Choose it when the workflow needs to continue through release preparation. | Plugin of skills; team config, GitHub CLI and a supported tracker/test setup. App QA uses Playwright MCP and a local stack. [Setup](https://github.com/Beakpoint-Insights/roost#install). |

## Documents, research and creative work

| Collection | What it adds | Stack and setup |
|---|---|---|
| [Anthropic Skills](https://github.com/anthropics/skills) | Document creation/editing plus examples and a template for writing a skill. | The document skills are source-available; check their individual licenses. [Setup](https://github.com/anthropics/skills/blob/main/README.md). |
| [Scientific Agent Skills](https://github.com/K-Dense-AI/scientific-agent-skills) | Bioinformatics, chemistry, imaging, statistics and scientific communication workflows. | Scientific packages and data access vary by discipline. [Setup](https://github.com/K-Dense-AI/scientific-agent-skills/blob/main/README.md). |
| [Obsidian Skills](https://github.com/kepano/obsidian-skills) | Markdown, Bases, JSON Canvas, CLI and Defuddle workflows for vault work. | Obsidian file formats and tooling. [Setup](https://github.com/kepano/obsidian-skills/blob/main/README.md). |
| [Remotion Skills](https://github.com/remotion-dev/skills) | Programmatic video creation, rendering, captions, multimedia and upgrade workflows. | Remotion. [Setup](https://github.com/remotion-dev/skills/blob/main/README.md). |
| [Academic Writing Skills](https://github.com/WenyuChiou/academic-writing-skills) | Plan or revise a research manuscript and review whether its argument matches the supplied sources. Choose it for paper writing rather than scientific computation. | Two skills in a plugin: writing and paper review. Supply the active manuscript, sources and venue requirements. [Setup](https://github.com/WenyuChiou/academic-writing-skills#install-and-use). |

## Marketing, business and automation

| Collection | What it adds | Packaging and setup |
|---|---|---|
| [Marketing Skills](https://github.com/coreyhaines31/marketingskills) | Copy, conversion, experimentation, analytics and SEO workflows. Supply the actual product, audience and customer context. | Marketing task collection. [Setup](https://github.com/coreyhaines31/marketingskills/blob/main/README.md). |
| [Anthropic Knowledge Work Plugins](https://github.com/anthropics/knowledge-work-plugins) | Sales, marketing, product, support and other role-based workflows. | Bundles of skills, connectors, commands and subagents; follow the documented Claude Code route. [Setup](https://github.com/anthropics/knowledge-work-plugins/blob/main/README.md). |
| [n8n Skills](https://github.com/czlonkowski/n8n-skills) | Expressions, nodes, workflow patterns and validation. Useful for constructing or troubleshooting a workflow. | Community collection designed around its author's separate `n8n-mcp` server. [Setup](https://github.com/czlonkowski/n8n-skills/blob/main/README.md). |
| [Claude Skills by alirezarezvani](https://github.com/alirezarezvani/claude-skills) | Engineering, marketing, operations and advisory workflows in one cross-functional library. | Distinguishes skills, agents and personas; choose by task. [Setup](https://github.com/alirezarezvani/claude-skills/blob/main/README.md). |

## Compare close alternatives

| If you are choosing between… | Use the first for… | Use the second for… |
|---|---|---|
| Expo / Callstack | Expo Router, Expo SDK and EAS delivery | React Native performance, native libraries, navigation and broader migration work |
| Supabase / Prisma | Database performance, RLS and Supabase platform workflows | ORM client, adapters, CLI and Prisma version migration |
| Supabase / Neon | Supabase/Postgres guidance and Supabase auth | Neon-specific branches, auth and platform operations |
| Postgres-focused skills / ClickHouse | Transactional application database work | Analytical schemas, query patterns and ingestion |
| Superpowers / Matt Pocock | A coordinated engineering process | A focused discussion, specification or planning task |
| A skill collection / Everything Claude Code | Reusable instructions for a chosen job | A wider setup that also changes hooks, rules and agent configuration |
| Playwright Skill / Agent Browser | Custom browser automation scripts | A browser CLI driven by snapshots and element references |
| Obsidian Skills / Planning with Files | Reading and editing vault formats | Preserving a task's plan, findings and progress |
| Superpowers / Roost | A general development process from brainstorming to verification | A configured epic-to-release process tied to your team's tracker and rollout checkpoints |
| Scientific Agent Skills / Academic Writing Skills | Discipline-specific analysis, scientific libraries and data workflows | Building and revising the manuscript's argument from supplied sources |

## Official sources and community marketplaces

For Anthropic's own examples and document skills, use [anthropics/skills](https://github.com/anthropics/skills). Stack publishers such as Vercel, Expo, WordPress and Cloudflare maintain their own specialist collections; community authors maintain the independent workflows listed alongside them.

A marketplace is an installation catalog. Anthropic's document-skills marketplace, the official Claude Code plugin marketplace, and community marketplaces such as Trail of Bits distribute different bundles. Check the publisher and selected package: adding a marketplace does not itself install every skill. See the [official marketplace guide](https://code.claude.com/docs/en/plugins/install).

## Skills and plugins, compared

| You need… | Use… | What changes |
|---|---|---|
| Reusable instructions for a task | A skill | Adds a `SKILL.md` workflow and optional supporting files |
| Several components installed together | A plugin | Can bundle skills, agents, hooks and connectors |
| Access to a database, browser or service | An MCP server or another tool integration | Adds callable tools or data access; account setup may be required |
| An independent worker with its own instructions | A subagent | Runs a bounded task in its own context |

Some entries above are skills distributed inside plugins. Choose the skills-only route when upstream offers it and that is all your task needs; choose the plugin when you need its other components. Compare actual bundles in [Best Claude Code Plugins](https://github.com/gbouslov/best-claude-code-plugins).

## Claude Code skills examples and best practices

For a small workflow of your own, create `.claude/skills/review-change/SKILL.md` in the project:

```markdown
---
name: review-change
description: Review a proposed change against its acceptance criteria before merging.
---

Read the acceptance criteria and changed files within the current repository.
Explain which criteria the change satisfies, identify missing checks, and
suggest the next verification. Report findings without editing files or
running deployment commands.
```

Invoke it with `/review-change`. Make the description specific, keep long references in supporting files, and check the workflow on realistic tasks. Compare its results with and without the skill before relying on it; the [official evaluation guide](https://agentskills.io/skill-creation/evaluating-skills) describes that process. The [Claude Code skills guide](https://code.claude.com/docs/en/skills) covers frontmatter and invocation controls.

## Install and list Claude Code skills

Follow the linked project's setup instructions. Repositories distribute skills in different ways: some are plugin marketplaces, some support the skills CLI, and some document copying an individual folder.

For Anthropic's document skills, run these commands **inside Claude Code**:

```text
/plugin marketplace add anthropics/skills
/plugin install document-skills@anthropic-agent-skills
```

For a skill you author or copy manually, the project location is `.claude/skills/<skill-name>/SKILL.md`; the personal location is `~/.claude/skills/<skill-name>/SKILL.md`. Project scope makes a shared workflow travel with the repository. Personal scope makes it available across your projects. The [official skills documentation](https://code.claude.com/docs/en/skills) explains discovery, invocation and configuration.

Read the instructions and accompanying scripts before enabling a third-party skill. For a shared workflow, keep the chosen version and setup instructions with the project. [Contributions](CONTRIBUTING.md) should link directly to the project's current installation instructions.

### Install a specific skill by task

These are upstream-documented commands to run in your terminal. The `skills` CLI uses Node/npm; check the installer prompts for your agent and project versus global scope.

| Your task | Command | Scope of the choice |
|---|---|---|
| Postgres query performance | `npx skills add supabase/agent-skills --skill supabase-postgres-best-practices` | SQL-focused skill; separate from the broader Supabase platform skill |
| WordPress plugin development | `npx skills add WordPress/agent-skills --skill wp-plugin-development` | One WordPress workflow |
| Prisma project setup | `npx skills add prisma/skills --skill prisma-orm-setup` | New setup; review its version policy before changing an existing app |
| Firecrawl in an application | `npx skills add firecrawl/skills --skill firecrawl-build` | Integration guidance; session scraping and research are separate skills |
| Persistent task planning | `npx skills add OthmanAdi/planning-with-files --skill planning-with-files -g` | The named planning skill, installed globally |

### List available and installed skills

In current Claude Code, open `/skills` to manage skill visibility, or type `/` to browse invocable skills and commands. Ask `What skills are available?` to see what the session can discover. Plugin-provided skills are managed through `/plugin`; the current [skills guide](https://code.claude.com/docs/en/skills) explains the difference.

If you installed through the separate `skills` CLI, `npx skills list` lists that installer's local skills and `npx skills list -g` lists global ones. Those commands are for the installer; they are not Claude Code built-in slash commands. See the [skills CLI reference](https://github.com/vercel-labs/skills/blob/main/docs/commands.md#skills-list).

## Troubleshooting skill discovery and listing limits

If a skill does not appear, check its `SKILL.md` location, frontmatter and the active project directory. A repository containing a nested `skills/` folder is not always installable by cloning its root into your personal skills folder: use its documented route. Invoke `/skill-name` directly when it is user-invocable.

If you see “skill listing will be truncated,” inspect `/context` and `/doctor`. The listing budget can shorten descriptions even when names remain visible; the current settings include `skillListingBudgetFraction` and the fixed-character `SLASH_COMMAND_TOOL_CHAR_BUDGET` override. Review the [official listing-limit guidance](https://code.claude.com/docs/en/skills#skill-descriptions-are-cut-short) before changing them. `/skill-doctor` can identify unused skills on supported versions.

For a todo-list skill, start with Planning with Files when you want a persistent plan and progress files. For normal issue tracking, Matt Pocock's setup and triage skills connect the workflow to your chosen tracker. Pick according to where you want tasks to live.

## Alternatives and other skill directories

For a one-off instruction, a normal prompt may be enough. Put persistent project context in `CLAUDE.md`, use a hook for a deterministic event check, and use a connector when the missing capability is service access. The [Claude Code features guide](https://code.claude.com/docs/en/features-overview) explains when these mechanisms fit.

For GitHub Copilot, the [official skills setup guide](https://docs.github.com/en/copilot/how-tos/copilot-cli/customize-copilot/add-skills) supports project skills in `.github/skills/`, `.claude/skills/` or `.agents/skills/`; personal skills use `~/.copilot/skills/` or `~/.agents/skills/`. The shared `SKILL.md` format can travel between hosts, but Claude-specific hooks, tools and plugin setup still need the target host's documented equivalents. Check the collection's Codex, Cursor or Copilot route before copying a whole bundle.

For more breadth, browse [Awesome Claude Skills](https://github.com/travisvn/awesome-claude-skills), [Composio's Awesome Claude Skills](https://github.com/ComposioHQ/awesome-claude-skills) and [Awesome Claude Code](https://github.com/hesreallyhim/awesome-claude-code). Reddit discussions can supply practitioner examples; use the linked primary repositories here to check current setup, licenses and dependencies before installing a recommendation.

## About the nightly activity check

Source review dates above describe editorial checks of upstream scope and setup. The table below tracks repository metadata; a commit can change any file and does not establish when a particular skill changed.

<!-- freshness:start -->

## Repository activity

Repository metadata checked **2026-11-04 (UTC)**. Stars, latest default-branch commit and archive status describe each source repository, including shared repositories; they do not measure an individual plugin or skill release. Selection and installation guidance are reviewed separately.

| Selected resource | Repository stars | Latest repository commit (UTC) | Archived |
|---|---:|---|---|
| [Anthropic Skills](https://github.com/anthropics/skills) | 187,164 | [2026-10-28](https://github.com/anthropics/skills/commit/ca45fc496a3436251f191354091d557da31c15b5) | No |
| [Vercel Agent Skills](https://github.com/vercel-labs/agent-skills) | 33,498 | [2026-10-27](https://github.com/vercel-labs/agent-skills/commit/1a2c79d4e6c4a2283dc2c614b6538cbe1ed5ca62) | No |
| [Matt Pocock Skills](https://github.com/mattpocock/skills) | 311,661 | [2026-10-31](https://github.com/mattpocock/skills/commit/4ae2317ddb22b046e26455e4f9c9b3aaaf62212d) | No |
| [Superpowers](https://github.com/obra/superpowers) | 311,963 | [2026-11-03](https://github.com/obra/superpowers/commit/22f0b463e7a5e579904dd6211a520321035526f7) | No |
| [Expo Skills](https://github.com/expo/skills) | 4,040 | [2026-11-01](https://github.com/expo/skills/commit/a9e5bd3fa00b4e61f632e43f85da73aee1942582) | No |
| [Trail of Bits Skills](https://github.com/trailofbits/skills) | 7,986 | [2026-11-02](https://github.com/trailofbits/skills/commit/711af095215ad4ecde5b90cd1d0124b3f1c4ca9e) | No |
| [Obsidian Skills](https://github.com/kepano/obsidian-skills) | 50,707 | [2026-09-15](https://github.com/kepano/obsidian-skills/commit/3ccff5338ea700537839b21900aa5358a0402c98) | No |
| [Marketing Skills](https://github.com/coreyhaines31/marketingskills) | 58,344 | [2026-10-30](https://github.com/coreyhaines31/marketingskills/commit/88c79f6528a9347420e57ceb1fff9a60de651768) | No |
| [WordPress Agent Skills](https://github.com/WordPress/agent-skills) | 2,329 | [2026-10-21](https://github.com/WordPress/agent-skills/commit/eff3785fc28c4380d172094518c66a6a997c95d4) | No |
| [Sanity Agent Toolkit](https://github.com/sanity-io/agent-toolkit) | 196 | [2026-10-27](https://github.com/sanity-io/agent-toolkit/commit/3ed3a143f8d3413faa7790ac0b2274fd3a8a6320) | No |
| [Stripe AI](https://github.com/stripe/ai) | 2,035 | [2026-11-04](https://github.com/stripe/ai/commit/8f4c6295246b771bdfbffd4a50171f75a03507c8) | No |
| [Resend Skills](https://github.com/resend/resend-skills) | 210 | [2026-11-03](https://github.com/resend/resend-skills/commit/56d7bbf865beaafcdd21e820e16bbd02026c2647) | No |
| [Callstack Agent Skills](https://github.com/callstackincubator/agent-skills) | 1,699 | [2026-10-08](https://github.com/callstackincubator/agent-skills/commit/59e9d17446a248b21d86f078fcd0bd2d36db1ca4) | No |
| [React Native Community Skills](https://github.com/react-native-community/skills) | 28 | [2026-08-05](https://github.com/react-native-community/skills/commit/1fb0e0848fc7f4bbf42fec490338613cbc6f6b08) | No |
| [Flutter Agent Plugins](https://github.com/flutter/agent-plugins) | 3,148 | [2026-11-03](https://github.com/flutter/agent-plugins/commit/774dc2c1e7fa748b792ef4d12580ca73686f82a5) | No |
| [Dart Skills](https://github.com/dart-lang/skills) | 539 | [2026-11-03](https://github.com/dart-lang/skills/commit/3942a4f1972c488dbced9770257faaab842c711d) | No |
| [iOS Simulator Skill](https://github.com/conorluddy/ios-simulator-skill) | 1,311 | [2026-10-19](https://github.com/conorluddy/ios-simulator-skill/commit/e38b3ad5cc2585140c91b9c0f974124c3add31dc) | No |
| [Supabase Agent Skills](https://github.com/supabase/agent-skills) | 2,998 | [2026-10-02](https://github.com/supabase/agent-skills/commit/c9be0e931b7930f7d02126d04774d904c381e7d7) | No |
| [Prisma Skills](https://github.com/prisma/skills) | 79 | [2026-10-29](https://github.com/prisma/skills/commit/8ea289b730c2e89f7ff1f518af128b113d842a92) | No |
| [Neon Agent Skills](https://github.com/neondatabase/agent-skills) | 111 | [2026-11-03](https://github.com/neondatabase/agent-skills/commit/ae9babbf804e90bf42e9444ebbc9278dfcb105eb) | No |
| [ClickHouse Agent Skills](https://github.com/ClickHouse/agent-skills) | 564 | [2026-11-02](https://github.com/ClickHouse/agent-skills/commit/d3b2b5ba43a8b80c2d08858b68d53edc701b5ace) | No |
| [Hugging Face Skills](https://github.com/huggingface/skills) | 11,263 | [2026-10-29](https://github.com/huggingface/skills/commit/25910b3d0ba31a2ba102f901cdc9e008c278a69c) | No |
| [Apify Agent Skills](https://github.com/apify/agent-skills) | 2,488 | [2026-10-19](https://github.com/apify/agent-skills/commit/f22557f15941aa6a5bc7539f0408d509d4a32ab6) | No |
| [Firecrawl Skills](https://github.com/firecrawl/skills) | 145 | [2026-10-22](https://github.com/firecrawl/skills/commit/2bf714d9f45e85085036a533ceb943c8577aef2b) | No |
| [Cloudflare Skills](https://github.com/cloudflare/skills) | 3,271 | [2026-11-03](https://github.com/cloudflare/skills/commit/1f2cd0a19588e2c6197c91dd7c71729df1fb6156) | No |
| [Microsoft Skills](https://github.com/microsoft/skills) | 3,172 | [2026-11-03](https://github.com/microsoft/skills/commit/db273d02235f048331ca1597c0a98d529da1cabc) | No |
| [HashiCorp Agent Skills](https://github.com/hashicorp/agent-skills) | 911 | [2026-11-04](https://github.com/hashicorp/agent-skills/commit/5e30fa5c867ba6777c37e4206babfd08049c396f) | No |
| [Sentry Skills](https://github.com/getsentry/skills) | 1,116 | [2026-11-02](https://github.com/getsentry/skills/commit/0c464f411bdfb8d4c12314b36264d06cb2f60270) | No |
| [Playwright Skill](https://github.com/lackeyjb/playwright-skill) | 3,264 | [2026-08-14](https://github.com/lackeyjb/playwright-skill/commit/dd47a6a023e249eb1b36e9e943eab89d0900865d) | No |
| [FFUF Skill](https://github.com/jthack/ffuf_claude_skill) | 216 | [2025-10-16](https://github.com/jthack/ffuf_claude_skill/commit/50fd4af4d8bd60cfc48fd84eda1720fbd718857d) | No |
| [Vercel Agent Browser](https://github.com/vercel-labs/agent-browser) | 45,428 | [2026-11-04](https://github.com/vercel-labs/agent-browser/commit/6682da310c75bed8af340b39cc10b7f71bded155) | No |
| [ECC (Everything Claude Code)](https://github.com/affaan-m/ECC) | 296,636 | [2026-10-30](https://github.com/affaan-m/ECC/commit/b38be6a7f6350964d59328b52f0624e1d1d552d1) | No |
| [wshobson Agents](https://github.com/wshobson/agents) | 42,167 | [2026-10-30](https://github.com/wshobson/agents/commit/7e2fb559cf4b824b27f1fec49fe88f7511066d26) | No |
| [Planning with Files](https://github.com/OthmanAdi/planning-with-files) | 27,862 | [2026-11-03](https://github.com/OthmanAdi/planning-with-files/commit/0fa6c79885e14534074cb7df8535e1efa3dc7149) | No |
| [Claude-Codex Skills](https://github.com/levnikolaevich/claude-code-skills) | 587 | [2026-10-26](https://github.com/levnikolaevich/claude-code-skills/commit/bb2f0cbf343dd31acdf10e3d6af7064afd8254c7) | No |
| [Scientific Agent Skills](https://github.com/K-Dense-AI/scientific-agent-skills) | 55,997 | [2026-11-02](https://github.com/K-Dense-AI/scientific-agent-skills/commit/a25cf9ec00e2745d03f8704acf6f6919694ccd9a) | No |
| [Remotion Skills](https://github.com/remotion-dev/skills) | 6,278 | [2026-11-02](https://github.com/remotion-dev/skills/commit/c7cb2fdcacd134fb2ccb9b7a44f9ffa44e467271) | No |
| [Anthropic Knowledge Work Plugins](https://github.com/anthropics/knowledge-work-plugins) | 34,635 | [2026-11-04](https://github.com/anthropics/knowledge-work-plugins/commit/d900840716eb262e1feb17c6f4406c9ce0e06bcf) | No |
| [n8n Skills](https://github.com/czlonkowski/n8n-skills) | 6,585 | [2026-10-24](https://github.com/czlonkowski/n8n-skills/commit/e037563e101749e630e6688d121d04529fe6ee7b) | No |
| [Claude Skills by alirezarezvani](https://github.com/alirezarezvani/claude-skills) | 29,255 | [2026-11-03](https://github.com/alirezarezvani/claude-skills/commit/c85b17e1fb621ba760478baaacc4fcb9be225e74) | No |
| [Roost](https://github.com/Beakpoint-Insights/roost) | 31 | [2026-11-03](https://github.com/Beakpoint-Insights/roost/commit/be0b48565104b2d64d5435eaa779acfb4eeadbd6) | No |
| [Academic Writing Skills](https://github.com/WenyuChiou/academic-writing-skills) | 369 | [2026-10-29](https://github.com/WenyuChiou/academic-writing-skills/commit/404eb2aacbd8a4f3f0813053cf615acad8ed68aa) | No |

<!-- freshness:end -->

## Frequently asked questions

### What are Claude Code skills?

Skills package reusable task instructions in a folder containing `SKILL.md`, with optional scripts and reference files. Claude Code can load an applicable skill or invoke it by name. See the [official guide](https://code.claude.com/docs/en/skills).

### What are Claude Code plugins vs skills?

A skill teaches a workflow; a [plugin](https://code.claude.com/docs/en/plugins) can distribute it alongside commands, hooks and agents. An [MCP server](https://code.claude.com/docs/en/mcp) connects the agent to tools or data, so a workflow may need both a skill and a connector.

### What are the best Claude Code skills?

Pick the row for your next task. For documents, start with Anthropic; for React performance, Vercel; for an Expo app, Expo; for requirements discussion, Matt Pocock. Add another collection when you have a task it covers.

### Can Claude Code skills be used in Codex?

The [Agent Skills format](https://agentskills.io/) is shared across participating tools. Check the project's instructions for your agent: host-specific hooks, commands and connectors can require different setup.

### Are Claude Code skills free?

Check the specific upstream license: Anthropic's document skills are source-available, while other examples use open-source licenses. A free download can still require a paid model, service or compute. The [MIT license](LICENSE) here covers this list's original text; linked projects retain their own terms.

### How to install Claude Code skills from GitHub?

Open the repository's current setup guide and use its documented plugin, skills-CLI or manual-folder route. The install table above gives focused examples; a GitHub repository can contain several skills and optional components.

### How to install Claude Code skills globally?

Manual personal skills live in `~/.claude/skills/<skill-name>/SKILL.md`; supported installers also offer a global option. Check the project's command and installer prompts so you install for Claude Code and the scope you intend.

### How to list all skills in Claude Code?

Open `/skills` in current Claude Code and ask `What skills are available?` to inspect session discovery. The `/` menu shows invocable commands; plugin skills and installer inventories are covered in the install-and-list section above.

### Where are Claude Code skills stored?

Project skills live under `.claude/skills/` and personal skills under `~/.claude/skills/`. Plugin and managed sources have their own loading rules, so use the [official locations guide](https://code.claude.com/docs/en/skills#choose-where-skills-load) when a skill comes from another source.

### Does Claude Code use skills automatically?

Claude can load relevant skills from their descriptions, and you can invoke user-invocable skills with `/skill-name`. A skill with `disable-model-invocation: true` requires manual invocation; see the [invocation controls](https://code.claude.com/docs/en/skills#control-who-invokes-a-skill).

## Contributions and selection

Entries are selected for a specific job, a primary source with usable setup instructions, and current availability. Source links and documented scope were checked on the date above. Suggest a missing task, update a changed setup link, or explain why two entries should be distinguished in [a contribution](CONTRIBUTING.md).

Added in this review: [Roost v1.3.1](https://github.com/Beakpoint-Insights/roost/releases/tag/roost-v1.3.1) and [Academic Writing Skills v1.3.24](https://github.com/WenyuChiou/academic-writing-skills/releases/tag/v1.3.24), both released on 28 October. These are new additions to this list; Academic Writing Skills existed before this release.

Maintained by [Gabe Bouslov](https://gabebouslov.com). Star the repository to find it again; propose improvements through an issue or pull request.

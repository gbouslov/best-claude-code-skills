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
| Work with an Obsidian vault | [Obsidian Skills](https://github.com/obsidianmd/obsidian-skills) | Covers the vault's Markdown, Bases and Canvas formats. |
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
| [Obsidian Skills](https://github.com/obsidianmd/obsidian-skills) | Markdown, Bases, JSON Canvas, CLI and Defuddle workflows for vault work. | Obsidian file formats and tooling. [Setup](https://github.com/obsidianmd/obsidian-skills/blob/main/README.md). |
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

Repository metadata checked **2026-11-26 (UTC)**. Stars, latest default-branch commit and archive status describe each source repository, including shared repositories; they do not measure an individual plugin or skill release. Selection and installation guidance are reviewed separately.

| Selected resource | Repository stars | Latest repository commit (UTC) | Archived |
|---|---:|---|---|
| [Anthropic Skills](https://github.com/anthropics/skills) | 200,613 | [2026-11-16](https://github.com/anthropics/skills/commit/e4bb5d960d87126ff3b3a8af1a104b7db67560ba) | No |
| [Vercel Agent Skills](https://github.com/vercel-labs/agent-skills) | 34,930 | [2026-11-20](https://github.com/vercel-labs/agent-skills/commit/5a37a6329fbad3666c3207392a6a7c0110e92efb) | No |
| [Matt Pocock Skills](https://github.com/mattpocock/skills) | 333,011 | [2026-11-25](https://github.com/mattpocock/skills/commit/6f7f7831a625f040a8e06a0e7954826b87ce775a) | No |
| [Superpowers](https://github.com/obra/superpowers) | 326,749 | [2026-11-03](https://github.com/obra/superpowers/commit/22f0b463e7a5e579904dd6211a520321035526f7) | No |
| [Expo Skills](https://github.com/expo/skills) | 4,243 | [2026-11-25](https://github.com/expo/skills/commit/c5e536273b6b4a7a3ad5dd9d74b6098c15138b21) | No |
| [Trail of Bits Skills](https://github.com/trailofbits/skills) | 8,437 | [2026-11-12](https://github.com/trailofbits/skills/commit/149d7b21f4067765b82e67029730b42d228ef4b4) | No |
| [Obsidian Skills](https://github.com/obsidianmd/obsidian-skills) | 53,792 | [2026-11-25](https://github.com/obsidianmd/obsidian-skills/commit/79e85b73ef041fdfb6437ab3824e2fe29eda9244) | No |
| [Marketing Skills](https://github.com/coreyhaines31/marketingskills) | 62,689 | [2026-11-23](https://github.com/coreyhaines31/marketingskills/commit/8fd2fcade2fd6629026e9dfe6d133b55b36968b9) | No |
| [WordPress Agent Skills](https://github.com/WordPress/agent-skills) | 2,404 | [2026-11-25](https://github.com/WordPress/agent-skills/commit/32ea909f7d01be2e08fee6aff6ae449a42b9b34f) | No |
| [Sanity Agent Toolkit](https://github.com/sanity-io/agent-toolkit) | 201 | [2026-11-25](https://github.com/sanity-io/agent-toolkit/commit/627296c38d9bd80b23343f93666e5bcb3c9ccc86) | No |
| [Stripe AI](https://github.com/stripe/ai) | 2,093 | [2026-11-25](https://github.com/stripe/ai/commit/d4b19a989bf12bdbd4d42de1f9bfd3aec56fd9da) | No |
| [Resend Skills](https://github.com/resend/resend-skills) | 220 | [2026-11-19](https://github.com/resend/resend-skills/commit/063246e39987faebc2608f968ca13a02d994a0d4) | No |
| [Callstack Agent Skills](https://github.com/callstackincubator/agent-skills) | 1,721 | [2026-10-08](https://github.com/callstackincubator/agent-skills/commit/59e9d17446a248b21d86f078fcd0bd2d36db1ca4) | No |
| [React Native Community Skills](https://github.com/react-native-community/skills) | 28 | [2026-08-05](https://github.com/react-native-community/skills/commit/1fb0e0848fc7f4bbf42fec490338613cbc6f6b08) | No |
| [Flutter Agent Plugins](https://github.com/flutter/agent-plugins) | 3,213 | [2026-11-18](https://github.com/flutter/agent-plugins/commit/ff6d472ee66dbed566c4500edee460c94fde0a02) | No |
| [Dart Skills](https://github.com/dart-lang/skills) | 561 | [2026-11-16](https://github.com/dart-lang/skills/commit/f84b16872b5d186f4e877511b49b93c204a1c4ef) | No |
| [iOS Simulator Skill](https://github.com/conorluddy/ios-simulator-skill) | 1,343 | [2026-11-08](https://github.com/conorluddy/ios-simulator-skill/commit/86fb9ba90a438bd2ee7ab640165bd77da396d941) | No |
| [Supabase Agent Skills](https://github.com/supabase/agent-skills) | 3,138 | [2026-10-02](https://github.com/supabase/agent-skills/commit/c9be0e931b7930f7d02126d04774d904c381e7d7) | No |
| [Prisma Skills](https://github.com/prisma/skills) | 80 | [2026-11-09](https://github.com/prisma/skills/commit/a6f192959cf43b08aa330fe1ffca090267215812) | No |
| [Neon Agent Skills](https://github.com/neondatabase/agent-skills) | 120 | [2026-11-18](https://github.com/neondatabase/agent-skills/commit/d3601d9e1f9398b96a1ee25047bafba5f04199eb) | No |
| [ClickHouse Agent Skills](https://github.com/ClickHouse/agent-skills) | 576 | [2026-11-24](https://github.com/ClickHouse/agent-skills/commit/0d6915c5bfff79282e40e424394e9691cafd488d) | No |
| [Hugging Face Skills](https://github.com/huggingface/skills) | 11,404 | [2026-11-25](https://github.com/huggingface/skills/commit/c158db6f839c65fe3234f0baa743f5e2c8d4ec13) | No |
| [Apify Agent Skills](https://github.com/apify/agent-skills) | 2,518 | [2026-11-23](https://github.com/apify/agent-skills/commit/fe2cbcc3338e0546fb03c7057799f29cae6a78ef) | No |
| [Firecrawl Skills](https://github.com/firecrawl/skills) | 175 | [2026-11-11](https://github.com/firecrawl/skills/commit/1d4b0728d0f448cafef2eb8370c907fde7cb6f42) | No |
| [Cloudflare Skills](https://github.com/cloudflare/skills) | 3,461 | [2026-11-24](https://github.com/cloudflare/skills/commit/ff191de7d903788eceaf516a514ae7d3b56b924a) | No |
| [Microsoft Skills](https://github.com/microsoft/skills) | 3,249 | [2026-11-20](https://github.com/microsoft/skills/commit/47eb3888eb42aef074fcb617931bf6e5934e45d9) | No |
| [HashiCorp Agent Skills](https://github.com/hashicorp/agent-skills) | 941 | [2026-11-04](https://github.com/hashicorp/agent-skills/commit/5e30fa5c867ba6777c37e4206babfd08049c396f) | No |
| [Sentry Skills](https://github.com/getsentry/skills) | 1,201 | [2026-11-14](https://github.com/getsentry/skills/commit/a582c51ee29d0f35e6ac321340796f77d43da733) | No |
| [Playwright Skill](https://github.com/lackeyjb/playwright-skill) | 3,325 | [2026-08-14](https://github.com/lackeyjb/playwright-skill/commit/dd47a6a023e249eb1b36e9e943eab89d0900865d) | No |
| [FFUF Skill](https://github.com/jthack/ffuf_claude_skill) | 216 | [2025-10-16](https://github.com/jthack/ffuf_claude_skill/commit/50fd4af4d8bd60cfc48fd84eda1720fbd718857d) | No |
| [Vercel Agent Browser](https://github.com/vercel-labs/agent-browser) | 54,008 | [2026-11-26](https://github.com/vercel-labs/agent-browser/commit/a67ba089fec5fbfec07346aebad11666463d9799) | No |
| [ECC (Everything Claude Code)](https://github.com/affaan-m/ECC) | 310,797 | [2026-11-20](https://github.com/affaan-m/ECC/commit/4adeee6732a12d1540f49a4d50a38ce8c97f9a53) | No |
| [wshobson Agents](https://github.com/wshobson/agents) | 42,901 | [2026-11-24](https://github.com/wshobson/agents/commit/c96b5f6552dba32e4492307493ee613581430715) | No |
| [Planning with Files](https://github.com/OthmanAdi/planning-with-files) | 28,236 | [2026-11-25](https://github.com/OthmanAdi/planning-with-files/commit/189fd09fecb246a4064f2cd0635153b5297f5369) | No |
| [Claude-Codex Skills](https://github.com/levnikolaevich/claude-code-skills) | 597 | [2026-11-11](https://github.com/levnikolaevich/claude-code-skills/commit/809845957a79a8e470d97a794ab7f19fa4f246b7) | No |
| [Scientific Agent Skills](https://github.com/K-Dense-AI/scientific-agent-skills) | 58,491 | [2026-11-23](https://github.com/K-Dense-AI/scientific-agent-skills/commit/c21d13b3cc2894680229ba9959a53281acb9200e) | No |
| [Remotion Skills](https://github.com/remotion-dev/skills) | 8,015 | [2026-11-24](https://github.com/remotion-dev/skills/commit/a3f4098a2afd0e13f6a6f8c8760e275f75457ea9) | No |
| [Anthropic Knowledge Work Plugins](https://github.com/anthropics/knowledge-work-plugins) | 36,961 | [2026-11-23](https://github.com/anthropics/knowledge-work-plugins/commit/5e504ae11498f2b8daa30d86b7dab97b2ecd8092) | No |
| [n8n Skills](https://github.com/czlonkowski/n8n-skills) | 6,711 | [2026-11-18](https://github.com/czlonkowski/n8n-skills/commit/ecdeca6f760b56bb1b11c0a7c961f11b69cb87d5) | No |
| [Claude Skills by alirezarezvani](https://github.com/alirezarezvani/claude-skills) | 30,498 | [2026-11-23](https://github.com/alirezarezvani/claude-skills/commit/ea7b5ab8da93bbba8880152d9ccb8c9979f12252) | No |
| [Roost](https://github.com/Beakpoint-Insights/roost) | 37 | [2026-11-17](https://github.com/Beakpoint-Insights/roost/commit/9567828d5c3bb7bcbcc0e9738052be52ca36b4ae) | No |
| [Academic Writing Skills](https://github.com/WenyuChiou/academic-writing-skills) | 491 | [2026-11-12](https://github.com/WenyuChiou/academic-writing-skills/commit/70e6d20921160fcf541bc4137ec4f6ca2875a069) | No |

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

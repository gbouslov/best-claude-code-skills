# Claude Code Skills

**40 skill collections and specialist skills, organised by the work you need to do.** Compare what each one adds, the stack it assumes, and its installation instructions.

A Claude Code skill is a folder with a `SKILL.md` file that teaches the agent a reusable task. This list covers documents, software development, mobile apps, security, data, research and marketing. It also identifies collections packaged as plugins and tools that include a skill.

**Last checked: 26 October 2026.** Maintained by [Gabe Bouslov](https://gabebouslov.com).

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

Browse: [web](#web-applications-and-content) · [mobile](#mobile-apps) · [data and ML](#data-databases-and-machine-learning) · [cloud](#cloud-and-infrastructure) · [security and browsers](#security-debugging-and-browser-testing) · [engineering](#engineering-workflows) · [documents and research](#documents-research-and-creative-work) · [marketing and automation](#marketing-business-and-automation).

## Web applications and content

| Collection | What it adds | Stack and setup |
|---|---|---|
| [Vercel Agent Skills](https://github.com/vercel-labs/agent-skills) | React performance, composition patterns, interface review and Vercel optimisation. Choose it when the change is in your web application's code or deployment. | React/Next.js and related web workflows. [Setup](https://github.com/vercel-labs/agent-skills/blob/main/README.md). |
| [WordPress Agent Skills](https://github.com/WordPress/agent-skills) | Routes WordPress work into block, theme, REST API, WP-CLI and permissions workflows. Useful for Gutenberg development and existing sites. | WordPress. [Setup](https://github.com/WordPress/agent-skills/blob/trunk/README.md). |
| [Sanity Agent Toolkit](https://github.com/sanity-io/agent-toolkit) | Content modelling, schemas, GROQ and Studio guidance, with separate skills and MCP options. | Sanity projects. [Setup](https://github.com/sanity-io/agent-toolkit/blob/main/README.md). |
| [Stripe AI](https://github.com/stripe/ai) | Stripe integration guidance in a repository that also contains AI SDK and MCP resources. Follow its agent-skills instructions for the reusable guidance. | Stripe integrations. [Setup](https://github.com/stripe/ai/blob/main/README.md). |
| [Resend Skills](https://github.com/resend/resend-skills) | Separate workflows for sending email, React Email, CLI work and agent inboxes. Useful when delivery and inbox behaviour are part of the application. | Resend and related email tooling; live operations need the relevant service access. [Setup](https://github.com/resend/resend-skills/blob/main/README.md). |

## Mobile apps

| Collection | What it adds | Stack and setup |
|---|---|---|
| [Expo Skills](https://github.com/expo/skills) | Expo Router interfaces, SDK upgrades, builds and updates. The first stop for an Expo-specific task. | Expo and EAS. [Setup](https://github.com/expo/skills/blob/main/README.md). |
| [Callstack Agent Skills](https://github.com/callstackincubator/agent-skills) | React Native performance, navigation, testing, migration and native-library workflows. Choose it for native/mobile concerns beyond Expo delivery. | React Native; task-specific native tooling. [Setup](https://github.com/callstackincubator/agent-skills/blob/main/README.md). |
| [React Native Community Skills](https://github.com/react-native-community/skills) | Focused upgrade guidance and migration to the Strict TypeScript API. Useful for a version transition in a CLI project. | React Native CLI projects. [Setup](https://github.com/react-native-community/skills/blob/main/README.md). |
| [Flutter Skills](https://github.com/flutter/skills) | Flutter UI, architecture, widget tests, integration tests and responsive layouts. | Flutter; some workflows use Dart/Flutter MCP tooling. [Setup](https://github.com/flutter/skills/blob/main/README.md). |
| [Dart Skills](https://github.com/dart-lang/skills) | Language-level CLI, tests, package fixes, FFI, native assets and documentation. Useful outside Flutter UI work too. | Dart. [Setup](https://github.com/dart-lang/skills/blob/main/README.md). |
| [iOS Simulator Skill](https://github.com/conorluddy/ios-simulator-skill) | Build and simulator workflows using Xcode tools and semantic navigation. | macOS, Xcode and the documented simulator dependencies. [Setup](https://github.com/conorluddy/ios-simulator-skill/blob/main/README.md). |

## Data, databases and machine learning

| Collection | What it adds | Stack and setup |
|---|---|---|
| [Supabase Agent Skills](https://github.com/supabase/agent-skills) | Postgres performance, row-level security and Supabase authentication, SSR and migrations. | Postgres/Supabase. [Setup](https://github.com/supabase/agent-skills/blob/main/README.md). |
| [Prisma Skills](https://github.com/prisma/skills) | Prisma CLI, client API, adapters, database setup and version migration. Choose it when the question is in the ORM layer. | Prisma; use guidance for your installed version. [Setup](https://github.com/prisma/skills/blob/main/README.md). |
| [Neon Agent Skills](https://github.com/neondatabase/agent-skills) | Neon-specific database branches, authentication and other platform workflows. | Neon Postgres. [Setup](https://github.com/neondatabase/agent-skills/blob/main/README.md). |
| [ClickHouse Agent Skills](https://github.com/ClickHouse/agent-skills) | Analytical table design, primary keys, joins, batching and chDB workflows. Choose it for analytical workloads. | ClickHouse/chDB. [Setup](https://github.com/ClickHouse/agent-skills/blob/main/README.md). |
| [Hugging Face Skills](https://github.com/huggingface/skills) | Hub models and datasets, model selection, training jobs and deployment. | Hugging Face tooling; model, compute and account needs depend on the task. [Setup](https://github.com/huggingface/skills/blob/main/README.md). |
| [Apify Agent Skills](https://github.com/apify/agent-skills) | Distinguishes running an existing Actor from building one or integrating it into an application. | Apify; service execution may be billed. [Setup](https://github.com/apify/agent-skills/blob/main/README.md). |
| [Firecrawl Skills](https://github.com/firecrawl/skills) | Web extraction, CLI use, application integration and research workflows as separate choices. | Firecrawl tooling and service access where required. [Setup](https://github.com/firecrawl/skills/blob/main/README.md). |

## Cloud and infrastructure

| Collection | What it adds | Stack and setup |
|---|---|---|
| [Cloudflare Skills](https://github.com/cloudflare/skills) | Guidance for building Workers and stateful applications, with product-specific routing and Wrangler workflows. | Cloudflare. [Setup](https://github.com/cloudflare/skills/blob/main/README.md). |
| [Microsoft Skills](https://github.com/microsoft/skills) | Azure SDK and Foundry guidance organised by language and product. The repository also contains agents, plugins and MCP configuration. | Microsoft/Azure stack. Select the relevant component. [Setup](https://github.com/microsoft/skills/blob/main/README.md). |
| [HashiCorp Agent Skills](https://github.com/hashicorp/agent-skills) | Terraform and Packer guidance available as product bundles or individual skills. | HashiCorp tooling. [Setup](https://github.com/hashicorp/agent-skills/blob/main/README.md). |

## Security, debugging and browser testing

| Collection | What it adds | Stack and setup |
|---|---|---|
| [Trail of Bits Skills](https://github.com/trailofbits/skills) | Audit context, differential review, smart-contract and agentic GitHub Actions security workflows. | Specialist plugins; select the relevant analysis. [Setup](https://github.com/trailofbits/skills/blob/main/README.md). |
| [Sentry Skills](https://github.com/getsentry/skills) | Engineering code review, simplification, debugging and security workflows, including Django-specific checks. | Sentry's engineering conventions and task-specific tooling. [Setup](https://github.com/getsentry/skills/blob/main/README.md). |
| [Playwright Skill](https://github.com/lackeyjb/playwright-skill) | Writes and runs browser automation for the task at hand. Useful when the browser check needs a custom script. | Playwright and browser dependencies. [Setup](https://github.com/lackeyjb/playwright-skill/blob/main/README.md). |
| [FFUF Skill](https://github.com/jthack/ffuf_claude_skill) | Focused web fuzzing and endpoint-discovery guidance. | ffuf, a compatible host setup and a target you are authorised to test. [Setup](https://github.com/jthack/ffuf_claude_skill/blob/main/README.md). |
| [Vercel Agent Browser](https://github.com/vercel-labs/agent-browser) | A browser CLI with a bundled skill and a snapshot/element-reference interaction model. | Tool plus skill; install the browser tooling as documented. [Setup](https://github.com/vercel-labs/agent-browser/blob/main/README.md). |

## Engineering workflows

| Collection | What it adds | Packaging and setup |
|---|---|---|
| [Superpowers](https://github.com/obra/superpowers) | An opinionated process from requirements and plans through implementation and verification. Choose it for a consistent way to approach whole tasks. | Workflow collection. [Setup](https://github.com/obra/superpowers/blob/main/README.md). |
| [Matt Pocock Skills](https://github.com/mattpocock/skills) | Focused questioning, specifications, tickets and design discussions. Choose a named workflow such as `grill-me` or `to-spec`. | Individual workflows; adapt issue tracking and document locations to your project. [Setup](https://github.com/mattpocock/skills/blob/main/README.md). |
| [Everything Claude Code](https://github.com/affaan-m/everything-claude-code) | Skills alongside memory, hooks, rules and agent configuration. Choose it when you want to adopt an environment as well as reusable task guidance. | Broader configuration system. [Setup](https://github.com/affaan-m/everything-claude-code/blob/main/README.md). |
| [wshobson Agents](https://github.com/wshobson/agents) | Modular developer bundles combining agents, commands and skills. | Plugin bundles; select the language or task you need. [Setup](https://github.com/wshobson/agents/blob/main/README.md). |
| [Planning with Files](https://github.com/OthmanAdi/planning-with-files) | Keeps the plan, findings and progress on disk so a long task can resume after interruption. | Persistent task planning with host-specific hooks. [Setup](https://github.com/OthmanAdi/planning-with-files/blob/master/README.md). |
| [Claude-Codex Skills](https://github.com/levnikolaevich/claude-code-skills) | Discovery, architecture, delivery planning and verification, grouped into suites with explicit checks and reports. | Standalone skills and suites. [Setup](https://github.com/levnikolaevich/claude-code-skills/blob/master/README.md). |

## Documents, research and creative work

| Collection | What it adds | Stack and setup |
|---|---|---|
| [Anthropic Skills](https://github.com/anthropics/skills) | Document creation/editing plus examples and a template for writing a skill. | The document skills are source-available; check their individual licenses. [Setup](https://github.com/anthropics/skills/blob/main/README.md). |
| [Scientific Skills](https://github.com/K-Dense-AI/claude-scientific-skills) | Bioinformatics, chemistry, imaging, statistics and scientific communication workflows. | Scientific packages and data access vary by discipline. [Setup](https://github.com/K-Dense-AI/claude-scientific-skills/blob/main/README.md). |
| [Obsidian Skills](https://github.com/kepano/obsidian-skills) | Markdown, Bases, JSON Canvas, CLI and Defuddle workflows for vault work. | Obsidian file formats and tooling. [Setup](https://github.com/kepano/obsidian-skills/blob/main/README.md). |
| [Remotion Skills](https://github.com/remotion-dev/skills) | Programmatic video creation, rendering, captions, multimedia and upgrade workflows. | Remotion. [Setup](https://github.com/remotion-dev/skills/blob/main/README.md). |

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

## Install the part you need

Follow the linked project's setup instructions. Repositories distribute skills in different ways: some are plugin marketplaces, some support the skills CLI, and some document copying an individual folder.

For Anthropic's document skills, run these commands **inside Claude Code**:

```text
/plugin marketplace add anthropics/skills
/plugin install document-skills@anthropic-agent-skills
```

For a skill you author or copy manually, the project location is `.claude/skills/<skill-name>/SKILL.md`; the personal location is `~/.claude/skills/<skill-name>/SKILL.md`. Project scope makes a shared workflow travel with the repository. Personal scope makes it available across your projects. The [official skills documentation](https://code.claude.com/docs/en/skills) explains discovery, invocation and configuration.

Read the instructions and accompanying scripts before enabling a third-party skill. For a shared workflow, keep the chosen version and setup instructions with the project. [Contributions](CONTRIBUTING.md) should link directly to the project's current installation instructions.

## Frequently asked questions

### What are Claude Code skills?

Skills package reusable task instructions in a folder containing `SKILL.md`, with optional scripts and reference files. Claude Code can load an applicable skill or invoke it by name. See the [official guide](https://code.claude.com/docs/en/skills).

### How are skills different from plugins and MCP servers?

A skill teaches a workflow. A plugin can distribute skills along with other components, such as commands, hooks and agents. An MCP server connects the agent to tools or data. A workflow may need both a skill and a connector; the rows above identify those dependencies. See [plugins](https://code.claude.com/docs/en/plugins) and [MCP](https://code.claude.com/docs/en/mcp).

### Which skill should I install first?

Pick the row for your next task. For documents, start with Anthropic; for React performance, Vercel; for an Expo app, Expo; for requirements discussion, Matt Pocock. Add another collection when you have a task it covers.

### Do the same skills work in Codex, Cursor and other agents?

The [Agent Skills format](https://agentskills.io/) is shared across participating tools. Check the project's instructions for your agent: host-specific hooks, commands and connectors can require different setup.

### Are these skills free and open source?

Check the upstream license for the specific skill. Collections can mix licenses: Anthropic's document skills are source-available, while other examples use open-source licenses. A free download can also require a paid model, service or compute. The [MIT license](LICENSE) here covers this list's original text; it does not change any linked project's terms.

## Contributions and selection

Entries are selected for a specific job, a primary source with usable setup instructions, and current availability. Source links and documented scope were checked on the date above. Suggest a missing task, update a changed setup link, or explain why two entries should be distinguished in [a contribution](CONTRIBUTING.md).

Useful companion directories: [Awesome Claude Skills](https://github.com/travisvn/awesome-claude-skills), [Composio's Awesome Claude Skills](https://github.com/ComposioHQ/awesome-claude-skills), and [Awesome Claude Code](https://github.com/hesreallyhim/awesome-claude-code).

Maintained by [Gabe Bouslov](https://gabebouslov.com). Star the repository to find it again; propose improvements through an issue or pull request.

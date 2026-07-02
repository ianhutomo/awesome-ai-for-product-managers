# Awesome AI for Product Managers

A curated, opinionated list of AI tools, workflows, and references for product managers who want practical leverage without turning their roadmap into demo theater.

> Status: published draft maintained by TARS from Ian’s AI-for-PM bookmarks and ongoing curation.

## Principles

- Prefer workflows over tool collecting.
- Include why a PM should care, not just what the tool does.
- Separate production-safe workflows from experiments.
- Keep privacy, data handling, and hallucination risk visible.
- Avoid AI slop: every entry should help a PM make better decisions, communicate clearer, or collaborate faster.

## Contents

- [Foundations / technical literacy](#foundations--technical-literacy)
- [Strategy & discovery](#strategy--discovery)
- [User research](#user-research)
- [PRD/spec writing](#prdspec-writing)
- [Analytics & experiments](#analytics--experiments)
- [Design and product review](#design-and-product-review)
- [Engineering collaboration](#engineering-collaboration)
- [Go-to-market and comms](#go-to-market-and-comms)
- [Agent systems for PMs](#agent-systems-for-pms)
- [Quality, safety, and evaluation](#quality-safety-and-evaluation)
- [Post ideas](#post-ideas)

## Foundations / technical literacy

- [Karpathy — LLM101n](https://github.com/karpathy/LLM101n) — Practical “build a Storyteller AI Large Language Model” course/repo. Useful for PMs who need enough model literacy to reason about tokens, training, evals, and why demos fail outside the happy path.
- [Karpathy — llm.c](https://github.com/karpathy/llm.c) — Minimal LLM training in C/CUDA. Not a PM workflow tool, but a good reference when explaining what is actually inside the black box.
- [Hugging Face Tasks](https://huggingface.co/tasks) — Good map of model capabilities and task categories.
- [OpenAI Cookbook](https://github.com/openai/openai-cookbook) — Practical examples for prompting, evals, structured outputs, RAG, and tool use.
- [Anthropic Cookbook](https://github.com/anthropics/anthropic-cookbook) — Useful Claude examples for tool use, evaluation, and agentic workflows.
- [AI Engineering from Scratch](https://aiengineeringfromscratch.com/) — Practical AI engineering curriculum; useful for PMs who need to understand how LLM apps, RAG, evals, and deployment pieces fit together.
- [Sophon AI Papers](https://sophon.at/papers) — Trending AI papers feed for scanning research shifts without living on arXiv.
- [Nate Berkopec — Thoughts on LLMs, May 2026](https://x.com/nateberkopec/status/2058014104854626490) — Opinionated industry read on current LLM capabilities and product implications.

## Strategy & discovery

- ChatGPT / Claude / Gemini — Fast synthesis and critique for strategy notes, market maps, JTBD hypotheses, and competitor teardown drafts. Treat as a sparring partner, not an oracle.
- Perplexity — Useful for sourced market scans and quick landscape mapping. Verify sources before decisions.
- NotebookLM — Strong for grounding answers in a defined corpus of docs, interviews, reports, or meeting notes.
- Exa / Tavily / Firecrawl — Developer-facing search/scrape primitives for PM research agents and internal knowledge workflows.
- [The Stanford STORM Method](https://x.com/heynavtoor/status/2067194761446920264) — Research workflow pattern for turning a broad topic into grounded outlines, questions, and synthesis.

## User research

- Granola — Meeting notes with strong capture UX; useful for PM follow-up and insight extraction.
- Fathom / Otter — Call recording/transcription options; check company privacy policies before uploading user calls.
- Dovetail AI — Research repository workflows; useful if the team already uses Dovetail.
- NotebookLM — Good for asking grounded questions across interview transcripts and research docs.

## PRD/spec writing

- Claude Projects / ChatGPT Projects — Keep product context, style, and examples together for PRD/spec iteration.
- Cursor / Claude Code / Codex — Useful when specs touch code, APIs, repo structure, or implementation constraints.
- Linear AI / Jira AI — Ticket hygiene, summaries, and acceptance criteria; best when humans still own prioritization.
- TARS Social/Spec/Strategy Writer skills — Local skill pattern for repeatable writing workflows with Ian’s voice and quality bar.
- [/goal + Loss Functions: Distill a Product in 30 Hours](https://x.com/elvissun/status/2065035615800864954) — Prompt/playbook framing for moving from product intent to concrete working artifacts.

## Analytics & experiments

- Amplitude AI / Mixpanel AI — Natural-language analytics helpers; use for exploration, not final metric truth.
- Metabase AI / Hex / Mode AI — SQL and notebook assistance for PM analytics workflows.
- Eppo / Statsig AI features — Experiment planning and analysis support; still require statistical judgment.
- ChatGPT Advanced Data Analysis — Good for CSV exploration, quick charts, and sanity checks.

## Design and product review

- Figma AI — Early ideation and design ops; evaluate outputs carefully.
- v0 / Bolt / Lovable — Fast UI prototypes for concept testing, not production source of truth.
- Claude / GPT-4o vision / Gemini vision — Screenshot critique, heuristic review, flow analysis.
- [Codex Sites](https://x.com/TheRohanVarma/status/2061872164442403139) — Example of code agents moving from implementation to shareable deployed prototypes for non-technical stakeholders.
- [Interface Craft](https://interfacecraft.dev/) — Curated design skills and references for raising the taste bar on AI-generated interfaces.
- [Animated onboarding from screenshots](https://x.com/bidah/status/2053071057737679138) — Claude skill pattern for turning product screenshots into onboarding videos and conversion assets.

## Engineering collaboration

- GitHub Copilot — Developer productivity baseline; PM value is understanding what engineering can prototype quickly.
- Cursor — Codebase Q&A and implementation exploration.
- Sourcegraph Cody — Code intelligence for larger repos.
- OpenAPI + LLM workflows — Turn API specs into PM-readable capability maps and edge-case checklists.
- [Interactive workflow map prompt](https://x.com/DaveJ/status/2054085519642931466) — Prompt pattern for turning app packages, components, and user actions into an explorable single-page HTML workflow map.
- [Using Claude Code: The Unreasonable Effectiveness of HTML](https://x.com/trq212/status/2052809885763747935) — Pattern for asking agents to produce inspectable HTML artifacts instead of walls of markdown.
- [Implementation notes prompt](https://x.com/trq212/status/2056415973125796184) — Lightweight way to make coding agents document assumptions, tradeoffs, and changes while implementing a spec.
- [A harness for every task](https://x.com/trq212/status/2061907337154367865) — Anthropic-style framing for dynamic workflows where agents build task-specific scaffolding.
- [Two-model coding workflow](https://x.com/kirillk_web3/status/2067302748970782920) — Cost-control pattern for routing coding-agent work between premium and cheaper models without losing review discipline.

## Go-to-market and comms

- Claude / ChatGPT — Positioning, launch notes, FAQs, customer emails, sales enablement drafts.
- Canva AI / Figma AI — Lightweight visuals; beware generic output.
- Descript / CapCut / OpusClip — Video editing and repurposing for launches and product education.
- [How to build your content system with AI](https://x.com/shannholmberg/status/2053399704499859757) — Example architecture for an AI-assisted content loop that finds ideas, drafts, publishes, and learns.

## Agent systems for PMs

- [Garry Tan — gstack](https://github.com/garrytan/gstack) — Opinionated agent/memory/workflow stack direction. Relevant as a benchmark for PM agent systems and durable memory.
- OpenClaw — Local autonomous agent runtime with tools, memory, browser, cron, and approval boundaries.
- [Claude on a Mac Mini: the second brain that builds itself](https://x.com/gippp69/status/2069068377574776987) — Concrete always-on agent loop pattern for turning saved media, articles, and notes into a local research system.
- Claude Code / Codex CLI — Code-aware agents for repo tasks, investigation, and structured implementation.
- n8n / Zapier / Make — Product ops automation; useful for structured workflows, less ideal for judgment-heavy work.
- [Autoloops > Agent Loops](https://x.com/meta_alchemist/status/2063999438050455870) — Guide to self-improving agent loops; useful for PMs designing repeatable AI workflows, not one-shot prompts.
- [How to build your own agent harness](https://x.com/mfpiccolo/status/2060069083878408689) — Explains harness choices and tradeoffs across agent frameworks.
- [Stop building Foxconn factories for your agents](https://x.com/garrytan/status/2061454423034110372) — Useful critique of over-orchestrated agent workflows and where human-in-the-loop leverage matters.
- [Ponytail](https://github.com/DietrichGebert/ponytail) — Claude Code skill that nudges agents toward simpler diffs; useful as a benchmarkable “less code” product-building constraint.
- [Your AI's Memory Is Quietly Making It Dumber](https://x.com/mvanhorn/status/2070966613994795489) — Argument for keeping always-loaded agent memory small, moving lessons into versioned skills, and using retrieval for everything else.
- [June](https://www.opensoftware.co/june) — Local-first Mac AI workspace with an agent, voice dictation, meeting notes, and privacy-preserving model routing; useful benchmark for personal PM agent UX and data-boundary choices.
- [Matt Pocock — Skills](https://github.com/mattpocock/skills) — Composable agent skills for alignment, triage, shared language, and repeatable engineering workflows; useful pattern library for PM-to-agent collaboration.

## Quality, safety, and evaluation

- Promptfoo — Prompt and LLM app testing.
- OpenAI Evals / inspect-style eval harnesses — Useful when AI becomes part of a product workflow.
- Human review gates — Still the best “tool” for public posts, customer-impacting changes, legal/medical/financial advice, and account actions.
- Privacy checklist — Never upload customer/user data to tools without confirming policy, DPA, retention, and team approval.
- [Claude Code self-check loops](https://x.com/ClaudeDevs/status/2061900434722496604) — Example of encoding manual review checks so an agent verifies its work before handoff.
- [Claude Code deny rules for secrets](https://x.com/0x_rody/status/2059930796488524061) — Practical reminder that agent tooling needs explicit data-access boundaries and secret-protection rules.
- [From Localhost to Launched: Safely Shipping Apps That Anyone Can Build](https://engineering.block.xyz/blog/from-localhost-to-launched-safely-shipping-apps-that-anyone-can-build) — Block’s platform pattern for letting non-engineers ship AI-generated internal tools with SSO, secrets, and data-access guardrails.

## Post ideas

- The PM AI stack I’d actually use in 2026
- AI agents for PMs: useful workflows, not demo theater
- How to turn customer calls into PRDs without creating AI slop
- A 5-agent product team OS: researcher, spec writer, reviewer, analyst, launch writer
- What belongs in an Awesome AI for Product Managers list?

## Contribution criteria

A resource belongs here if it helps a PM do at least one of these:

1. Understand technical tradeoffs better.
2. Synthesize research or evidence faster.
3. Write clearer specs, decisions, or launch artifacts.
4. Collaborate with design/engineering more effectively.
5. Build safer repeatable AI workflows.

Avoid adding pure hype, generic tool directories, or entries without a PM-specific use case.

## License

Draft pending Ian review. Suggested: CC BY 4.0 for content, MIT only if code/scripts are added.

# Awesome AI for Product Managers

A curated, opinionated list of AI tools, workflows, and references for product managers who want practical leverage without turning their roadmap into demo theater.

> Status: draft repo prepared by TARS for Ian review. Not yet published to GitHub because GitHub CLI is not authenticated on this Mac mini.

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

## Strategy & discovery

- ChatGPT / Claude / Gemini — Fast synthesis and critique for strategy notes, market maps, JTBD hypotheses, and competitor teardown drafts. Treat as a sparring partner, not an oracle.
- Perplexity — Useful for sourced market scans and quick landscape mapping. Verify sources before decisions.
- NotebookLM — Strong for grounding answers in a defined corpus of docs, interviews, reports, or meeting notes.
- Exa / Tavily / Firecrawl — Developer-facing search/scrape primitives for PM research agents and internal knowledge workflows.

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

## Analytics & experiments

- Amplitude AI / Mixpanel AI — Natural-language analytics helpers; use for exploration, not final metric truth.
- Metabase AI / Hex / Mode AI — SQL and notebook assistance for PM analytics workflows.
- Eppo / Statsig AI features — Experiment planning and analysis support; still require statistical judgment.
- ChatGPT Advanced Data Analysis — Good for CSV exploration, quick charts, and sanity checks.

## Design and product review

- Figma AI — Early ideation and design ops; evaluate outputs carefully.
- v0 / Bolt / Lovable — Fast UI prototypes for concept testing, not production source of truth.
- Claude / GPT-4o vision / Gemini vision — Screenshot critique, heuristic review, flow analysis.

## Engineering collaboration

- GitHub Copilot — Developer productivity baseline; PM value is understanding what engineering can prototype quickly.
- Cursor — Codebase Q&A and implementation exploration.
- Sourcegraph Cody — Code intelligence for larger repos.
- OpenAPI + LLM workflows — Turn API specs into PM-readable capability maps and edge-case checklists.

## Go-to-market and comms

- Claude / ChatGPT — Positioning, launch notes, FAQs, customer emails, sales enablement drafts.
- Canva AI / Figma AI — Lightweight visuals; beware generic output.
- Descript / CapCut / OpusClip — Video editing and repurposing for launches and product education.

## Agent systems for PMs

- [Garry Tan — gstack](https://github.com/garrytan/gstack) — Opinionated agent/memory/workflow stack direction. Relevant as a benchmark for PM agent systems and durable memory.
- OpenClaw — Local autonomous agent runtime with tools, memory, browser, cron, and approval boundaries.
- Claude Code / Codex CLI — Code-aware agents for repo tasks, investigation, and structured implementation.
- n8n / Zapier / Make — Product ops automation; useful for structured workflows, less ideal for judgment-heavy work.

## Quality, safety, and evaluation

- Promptfoo — Prompt and LLM app testing.
- OpenAI Evals / inspect-style eval harnesses — Useful when AI becomes part of a product workflow.
- Human review gates — Still the best “tool” for public posts, customer-impacting changes, legal/medical/financial advice, and account actions.
- Privacy checklist — Never upload customer/user data to tools without confirming policy, DPA, retention, and team approval.

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

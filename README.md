# Awesome-Prompt-Engineering-Templates

# Top Prompt Engineering & Templates Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Community Prompt Libraries, Self-Hosted Registries & Structured Template Frameworks*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Prompt Engineering & Templates**. These tools help individuals and teams discover, organize, and reuse prompts — from massive community-curated collections to self-hosted private libraries and lightweight frameworks that treat prompts as structured, versionable software components.

**Examples** include prompts.chat (Awesome ChatGPT Prompts), Fabric, OpenPromptKit, PromptBase, PromptHero, AIPRM, FlowGPT, Snack Prompt, ChatHub, and PromptPerfect (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, community curation, and template reuse — ideal for teams prioritizing data sovereignty, avoiding vendor lock-in, and building prompt libraries they fully control.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[PromptBase](https://promptbase.com/)**  
  **Marketplace for buying and selling prompts** across ChatGPT, Midjourney, DALL·E, and Stable Diffusion. Curated prompt marketplace with seller payouts. **Best for discovering niche, production-ready prompts** for specific use cases without building a library from scratch.

- **[PromptHero](https://prompthero.com/)**  
  **Prompt search engine and community** focused on AI art generation prompts for Midjourney, Stable Diffusion, and DALL·E. **Best for visual creators** seeking image-generation templates.

- **[AIPRM](https://www.aiprm.com/)**  
  **Chrome extension providing a curated prompt library** for ChatGPT with team workspaces and prompt management. **Best for ChatGPT users wanting prompt templates directly in the interface** without switching tools.

- **[FlowGPT](https://flowgpt.com/)**  
  **Community platform for discovering and sharing ChatGPT prompts** with use-case categories, rankings, and social features. **Best for discovering community-tested prompts** across diverse categories.

- **[Snack Prompt](https://snackprompt.com/)**  
  **Community-driven prompt sharing platform** with a focus on simplicity and accessibility. **Best for quick prompt discovery** without a heavy management layer.

- **[PromptPerfect](https://promptperfect.jina.ai/)**  
  **AI-powered prompt optimization tool** from Jina AI that refines and improves prompts automatically. **Best for teams wanting to improve prompt quality** without manual iteration.

## Open-Source GitHub Projects

- **[prompts.chat](https://github.com/f/prompts.chat)**  
  **The world's largest open-source prompt library for AI** — MIT licensed source, CC0 public domain prompt content, **143,000+ GitHub stars** [citation:1][citation:6] . **Formerly known as Awesome ChatGPT Prompts**, created in December 2022 as the first prompt library [citation:1] . **Works with ChatGPT, Claude, Gemini, Llama, Mistral, and more** . **Referenced by Harvard and Columbia** with 40+ academic citations; the most liked dataset on Hugging Face [citation:1] . **Self-hostable with complete privacy** — `npx prompts.chat new my-prompt-library` sets up a private instance with custom branding, themes, and authentication (GitHub/Google/Azure AD) [citation:1] . **Integrations**: CLI, **Claude Code plugin** (`/plugin marketplace add f/prompts.chat`), and **MCP server** for use in AI tools [citation:1] . **Interactive Book of Prompting** covers 25+ chapters on prompt engineering; **Prompting for Kids** teaches ages 8-14 [citation:1] . **Best for individuals and organizations wanting the largest community-curated prompt collection** with a self-hosted path for private libraries.

- **[Fabric](https://github.com/danielmiessler/fabric)**  
  **The leading open-source framework for augmenting humans using AI prompts** — MIT licensed, **50,000+ GitHub stars** . **Patterns** are reusable prompt templates stored as Markdown files (`patterns/{name}/system.md`), designed for maximum readability and editability — both for the creator and the AI receiving them [citation:4][citation:8] . **Markdown structure emphasizes what the AI should do and in what order**; instructions are kept extremely clear and use the System section almost exclusively [citation:4] . **CLI-first**: `fabric --pattern summarize` or `fabric -y "https://youtube.com/..." --pattern extract_wisdom` [citation:4] . **YouTube transcript grabbing**, **Jina AI web scraping**, and **multi-provider support** built in [citation:4] . **Prompt strategies** like Chain of Thought and Chain of Draft available as JSON files in `/strategies` [citation:4] . **Custom private patterns** stored separately and never overwritten by updates [citation:4] . **Best for individuals and teams wanting a crowdsourced pattern library** with CLI access, independent of any specific LLM provider.

- **[OpenPromptKit](https://pypi.org/project/openpromptkit/)**  
  **A lightweight open-source toolkit for building structured, reusable, testable, and version-controlled AI prompts** — MIT licensed, v0.1.0 [citation:3] . **Treats prompts as reusable software components** rather than isolated text fragments . **Goals**: reusable prompt templates, structured prompt variables, prompt validation, versioning, testing, workflow composition, and reproducible examples [citation:3] . **Example template**: `You are an expert {{role}}. Analyze the following input: {{input}} Return the result using the following format: {{format}}` — variables supplied programmatically instead of rewriting prompts manually [citation:3] . **Best for developers wanting a minimal foundation for organizing prompts systematically** without a heavy platform dependency.

### Additional Strong Open-Source Options

- **Langfuse** — Open-source LLM engineering platform with prompt management, versioning, and labels for environments and A/B testing. Self-hostable.
- **Agenta** — Open-source LLMOps platform with prompt playground, management, evaluation, and observability. MIT licensed.
- **MLflow Prompt Registry** — Git-inspired versioning with immutable versions, aliases for staging/production, and lineage tracking between prompt versions and application versions.
- **PromptHub** — AI prompt management with Git-style branching and CI/CD guardrails (commercial, but with community-driven prompt organization).
- **Awesome Prompt Engineering** — Curated resources covering papers, tools, models, APIs, benchmarks, courses, and communities for prompt engineering [citation:7].

**Frameworks for building custom systems**: Combine **prompts.chat** for a massive community library with self-hosting for private organizational use, **Fabric** for CLI-driven pattern execution and custom private patterns, and **OpenPromptKit** for treating prompts as structured, versionable software components — to build a prompt engineering and template stack tailored to your discovery needs, deployment constraints, and engineering rigor.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Prompt engineering tools and template libraries differ significantly in curation model, deployment capability, and licensing. **prompts.chat's prompt content is dedicated to the public domain under CC0** while its source code is MIT licensed [citation:1] . **Fabric's Patterns are Markdown files** designed for human and AI readability, with custom private patterns never overwritten by updates [citation:4] . **OpenPromptKit is at v0.1.0** — early-stage, with future releases planned for validation, testing, and workflow execution [citation:3] . **Community prompt libraries contain user-submitted content** — quality and safety vary; review prompts before deploying them in production workflows.
- Self-hosted open-source solutions require proper PostgreSQL setup for prompts.chat, authentication configuration, and ongoing maintenance of your private instance.

---

**Made for AI engineers, prompt engineers, and teams building reusable, versioned prompt libraries.**
Let's make prompt engineering and templates more open, curated, and reusable.

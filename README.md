# awesome-agent-skills

A curated list of awesome Agent Skills frameworks, libraries and software.

* Learning and Reference
	* [Tutorials and Books](#tutorials-and-books)
	* [Awesome Lists and Collections](#awesome-lists-and-collections)
* Language and Tooling
	* [Linters and Formatters](#linters-and-formatters)
	* [Version Control](#version-control)
* Web
	* [Web Frameworks](#web-frameworks)
	* [Frontend and UI Components](#frontend-and-ui-components)
	* [Scraping and Crawling](#scraping-and-crawling)
* Data and Storage
	* [Databases](#databases)
* Machine Learning and AI
	* [LLM and Inference](#llm-and-inference)
	* [Computer Vision](#computer-vision)
	* [Data Science and Analytics](#data-science-and-analytics)
* AI Agents
	* [Agent Frameworks and Runtimes](#agent-frameworks-and-runtimes)
	* [Agent Skills and Tooling](#agent-skills-and-tooling)
	* [Memory and Context](#memory-and-context)
	* [Evaluation and Benchmarks](#evaluation-and-benchmarks)
* Networking and Distributed
	* [Cloud and Infrastructure](#cloud-and-infrastructure)
* User Interface
	* [Mobile](#mobile)
	* [Applications and End User Tools](#applications-and-end-user-tools)
* Graphics and Media
	* [Graphics and Rendering](#graphics-and-rendering)
	* [Game Development](#game-development)
	* [Image and Video](#image-and-video)
* Security
	* [Security Tools](#security-tools)
* Testing and Quality
	* [Testing](#testing)
* Utilities
	* [Command Line Tools](#command-line-tools)
	* [Text Processing](#text-processing)
	* [Automation and Scripting](#automation-and-scripting)
* Systems and Hardware
	* [Embedded and Firmware](#embedded-and-firmware)
* Business and Domain
	* [Finance and Trading](#finance-and-trading)
	* [Business and Productivity](#business-and-productivity)
* Science and Math
	* [Scientific Computing](#scientific-computing)
* [Other](#other)

## Learning and Reference

### Tutorials and Books

* [liyupi/ai-guide](https://github.com/liyupi/ai-guide) - 程序员鱼皮的 AI 资源大全 + Vibe Coding 零基础教程，分享 OpenClaw 保姆级教程、大模型玩法（DeepSeek / GPT / Gemini / Claude / GLM）、最新 AI 资讯、Prompt 提示词大全、AI 知识百科（Agent Skills / RAG / MCP / A2A）、AI 编程教程（Harness Engineering）、AI 工具用法（Cursor / Claude Code / TRAE / Codex / Copilot）、AI 开发框架教程（Spring AI / LangChain）、AI 产品变现指南，帮你快速掌握 AI 技术，走在时代前沿。本项目为开源文档 aiguide，已升级为鱼皮 AI 导航网站
* [zebbern/claude-code-guide](https://github.com/zebbern/claude-code-guide) - Claude Code Guide - Setup, Commands, workflows, agents, skills & tips-n-tricks from beginner to power user!
* [samber/cc-skills-golang](https://github.com/samber/cc-skills-golang) - 🧑‍🎨 A collection of Golang agentic skills that works
* [xu-xiang/everything-claude-code-zh](https://github.com/xu-xiang/everything-claude-code-zh) - everything-claude-code 中文翻译项目：完整的 Claude Code 配置集合（agents, skills, hooks, commands, rules, MCPs）。源自 Anthropic 黑客松获胜者的实战配置，助力中文工程师高效理解与使用 Claude Code。
* [datawhalechina/agent-skills-with-anthropic](https://github.com/datawhalechina/agent-skills-with-anthropic) - 本项目围绕吴恩达老师在DeepLearning.AI出品的agent-skills-with-anthropic系列课程，为学习者打造中文翻译与知识整理教程。项目提供课程内容翻译、知识点梳理和示例代码解读等内容，欢迎大家Star!
* [https-deeplearning-ai/sc-agent-skills-files](https://github.com/https-deeplearning-ai/sc-agent-skills-files)
* [MaJerle/c-code-style](https://github.com/MaJerle/c-code-style) - Recommended C code style and coding rules for standard C99 or later. Comes with AI agent skill to write, edit and format the code.
* [Kotlin/kotlin-agent-skills](https://github.com/Kotlin/kotlin-agent-skills) - A collection of AI agent skills useful for projects using Kotlin language
* [mkosir/typescript-style-guide](https://github.com/mkosir/typescript-style-guide) - ⚙️ TypeScript Style Guide and Agent Skill. A concise set of conventions and best practices for consistent, maintainable code.
* [dennisdoomen/CSharpGuidelines](https://github.com/dennisdoomen/CSharpGuidelines) - A set of coding guidelines for C# up to v14, design principles, layout rules and Agent Skills for improving the overall quality of your code development.
* [JimLiu/Illustrated-Agent-Skills](https://github.com/JimLiu/Illustrated-Agent-Skills) - 《图解Skill——AI提效实战指南》官方 Repo
* [ramziddin/solid-skills](https://github.com/ramziddin/solid-skills) - AI agent skill for writing senior-engineer quality code through SOLID principles, TDD, and clean architecture
* [HoangNguyen0403/agent-skills-standard](https://github.com/HoangNguyen0403/agent-skills-standard) - A collection of Agent Skills Standard and Best Practice for Programming Languages, Frameworks that help our AI Agent follow best practies on frameworks and programming laguages
* [liyupi/yupi-skill](https://github.com/liyupi/yupi-skill) - 🐟 程序员鱼皮 Agent Skill｜把自己蒸馏成 AI 技能包，用我的思维方式和表达风格回答编程学习、求职面试、AI 编程、简历优化、技术选型、创业经验等问题。支持 Claude Code / Cursor / OpenClaw
* [wesammustafa/opencode-primer](https://github.com/wesammustafa/opencode-primer) - Master OpenCode, the open-source AI coding agent — setup, agents, skills, plugins, MCP, Zen & headless CI.
* [qqzhangyanhua/learn-opencode-agent](https://github.com/qqzhangyanhua/learn-opencode-agent) - OpenCode AI Coding Agent 学习与实践教程：从 Agents、Skills、MCP、Context Engineering 到 AI Coding Workflow。
* [elisaterumi-ai/agent-skills-in-practice](https://github.com/elisaterumi-ai/agent-skills-in-practice) - Learn what AI skills are and how to design, structure, and use them in real-world agent systems.
* [selmakcby/claude-agents-skills](https://github.com/selmakcby/claude-agents-skills) - Multi-Agent Claude Code setup — 4 uzman ajan (planner · ui-agent · builder · reviewer) + skills + Next.js demo projesi. YouTube Bölüm 1 video materyalleri.
* [kcchien/model-thinking](https://github.com/kcchien/model-thinking) - 思維模型工具箱 — 200+ mental models across 10 domains for AI-assisted thinking. Agent Skill for Claude Code.
* [Lyn-77/ProMentor](https://github.com/Lyn-77/ProMentor) - ProMentor 是一个 AI Coding Agent Skill。装上它，你的 AI 编程助手立刻化身为导师——扫描项目架构、生成阶梯式 Chapter、带你手写核心逻辑、自动判题、AI Code Review。
* [hugobowne/show-us-your-agent-skills](https://github.com/hugobowne/show-us-your-agent-skills) - Companion repo to our livestream series Show Us Your (Agent) Skills
* [AlphaMao1/AlphaMao-technology-mapping](https://github.com/AlphaMao1/AlphaMao-technology-mapping) - 从一个技术关键词出发，自动生成前沿技术领域的技术全景图谱。AI Agent Skill for Gemini CLI / Claude Code.

### Awesome Lists and Collections

* [VoltAgent/awesome-agent-skills](https://github.com/VoltAgent/awesome-agent-skills) - A curated collection of 1000+ agent skills from official dev teams and the community, compatible with Claude Code, Codex, Gemini CLI, Cursor, and more.
* [heilcheng/awesome-agent-skills](https://github.com/heilcheng/awesome-agent-skills) - Tutorials, Guides and Agent Skills Directories
* [libukai/awesome-agent-skills](https://github.com/libukai/awesome-agent-skills) - Agent Skills 终极指南：快速入门、资源推荐、精选技能与实用工具 ｜The Ultimate Guide to Agent Skills: QuickStart, Resources, Features&Toolkit
* [twostraws/Swift-Agent-Skills](https://github.com/twostraws/Swift-Agent-Skills) - A curated directory of open-source AI agent skills for Swift and Apple platform development.
* [Prat011/awesome-llm-skills](https://github.com/Prat011/awesome-llm-skills) - A curated list of awesome LLM and AI Agent Skills, resources and tools for customising AI Agent workflows - that works with Claude Code, Codex, Gemini CLI and your custom AI Agents
* [mliu98/awesome-human-distillation](https://github.com/mliu98/awesome-human-distillation) - A curated catalog of human distillliation agent skills
* [skillmatic-ai/awesome-agent-skills](https://github.com/skillmatic-ai/awesome-agent-skills) - The definitive resource for Agent Skills - modular capabilities revolutionizing AI agent architecture
* [JackyST0/awesome-agent-skills](https://github.com/JackyST0/awesome-agent-skills) - 🤖 精选的 AI Agent Skills 列表，适用于 Cursor、Claude Code、GitHub Copilot 等 AI 编程工具
* [LLMQuant/awesome-trading-agents](https://github.com/LLMQuant/awesome-trading-agents) - Curated list of LLM-driven trading agents, MCP servers, and agent skills for market research, strategy, and execution.
* [modelscope/Awesome-Vibe-Research](https://github.com/modelscope/Awesome-Vibe-Research) - An open, collaboratively-built repository for AI-assisted scientific research — collecting and curating agents, skills, workflows, tools, and best practices across the full research lifecycle. 面向 AI 辅助科研的开放共建仓库 收集和沉淀科研全流程中的 agents、skills、workflows、tools 与最佳实践
* [baibizhe/Awesome-Skills-Paper](https://github.com/baibizhe/Awesome-Skills-Paper) - contains the list of papers of agent skills
* [futantan/agent-skills.md](https://github.com/futantan/agent-skills.md) - Find awesome Agent Skills
* [finfin/awesome-frontend-skills](https://github.com/finfin/awesome-frontend-skills) - A curated list of frontend Agent Skills installable via npx skills add
* [itgoyo/awesome-agent-skills](https://github.com/itgoyo/awesome-agent-skills) - 收集全网最热门的Agent-Skills项目
* [BioTender-max/awesome-bio-agent-skills](https://github.com/BioTender-max/awesome-bio-agent-skills) - A curated collection of AI agent skills for biomedical research, covering genomics, proteomics, single-cell analysis, clinical AI, and protein design.
* [JayLZhou/Awesome-Agent-Skills](https://github.com/JayLZhou/Awesome-Agent-Skills)
* [CommandCodeAI/agent-skills](https://github.com/CommandCodeAI/agent-skills) - A curated list of awesome Skills, resources, and tools for customizing coding agent workflows.
* [kodustech/awesome-agent-skills](https://github.com/kodustech/awesome-agent-skills) - Curated list of Agent Skills for AI coding agents like Claude Code, Codex and Cursor.
* [Techopolis/awesome-ios-ai](https://github.com/Techopolis/awesome-ios-ai) - AI agent skills, agent teams, MCP servers, and tools that make AI coding assistants better at Swift and iOS development.
* [GoekeLab/awesome-genomic-skills](https://github.com/GoekeLab/awesome-genomic-skills) - A curated list of awesome genomics and bioinformatics agentic skills, MCPs and benchmarks for Claude Code, Copilot, Codex, Cursor, Gemini CLI, etc
* [Ezeafk/awesome-agent-skills](https://github.com/Ezeafk/awesome-agent-skills) - Curated reusable skills, workflows, and tool-backed capabilities for AI agents.
* [LLMSecurity/awesome-agent-skills-security](https://github.com/LLMSecurity/awesome-agent-skills-security) - 🛡️ A curated list of resources on agent skills security: attacks, defenses, frameworks, and benchmarks for securing AI agent tool use and skill ecosystems
* [codesstar/hermes-skill-atlas](https://github.com/codesstar/hermes-skill-atlas) - The complete, interactive map of Hermes Agent skills — 70+ curated, verified, open source. 🗺️
* [scienceaix/agentskills](https://github.com/scienceaix/agentskills) - Awesome Agent Skills collection list, papers, tools, projects, and resources
* [ChuckSRQ/awesome-hermes-skills](https://github.com/ChuckSRQ/awesome-hermes-skills) - A curated collection of production-ready Hermes Agent skills — brainstorming, PRD workflows, debugging, Apple integrations, MLOps, document processing, and more.
* [GulajavaMinistudio/awesome-copilot-id](https://github.com/GulajavaMinistudio/awesome-copilot-id) - A curated collection of custom agents, skills, rules, and prompts for GitHub Copilot, Google Antigravity, OpenCode, ChatGPT Codex, and Oh My Pi. Tailored for Indonesian and International developers to streamline SDLC workflows with AI.
* [anchildress1/awesome-github-copilot](https://github.com/anchildress1/awesome-github-copilot) - My ongoing WIP 🏗️ AI prompts, custom agents, skills & instructions - curated by me (and Copilot + ChatGPT).
* [thienanblog/awesome-ai-agent-skills](https://github.com/thienanblog/awesome-ai-agent-skills) - A curated list of essential skills, tools, and resources for building and enhancing advanced AI agents.
* [kael-odin/awesome-academic-research-skills](https://github.com/kael-odin/awesome-academic-research-skills) - 面向中文用户的学术论文与科研 Agent Skill 每日排行榜 · 自动搜索、过滤并排名 GitHub 上的 Claude Code / Codex / OpenCode 科研 Skill 仓库
* [BENZEMA216/awesome-weread](https://github.com/BENZEMA216/awesome-weread) - 基于微信读书官方 Agent Skill 的二创项目精选 · Curated projects built on WeRead's official Agent Skill (released 2026-05-17)

## Language and Tooling

### Linters and Formatters

* [yzddmr6/repo-analyzer](https://github.com/yzddmr6/repo-analyzer) - AI coding agent skill for deep architectural analysis of open-source projects | 开源项目深度架构分析，一句话生成专业级分析报告
* [Zhen-Bo/smell-check](https://github.com/Zhen-Bo/smell-check) - Agent Skill for code and test smell audits. Evidence-ranked findings from Refactoring, Clean Code, and the test-smell literature. Formerly pragmatic-code-review.
* [maksimzayats/specx](https://github.com/maksimzayats/specx) - ⚙️ Executable architecture guardrails and agent skills for building structured Python services!
* [Yevanchen/reclaim-code-entropy](https://github.com/Yevanchen/reclaim-code-entropy) - An evidence-first Agent Skill for safely simplifying any codebase.
* [cxuu/golang-skills](https://github.com/cxuu/golang-skills) - AI Agent Skills for idiomatic, production-ready Go code, distilled from Google, Uber, Community
* [fallow-rs/fallow-skills](https://github.com/fallow-rs/fallow-skills) - Agent skills for fallow, codebase intelligence for TypeScript and JavaScript. Teaches AI agents how to find unused code, duplication, circular deps, complexity hotspots, architecture drift, design-system drift, and (with Fallow Runtime) hot-path and cold-path evidence. Works with Claude Code, Cursor, Codex, Gemini CLI, and 30+ agents.
* [MrZoyo/deslop-GPT](https://github.com/MrZoyo/deslop-GPT) - Deletion-first Agent Skill for removing test bloat, verification theater, and speculative fallbacks while preserving behavior.

### Version Control

* [greptileai/skills](https://github.com/greptileai/skills) - Agent skill for checking PR review comments, status checks, and description completeness
* [vikingmute/review-forge](https://github.com/vikingmute/review-forge) - review-forge is an Agent Skill for structured, auditable code review workflows
* [win4r/agent-skills-code-review-router](https://github.com/win4r/agent-skills-code-review-router)
* [blessonism/github-explorer-skill](https://github.com/blessonism/github-explorer-skill) - OpenClaw Agent Skill — 对任意 GitHub 项目进行多源深度分析，输出结构化研判报告
* [danverbraganza/jujutsu-skill](https://github.com/danverbraganza/jujutsu-skill) - Agent Skill for working with Jujutsu VCS
* [fvadicamo/dev-agent-skills](https://github.com/fvadicamo/dev-agent-skills) - Claude Code skills plugin for Git, GitHub, and skill authoring workflows
* [mgratzer/forge](https://github.com/mgratzer/forge) - A collection of agent skills for structured, GitHub-centric development.
* [musoyangrigor/gitx-skill](https://github.com/musoyangrigor/gitx-skill) - GitX is a portable AI-agent skill for creating clean Git commits, tagged branches, and safe pushes across Codex, Claude Code, Cursor, and other skills-compatible agents.

## Web

### Web Frameworks

* [vuejs-ai/skills](https://github.com/vuejs-ai/skills) - Agent skills for Vue 3 development
* [datopian/portaljs](https://github.com/datopian/portaljs) - 🌀 AI-native framework for building data portals. Scaffold a full portal from a brief and load datasets in minutes with agentic skills — any backend (CKAN, GitHub, Frictionless).
* [WordPress/agent-skills](https://github.com/WordPress/agent-skills) - Expert-level WordPress knowledge for AI coding assistants - blocks, themes, plugins, and best practices
* [TanStack/cli](https://github.com/TanStack/cli) - The official TanStack CLI - Project Scaffolding, MCP Server, Agent Skills Installation, etc
* [laravel/agent-skills](https://github.com/laravel/agent-skills) - Laravel official collection of agent skills
* [marckohlbrugge/37signals-skills](https://github.com/marckohlbrugge/37signals-skills) - Unofficial agent skills + reference guide that teach AI coding assistants to write Rails the 37signals way — extracted from Fizzy, Campfire, and DHH's code reviews
* [jdubois/dr-jskill](https://github.com/jdubois/dr-jskill) - An Agent Skill for creating Spring Boot applications
* [Automattic/agent-skills](https://github.com/Automattic/agent-skills) - Agent Skills for WordPress - folders of instructions, scripts, and resources *(archived)*
* [sivaprasadreddy/sivalabs-agent-skills](https://github.com/sivaprasadreddy/sivalabs-agent-skills) - Spring Boot skills for AI coding agents
* [gdarko/laravel-vue-starter](https://github.com/gdarko/laravel-vue-starter) - AI-native Laravel/Vue boilerplate. Tailwind + DaisyUI, Sanctum, Fortify, Pinia. Built-in agent skills for Claude Code, Cursor, Copilot, Gemini & Junie.
* [remix-run/agent-skills](https://github.com/remix-run/agent-skills) - Agent Skills for working with React Router *(archived)*
* [frappe/skills](https://github.com/frappe/skills) - Agent skills for Frappe App development
* [Automattic/wordpress-agent-skills](https://github.com/Automattic/wordpress-agent-skills) - A collection of agent skills that can be used to create WordPress themes and sites
* [Weaverse/shopify-hydrogen-skills](https://github.com/Weaverse/shopify-hydrogen-skills) - Dedicated agent skills for building, upgrading, and maintaining Shopify Hydrogen storefronts — works with Claude, Cursor, Copilot, and more.
* [aurorascharff/nextjs-app-architecture-skill](https://github.com/aurorascharff/nextjs-app-architecture-skill) - An agent skill for building and auditing Next.js 16+ App Router applications.
* [gogf/skills](https://github.com/gogf/skills) - GoFrame Agent Skills empowering AI to deeply understand GoFrame conventions and best practices, generating high-quality, production-ready code.
* [viewflow/seedkit](https://github.com/viewflow/seedkit) - Build any Django app — from a SaaS to a dashboard to an API — from a single sentence. An agent skill that wires packages, splits dev/prod settings, and adds CI.

### Frontend and UI Components

* [op7418/guizang-ppt-skill](https://github.com/op7418/guizang-ppt-skill) - AI-agent Skill for generating polished HTML slide decks: editorial magazine and Swiss layouts, image prompts, social covers, and a WebGL/low-power presentation runtime.
* [nicobailon/visual-explainer](https://github.com/nicobailon/visual-explainer) - Agent skill that generates rich HTML pages or slide decks for diagrams, diff reviews, plan audits, data tables, and project recaps
* [google-labs-code/stitch-skills](https://github.com/google-labs-code/stitch-skills) - A library of Agent Skills designed to work with the Stitch MCP server. Each skill follows the Agent Skills open standard, for compatibility with coding agents such as Antigravity, Gemini CLI, Claude Code, Cursor.
* [chuspeeism/dashi-ppt-skill](https://github.com/chuspeeism/dashi-ppt-skill) - An AI-agent skill that generates browser-editable presentations from multiple visual themes, exportable to HTML, PDF, and PPTX.
* [MengTo/Skills](https://github.com/MengTo/Skills) - Agent skills for designers and builders using Codex, Claude, Cursor, and other AI coding agents
* [jakubkrehel/skills](https://github.com/jakubkrehel/skills) - A collection of agent skills that help you build a great interface.
* [JimLiu/baoyu-design](https://github.com/JimLiu/baoyu-design) - Run Claude Design locally as an Agent Skill — Cursor, Claude Code & more. Produce polished UI mockups, prototypes, decks & wireframes as self-contained HTML, without claude.ai/design. Best with Opus 4.8.
* [jakubkrehel/make-interfaces-feel-better](https://github.com/jakubkrehel/make-interfaces-feel-better) - An agent skill that helps make your interface feel better.
* [plannotator/effective-html](https://github.com/plannotator/effective-html) - Agent skills for useful HTML artifacts, wireframes, interactive prototypes, plans, and diagrams.
* [Owl-Listener/designer-skills](https://github.com/Owl-Listener/designer-skills) - Designer Skills Collection: agentic skills, commands, and plugins for design — from research to systems, UI, interaction, and delivery.
* [yetone/kill-ai-slop](https://github.com/yetone/kill-ai-slop) - A field guide to the visual & copy tics of AI-generated products — and an Agent Skill that scans your project and strips them out. https://killaislop.com
* [bitjaru/styleseed](https://github.com/bitjaru/styleseed) - Open-source design-method engine for Claude Code, Codex & Cursor. 23 agent skills for fixed design judgment, multiple grammars, semantic palettes, reference compilation, and evidence-verified UI. MIT.
* [sunbigfly/ppt-agent-skills](https://github.com/sunbigfly/ppt-agent-skills) - A code-driven presentation generation framework. 像构建软件工程一样生成演示文稿。
* [plugin87/ux-ui-agent-skills](https://github.com/plugin87/ux-ui-agent-skills) - Turn Claude into a Senior Design Architect — DTCG design tokens, 42 components, WCAG 2.2 accessibility, any-framework code, 138 design systems, and runnable skills.
* [figma/community-resources](https://github.com/figma/community-resources) - A collection of open source plugins, widgets, agent skills, and developer resources for Figma products that have been shared on GitHub.
* [suleimanodetoro/skills](https://github.com/suleimanodetoro/skills) - Agent skills for interface design, React, React Native, and software security.
* [julianoczkowski/designer-skills](https://github.com/julianoczkowski/designer-skills) - A collection of agent skills for designers who prototype and build with AI coding tools. These skills encode design process so AI follows a structured path instead of producing random output.
* [shaom/infocard-skills](https://github.com/shaom/infocard-skills) - Open-source agent skills for generating editorial-style information cards from natural-language input.
* [aboul3ata/lazyweb-skill](https://github.com/aboul3ata/lazyweb-skill) - Lazyweb agent skills: start with /lazyweb:lazyweb-welcome, free screenshot references, optional paid 20k+ A/B Test Agent.
* [ryanbbrown/revealjs-skill](https://github.com/ryanbbrown/revealjs-skill) - Coding agent skill for making reveal.js presentations
* [vueuse/skills](https://github.com/vueuse/skills) - Agent Skills for VueUse
* [educlopez/ui-craft](https://github.com/educlopez/ui-craft) - Design engineering system for AI coding agents — ship UI with craft-level quality. Install as an agent skill.
* [PatternsDev/skills](https://github.com/PatternsDev/skills) - Agent skills for https://patterns.dev
* [jakubkrehel/oklch-skill](https://github.com/jakubkrehel/oklch-skill) - An agent skill that helps you work with OKLCH colors.
* [hubeiqiao/apple-bento-grid](https://github.com/hubeiqiao/apple-bento-grid) - Agent skill that generates Apple-inspired bento grid presentation cards. For Claude Code, Codex, and any AI coding agent.
* [DeckardGer/tanstack-agent-skills](https://github.com/DeckardGer/tanstack-agent-skills) - TanStack Agent Skills: Best practices for TanStack Query, Router, and Start for AI coding agents
* [arvindrk/extract-design-system](https://github.com/arvindrk/extract-design-system) - Extract design tokens (colors, typography, spacing, border radius, shadows) from any public website. Generates JSON and CSS custom properties for local projects. Available as an AI agent skill (Claude, Cursor, Codex) and standalone CLI.
* [skilld-dev/vue-ecosystem-skills](https://github.com/skilld-dev/vue-ecosystem-skills) - Agent Skills for the Vue ecosystem, written from current docs, issues, and releases
* [maplibre/maplibre-agent-skills](https://github.com/maplibre/maplibre-agent-skills) - Community-maintained agent skills for MapLibre GL JS — helping AI coding assistants write better mapping code
* [OpenLabs-so/oa-design](https://github.com/OpenLabs-so/oa-design) - The Open Analytics design language as an agent skill: component recipes with type-checked source, token CSS, and a CLI. Works with Claude Code, Cursor, or any agent.
* [TheGoat395/Codex-Skills](https://github.com/TheGoat395/Codex-Skills) - Codex-first Agent Skills library for premium frontend, website, motion, accessibility, QA, and handoff workflows.
* [AIwithhassan/lets-scroll](https://github.com/AIwithhassan/lets-scroll) - Agent skill that builds scroll-scrubbed "fly through the world" landing pages, AI-generated scenes + camera flights chained into one seamless continuous shot, driven by scroll. Claude Code / Codex / SKILL.md-compatible.
* [webflow/webflow-skills](https://github.com/webflow/webflow-skills) - Official Webflow Agent Skills
* [feature-sliced/skills](https://github.com/feature-sliced/skills) - AI agent skills for applying Feature-Sliced Design (FSD) v2.1 in frontend projects.
* [mdrbx/nerv-ui](https://github.com/mdrbx/nerv-ui) - Typed React command-center components, live examples, and a portable coding-agent skill.
* [Lombiq/Tailwind-Agent-Skills](https://github.com/Lombiq/Tailwind-Agent-Skills) - Agent-optimized Tailwind CSS v4 documentation skill with local snapshots and indexing.
* [Songzhi-lab/chinese-font-selector](https://github.com/Songzhi-lab/chinese-font-selector) - 全网首个中文字体专业知识包：可商用中文字体库（授权三级分类）、场景×气质选字矩阵、中英混排与排版规则。让 AI 选中文设计字体不再甩给你一堆 Inter / Chinese font selection agent skill: license-safe free commercial CJK fonts, scene-based selection matrix, CJK-Latin pairing rules. Works with Claude Code / Cursor / Kimi / Codex.
* [csuyincs-creator/fluidglass-ui](https://github.com/csuyincs-creator/fluidglass-ui) - WebGL fluid glass card interface generator — agent skill + zero-dependency reference implementation. Apache-2.0.
* [hakilee/design-farmer](https://github.com/hakilee/design-farmer) - Agent skill that turns design system quality from "best effort" into a repeatable engineering workflow.

### Scraping and Crawling

* [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill) - AI agent skill that researches any topic across Reddit, X, YouTube, HN, Polymarket, and the web - then synthesizes a grounded summary
* [browserbase/skills](https://github.com/browserbase/skills) - Browserbase's official collection of agent skills to access the web.
* [apify/agent-skills](https://github.com/apify/agent-skills) - Collection of Apify agent skills
* [boyang-hu/website-rebuild-skill](https://github.com/boyang-hu/website-rebuild-skill) - 复刻网站的 Agent Skill：抓只读镜像、从压缩代码逐行还原、自动比对验收。An agent skill that mirrors a website, rebuilds it from the minified code, and verifies the result with automated diffs.
* [oxylabs/agent-skills](https://github.com/oxylabs/agent-skills) - Official Agent skills of Oxylabs products
* [firecrawl/cli](https://github.com/firecrawl/cli) - CLI and Agent Skill for Firecrawl - Add scrape, search, and browsing capabilities to your AI agents
* [apify/awesome-skills](https://github.com/apify/awesome-skills) - Community collection of Apify agent skills for AI coding assistants
* [liangdabiao/tikhub_api_skill](https://github.com/liangdabiao/tikhub_api_skill) - TikHub API 助手是一个 Codex/Claude Code Agent Skill，用于帮助用户搜索、发现和调用 TikHub API。TikHub 提供了多平台社交媒体数据 API，支持抖音、TikTok、小红书、Instagram、YouTube、Twitter、Reddit 等平台。This is a TikHub API skill/documentation repository.
* [hect0x7/jmcomic-ai](https://github.com/hect0x7/jmcomic-ai) - 禁漫天堂 Agent Skills / AI 原生 JMComic 助手：通过 MCP 与 Skills 将 JMComic 注入你的 AI Agent. / AI-powered JMComic assistant for seamless integration with AI Agents via MCP & Skills.
* [SpaceZephyr/read-buddy](https://github.com/SpaceZephyr/read-buddy) - Read Buddy: Agent Skills for reading webpages, RSS, YouTube, X, Feishu docs, OCR, podcasts, topics and personal knowledge sources
* [GuppyTheCat/obsidian-clipper-template-creator](https://github.com/GuppyTheCat/obsidian-clipper-template-creator) - Agent Skill that enables AI agents (Claude Code, Cursor, Gemini CLI, etc.) to help you create importable JSON templates for the Obsidian Web Clipper.
* [Kris77z/web-experience-cloner](https://github.com/Kris77z/web-experience-cloner) - Reusable AI agent skill for cloning, mirroring, offline-validating, and rewriting complex web experiences.

## Data and Storage

### Databases

* [supabase/agent-skills](https://github.com/supabase/agent-skills) - Agent Skills to help developers using AI agents with Supabase
* [ClickHouse/agent-skills](https://github.com/ClickHouse/agent-skills) - The official Agent Skills for ClickHouse and ClickHouse Cloud
* [waynesutton/convexskills](https://github.com/waynesutton/convexskills) - AI agent skills and templates for building production ready apps with Convex. Patterns for queries, mutations, cron jobs, webhooks, migrations, and more.
* [mongodb/agent-skills](https://github.com/mongodb/agent-skills) - Use the official MongoDB Skills with your favorite coding agent to build faster.
* [redis/agent-skills](https://github.com/redis/agent-skills) - Redis' official collection of agent skills
* [neondatabase/agent-skills](https://github.com/neondatabase/agent-skills) - Agent Skills for Neon Severless Postgres

## Machine Learning and AI

### LLM and Inference

* [ckelsoe/prompt-architect](https://github.com/ckelsoe/prompt-architect) - Agent skill for analyzing and improving prompts using 31 frameworks across 7 intent categories. Works with Claude Code, Gemini CLI, Cursor, Copilot, and 30+ Agent Skills compatible tools.
* [intertwine/dspy-agent-skills](https://github.com/intertwine/dspy-agent-skills) - Production-grade DSPy 3.2.x agent skills + validated end-to-end examples for Claude Code and Codex CLI — fundamentals, evaluation, GEPA, BetterTogether, and RLM.
* [kangarooking/agnes-free-model-skills](https://github.com/kangarooking/agnes-free-model-skills) - Agnes AI 免费文本、图片、视频模型的 Codex/Agent Skills
* [kangarooking/system-prompt-skills](https://github.com/kangarooking/system-prompt-skills) - 从 165 个顶级 AI 产品系统提示词中蒸馏出的 15 个可执行 Agent skill
* [thesysdev/make-no-mistakes](https://github.com/thesysdev/make-no-mistakes) - make-no-mistakes (M-Stack) is exactly what the name implies: a mathematically rigorous agent skill that instructs the model to make zero mistakes.
* [veniceai/skills](https://github.com/veniceai/skills) - Agent Skills for the Venice.ai API. One folder per surface area, each with a SKILL.md for agent runtimes (Cursor, Claude, Codex, etc.).
* [LiarMTTT/TavernWeave](https://github.com/LiarMTTT/TavernWeave) - Noncommercial Agent Skills for SillyTavern rolecard engineering.
* [vllm-project/vllm-skills](https://github.com/vllm-project/vllm-skills) - Agent skills for vLLM
* [XiaomiMiMo/MiMo-Skills](https://github.com/XiaomiMiMo/MiMo-Skills) - Agent skills for Xiaomi MiMo series.
* [BerriAI/litellm-skills](https://github.com/BerriAI/litellm-skills) - Agent Skills for managing live LiteLLM proxy deployments — users, teams, keys, orgs, models, MCP servers, agents
* [Apeironics/prompt-refine-skill](https://github.com/Apeironics/prompt-refine-skill) - Agent Skill that silently refines prompts for the currently running model
* [JBurlison/MetaPrompts](https://github.com/JBurlison/MetaPrompts) - Meta Prompting to generate AI instructions, agents, skills & prompts
* [liangdabiao/skill-ten-prompt-generator](https://github.com/liangdabiao/skill-ten-prompt-generator) - 基于 Claude Code Agent Skills 的 AI 提示词工程系统 - 10个场景化专家，自动路由，精准生成优秀提示词 ## 项目简介 这是一个基于 Claude Code Agent Skills 技术的智能提示词生成系统。通过自然语言请求，系统会自动路由到对应的专业 Skill，帮助用户写出高质量的 AI 提示词。

### Computer Vision

* [qtzx06/yolodex](https://github.com/qtzx06/yolodex) - agent skills for autonomous data labeling, winner at openai codex hackathon 2026
* [NVIDIA-AI-IOT/DeepStream_Coding_Agent](https://github.com/NVIDIA-AI-IOT/DeepStream_Coding_Agent) - A project showcasing how to leverage AI coding assistants (Cursor, Claude Code, etc.) for accelerated NVIDIA DeepStream SDK application development using a curated agentic skill and structured prompts.
* [landing-ai/ade-document-processing-skills](https://github.com/landing-ai/ade-document-processing-skills) - Agent skills for LandingAI's Agentic Document Extraction (ADE) — production-ready document AI for agentic coding assistants
* [liangdabiao/deepseek-v4-flash-vision-rag](https://github.com/liangdabiao/deepseek-v4-flash-vision-rag) - DeepSeek V4-Flash Vision RAG 让 AI 真正"看懂" 一份 PDF，然后你对它提问：它告诉你答案、答案在第几页， 并把那一页的原图展示出来给你核对。 基于 DeepSeek 视觉大模型 deepseek-v4-flash-vision-exp 的 PDF 深度问答与检索 （vision RAG）agent skill。支持文字版 PDF，也支持扫描版；能看懂 图表、表格、代码块、公式，而不只是认字。
* [liangdabiao/deepseek-v4-flash-vision-video-rag](https://github.com/liangdabiao/deepseek-v4-flash-vision-video-rag) - DeepSeek V4-Flash Vision Video RAG 让 AI 真正"看懂" 一段视频，然后你对它提问：它告诉你答案、答案发生在 第几分几秒，并切出那一段的可播放片段和关键帧给你核对。 基于 DeepSeek 视觉大模型 deepseek-v4-flash-vision-exp 的视频理解与问答 （video RAG）agent skill。先按时间轴抽帧阅读、建立索引（一次性），再对问题做 本地粗筛 → 视觉精排 → 深读回答；回答带 [MM:SS] 时间戳引用，自动生成 自包含 HTML 预览页（内嵌可播放片段 + 关键帧 + 答案），双击浏览器即看。

### Data Science and Analytics

* [retentioneering/retentioneering-tools](https://github.com/retentioneering/retentioneering-tools) - Python toolkit, MCP server, and agent skills for reproducible, auditable clickstream and event log analytics. Helps AI agents, data scientists and analysts build, validate, and cross-check product analytics, quantitative UX, customer journeys, graph-based user flows, behavioral segmentation, A/B tests, process mining models, Markov chain simulation
* [dbt-labs/dbt-agent-skills](https://github.com/dbt-labs/dbt-agent-skills) - A curated collection of Agent Skills for working with dbt, to help AI agents understand and execute dbt workflows more effectively.
* [databricks/databricks-agent-skills](https://github.com/databricks/databricks-agent-skills)
* [streamlit/agent-skills](https://github.com/streamlit/agent-skills) - A collection of agent skills for development of Streamlit apps. *(archived)*
* [caylent/tufte-data-viz](https://github.com/caylent/tufte-data-viz) - Agent skill: Edward Tufte's data visualization principles for clean, honest, high-data-ink-ratio charts. Recharts, ECharts, Chart.js, matplotlib, Plotly, D3/SVG.
* [tryopendata/skills](https://github.com/tryopendata/skills) - Official Agent Skills for the OpenData platform
* [wagner-niklas/Alfred](https://github.com/wagner-niklas/Alfred) - Alfred: An open-source Data Assistant for domain adoption, powered by agent skills, semantic knowledge graphs and relational data. *(archived)*
* [Humphrey4data/tableau-to-hex-skill](https://github.com/Humphrey4data/tableau-to-hex-skill) - Agent skill for migrating Tableau, Looker, and Power BI dashboards to Hex apps: extract specs, rebuild with Hex AI, verify parity
* [polars-inc/skills](https://github.com/polars-inc/skills) - AI agent skills by Polars

## AI Agents

### Agent Frameworks and Runtimes

* [ageerle/ruoyi-ai](https://github.com/ageerle/ruoyi-ai) - An enterprise AI development framework for building AI agents. It provides unified management of multi-provider LLMs, secure enterprise knowledge bases with high-precision retrieval, visual workflow orchestration and multi-agent coordination. Compatible with mainstream Agent Skill standards, it enables developers to efficiently build production-gra
* [gotalab/cc-sdd](https://github.com/gotalab/cc-sdd) - Turn approved specs into long-running autonomous implementation. A minimal, adaptable SDD harness with Agent Skills for Claude Code, Codex, Cursor, Copilot, Windsurf, OpenCode, Gemini CLI, and Antigravity.
* [rpamis/comet](https://github.com/rpamis/comet) - Comet: agent skill harness for turning ideas into evaluated workflows
* [DenisSergeevitch/agents-best-practices](https://github.com/DenisSergeevitch/agents-best-practices) - Provider-neutral Agent Skill for Codex, Claude Code, and agentic harness design.
* [lessweb/deepcode-cli](https://github.com/lessweb/deepcode-cli) - Deep Code 是专为 deepseek-v4 模型优化的终端 AI 编码助手，支持深度思考、推理强度控制以及 Agent Skills。
* [spring-ai-community/spring-ai-agent-utils](https://github.com/spring-ai-community/spring-ai-agent-utils) - A Spring AI library that brings Claude Code-inspired tools and agent skills to your AI applications.
* [SJTU-IPADS/SkVM](https://github.com/SJTU-IPADS/SkVM) - The Language Virtual Machine for Agent Skills
* [hashgraph-online/registry-broker-skills](https://github.com/hashgraph-online/registry-broker-skills) - AI agent skills for the Universal Registry - search, chat, and register 72,000+ agents across 14+ protocols. Works with Claude, Codex, Cursor, OpenClaw, and any AI assistant.
* [keli-wen/agentic-harness-patterns-skill](https://github.com/keli-wen/agentic-harness-patterns-skill) - Agent skill for harness engineering — memory, permissions, context engineering, multi-agent coordination. Distilled from Claude Code, with Codex CLI and Gemini CLI on the roadmap. EN/ZH. Install via npx skills add.
* [69gg/Undefined](https://github.com/69gg/Undefined) - QQ bot platform with cognitive memory architecture and multi-agent Skills, via OneBot V11.
* [initializ/forge](https://github.com/initializ/forge) - Forge is the open-source runtime for Anthropic's Agent Skills standard — built for the agent that runs next to a service, in your environment, on infrastructure you already operate. Write a SKILL.md. Compile to a portable, hardened agent. Deploy it anywhere containers run: Kubernetes, on-prem, air-gapped, embedded in CI, or as an A2A endpoint.
* [Yanyutin753/LambChat](https://github.com/Yanyutin753/LambChat) - LambChat — Enterprise Agent Infra for governed AI agents. Skills + MCP powered, Loop Agent ready, multi-tenant by design.
* [skrun-dev/skrun](https://github.com/skrun-dev/skrun) - Deploy any Agent Skill as an API via POST /run. The open-source multi-model alternative to Claude Managed Agents, Microsoft Foundry & Mistral/Koyeb — works with any LLM.
* [Birfy/agentdescent](https://github.com/Birfy/agentdescent) - Gradient descent, but the parameters are agents — a parallel, asynchronous framework for self-evolving agents (skills, prompts, harnesses). Diffs are the gradients; the aggregator is the optimizer.
* [getnao/sylph](https://github.com/getnao/sylph) - The open-source company brain. Run your entire company with AI agents, skills, and a self-improving context.
* [Owl-Listener/ai-design-skills](https://github.com/Owl-Listener/ai-design-skills) - AI Design Skills Collection: agentic skills, commands, and plugins for designing AI products — from interaction patterns to alignment, evaluation, agent orchestration, and prompt architecture.
* [gaasher/Agent-Loop-Skills](https://github.com/gaasher/Agent-Loop-Skills) - Loop until it's better — drop-in agentic loops (autoresearch, scientific writing, data analysis, code/SQL/prompt optimization, red-teaming) as open-standard Agent Skills. Verification-gated; native on Claude Code, portable across Codex, Cursor & other Skills hosts.
* [szsip239/teamclaw](https://github.com/szsip239/teamclaw) - TeamClaw 是面向企业内部 AI Agent 落地的 operations control plane。它把运行时实例、Agent、Skills、模型资源、知识库、权限、审计和对话体验收口到一个多租户平台里，让团队可以在同一套界面里管理多个实例、多个部门、多个 Agent 和多个 runtime。
* [soba-labs/langchain-agent-skills](https://github.com/soba-labs/langchain-agent-skills) - A collection of agent-optimized LangChain, LangGraph and LangSmith skills for AI coding assistants.
* [GoogleCloudPlatform/cxas-scrapi](https://github.com/GoogleCloudPlatform/cxas-scrapi) - A powerful Python API, CLI, and set of Agent Skills for CX Agent Studio to automate, evaluate, and scale your agents with ease.
* [aws-samples/sample-strands-agents-agentskills](https://github.com/aws-samples/sample-strands-agents-agentskills) - Agent Skills implementation for Strands Agents SDK
* [mturac/everything-openai-codex](https://github.com/mturac/everything-openai-codex) - EOC: open-source operating system for OpenAI Codex workflows with agents, skills, hooks, rules, memory, safety gates, and cross-harness adapters.
* [runxhq/runx](https://github.com/runxhq/runx) - the governed runtime for agent skill workflows, off the leash but on the record
* [Bevel-Software/Hexis](https://github.com/Bevel-Software/Hexis) - Git-backed control plane for AI-agent skills, tools, context, permissions, and identity. Self-hosted and MCP-native.
* [shinpr/sub-agents-skills](https://github.com/shinpr/sub-agents-skills) - Cross-LLM sub-agent orchestration as an Agent Skills. Route tasks to Codex, Claude Code, Grok, GLM, Kimi, Cursor, Gemini, OpenCode, or Command Code from any compatible tool.
* [kucherenko/gangsta](https://github.com/kucherenko/gangsta) - AI agentic skills framework for spec-driven development, built on the organizational model of mafia.
* [CALLE-AI/awesome-phone-call-agents](https://github.com/CALLE-AI/awesome-phone-call-agents) - Portable phone-call Agent Skills, apps, examples, adapters, and scheduler recipes for AI agents.
* [tech4idea/viforge](https://github.com/tech4idea/viforge) - ViForge is a local-first AI collaboration workbench for creative and knowledge work. It helps people turn ideas, judgment, and personal methodology into reusable agents, skills, knowledge bases, and evaluable workflows.
* [mastra-ai/skills](https://github.com/mastra-ai/skills) - Official agent skills for coding agents working with the Mastra AI framework
* [levi-qiao/longgraph-skill](https://github.com/levi-qiao/longgraph-skill) - Long-horizon agent skill for Claude Code / Cursor / Codex / Grok Build — multi-task ledger loop, host-portable, clean-context supervisor, verified gates. Markdown library (loop-graph), not a framework.
* [tiann/execplan-skill](https://github.com/tiann/execplan-skill) - An [Agent Skill](https://agentskills.io) that enables AI coding agents to tackle complex, long-running implementation tasks autonomously.
* [ujjwalredd/Dopamine](https://github.com/ujjwalredd/Dopamine) - A human-dopamine-inspired AI agent skill that adapts effort, learns from feedback, and delivers the smallest verified solution.
* [livekit/agent-skills](https://github.com/livekit/agent-skills) - Reusable AI coding agent skills for building voice AI with LiveKit
* [roundpilot/superpowers-antigravity](https://github.com/roundpilot/superpowers-antigravity) - An agentic skills framework & software development methodology that works. Built natively for Antigravity 2.0, CLI & IDE
* [Osteoporosis/luna-chat-coder](https://github.com/Osteoporosis/luna-chat-coder) - Agent Skill and repository template for end-to-end software development entirely inside ordinary Web AI chat.
* [gfernandf/agent-skills](https://github.com/gfernandf/agent-skills) - Not another agent orchestrator — ORCA is a runtime for executable cognition.
* [mochow13/keen-code](https://github.com/mochow13/keen-code) - A context-aware terminal-based coding agent written in Go. Supports multiple-providers, MCPs, Subagents, Agent Skills, controllable tool output retention, hashline edits, and more.

### Agent Skills and Tooling

* [obra/superpowers](https://github.com/obra/superpowers) - An agentic skills framework & software development methodology that works.
* [anthropics/skills](https://github.com/anthropics/skills) - Public repository for Agent Skills
* [addyosmani/agent-skills](https://github.com/addyosmani/agent-skills) - Production-grade engineering skills for AI coding agents.
* [sickn33/agentic-awesome-skills](https://github.com/sickn33/agentic-awesome-skills) - AAS Core is the local, agent-first control plane for complete catalog discovery, agent-owned selection, stack validation, and planning, backed by 2,100+ agentic skills. Includes CLI, local MCP, catalog, plugins, and Workbench.
* [github/awesome-copilot](https://github.com/github/awesome-copilot) - Community-contributed instructions, agents, skills, and configurations to help you make the most of GitHub Copilot.
* [vercel-labs/skills](https://github.com/vercel-labs/skills) - The open agent skills tool - npx skills
* [alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills) - 380 Claude Code skills & agent skills & plugins (30+ Agents, 70+ custom commands, 380+ skills, customizable references, scripts)for Claude Code, Codex, Gemini CLI, Cursor, and 8 more coding agents — engineering, marketing, product, compliance, C-level advisory, research, business operations, commercial & finance, and your daily productivity skills.
* [agentskills/agentskills](https://github.com/agentskills/agentskills) - Specification and documentation for Agent Skills
* [KKKKhazix/khazix-skills](https://github.com/KKKKhazix/khazix-skills) - 数字生命卡兹克开源的 AI Skills 合集 | Agent Skills: leader（帮你定义目标）, neat-freak 洁癖, hv-analysis, khazix-writer & more — Claude Code, Codex & 40+ agents
* [kangarooking/cangjie-skill](https://github.com/kangarooking/cangjie-skill) - 把书、长视频、播客等高价值内容蒸馏成可执行的 Agent Skills（Distill high-value content from books, long-form videos, podcasts, and more into executable Agent Skills）
* [refly-ai/refly](https://github.com/refly-ai/refly) - The first open-source agent skills builder. Define skills by vibe workflow, run on Claude Code, Cursor, Codex & more. Build Clawdbot 🦞· APIs for Lovable · Bots for Slack & Lark/Feishu · Skills are infrastructure, not prompts.
* [anbeime/skill](https://github.com/anbeime/skill) - 收录最全、更新最快的技能Skills商店：精选原创技能包（涵盖文档处理、内容创作、编程开发、机器学习、自动化工作流），全部打包好可直接安装使用！同时自动抓取GitHub上万个Skills项目，按分类、更新时间、Star数量整理。The most comprehensive and frequently updated AI Agent skill library, featuring curated skill packs across document processing, content creation, programming, machine learning, automated workflows, and many more domains.
* [antfu/skills](https://github.com/antfu/skills) - Anthony Fu's curated collection of agent skills.
* [tech-leads-club/agent-skills](https://github.com/tech-leads-club/agent-skills) - The secure, validated skill registry for professional AI coding agents. Extend Antigravity, Claude Code, Cursor, Copilot and more with absolute confidence.
* [iflytek/skillhub](https://github.com/iflytek/skillhub) - Self-hosted, open-source agent skill registry for enterprises. Publish & version skill packages, govern with RBAC and audit logs, deploy on-premise with Docker or Kubernetes.
* [davidondrej/skills](https://github.com/davidondrej/skills) - access to david ondrej's personal agent skills
* [yaojingang/yao-meta-skill](https://github.com/yaojingang/yao-meta-skill) - YAO = Yielding AI Outcomes. A rigorous engineering, evaluation, governance, and portability system for reusable agent skills.
* [softaworks/agent-toolkit](https://github.com/softaworks/agent-toolkit) - A curated collection of skills for AI coding agents. Skills are packaged instructions and scripts that extend agent capabilities across development, documentation, planning, and professional workflows.
* [GuDaStudio/skills](https://github.com/GuDaStudio/skills) - This repository contains a collection of Agent Skills developed by GudaStudio, enabling seamless collaboration between Claude and other AI models and tools.
* [rmyndharis/antigravity-skills](https://github.com/rmyndharis/antigravity-skills) - A curated collection of Agent Skills for Google Antigravity
* [Pluviobyte/rnskill](https://github.com/Pluviobyte/rnskill) - 雪踏乌云的 AI Agent Skills 集合
* [alchaincyf/huashu-skills](https://github.com/alchaincyf/huashu-skills) - 花叔全部开源 Agent Skills 总目录：16 旗舰 + 14 人物视角 + 22 内置共 52 个 skill，分层分类 + AI Agent 安装协议 + 机器可读 skills.json + 更新检查机制
* [CloudAI-X/claude-workflow-v2](https://github.com/CloudAI-X/claude-workflow-v2) - Universal Claude Code workflow plugin with agents, skills, hooks, and commands
* [noobnooc/agent](https://github.com/noobnooc/agent) - My profile & the agent skills I created
* [microsoft/waza](https://github.com/microsoft/waza) - CLI / Framework for Agent Skills - create, test, measure and improve skill quality and effectiveness
* [tjboudreaux/cc-thinking-skills](https://github.com/tjboudreaux/cc-thinking-skills) - 28 eval-informed mental models and critical-thinking skills for Claude Code, GitHub Copilot, Codex, Cursor, and other Agent Skills-compatible tools
* [caliber-ai-org/ai-setup](https://github.com/caliber-ai-org/ai-setup) - Continuously sync your AI setups with one command. Codebase tailor suited agent skills, MCPs and config files for Claude Code, Cursor, and Codex.
* [sentient-agi/EvoSkill](https://github.com/sentient-agi/EvoSkill) - EvoSkill — An open-source framework that automatically discovers and synthesizes reusable agent skills from failed trajectories to improve coding agent performance.
* [MoizIbnYousaf/ai-agent-skills](https://github.com/MoizIbnYousaf/ai-agent-skills) - Universal skill installer and package manager for AI coding agents. One command, 12+ runtimes. npx ai-agent-skills
* [alibaba-flyai/flyai-skill](https://github.com/alibaba-flyai/flyai-skill) - fly ai agent skill
* [openclaw/agent-skills](https://github.com/openclaw/agent-skills) - Useful skills for agents and claws.
* [Spielewoy/autoprompt-skill](https://github.com/Spielewoy/autoprompt-skill) - Autoprompt is a coding-agent skill that cuts failures by 45% on agentic coding tasks.
* [getsentry/skills](https://github.com/getsentry/skills) - Agent Skills used by the Sentry team for development.
* [LearnPrompt/luban-skill](https://github.com/LearnPrompt/luban-skill) - 鲁班 | Luban — 把'能用的Skill'打磨成'能被装、能传播、能验证、能进化'的公共资产。Agent skill-polishing workshop: 验料·访行·过尺·慢刨·回炉
* [tiangolo/library-skills](https://github.com/tiangolo/library-skills) - Library Agent Skills
* [lixiaolin94/skills](https://github.com/lixiaolin94/skills) - Collection of AI agent skills for Claude Code
* [huggingface/upskill](https://github.com/huggingface/upskill) - Generate and evaluate agent skills for code agents like Claude Code, Open Code, OpenAI Codex
* [inference-sh/skills](https://github.com/inference-sh/skills) - inference.sh Agent skills for using our API to give your agents access to hundreds of apps and other agents
* [staruhub/ClaudeSkills](https://github.com/staruhub/ClaudeSkills) - 13 curated Agent Skills for research, product decisions, decks, publishing, audits, and more — portable across skills-compatible agents.
* [Gentleman-Programming/Gentleman-Skills](https://github.com/Gentleman-Programming/Gentleman-Skills) - Community-driven AI agent skills for Claude Code, OpenCode, and other AI assistants. Curated patterns and community contributions.
* [michaelshimeles/skills](https://github.com/michaelshimeles/skills) - Agent skills and an AGENTS.md workflow template — isolate in worktrees, build to a service layer, prove with evidence, ship with before/after proof and Greptile review loops. For Claude Code, Cursor, and Codex.
* [enulus/OpenPackage](https://github.com/enulus/OpenPackage) - The open, universal, coding agent skills, agents, rules, and commands organizer and package manager.
* [kangarooking/kangarooking-skills](https://github.com/kangarooking/kangarooking-skills) - My custom AI Agent skills
* [sleekdotdesign/agent-skills](https://github.com/sleekdotdesign/agent-skills)
* [zjp1997720/zhijian-skills](https://github.com/zjp1997720/zhijian-skills) - Canonical source and governance toolkit for Zhijian AI public Agent Skills
* [Kamalnrf/claude-plugins](https://github.com/Kamalnrf/claude-plugins) - Lightweight registry to discover, install, and manage all public Claude plugins and agent skills for your favourite AI coding agent.
* [chenjin-cmd/agent-skills-launch-pack_](https://github.com/chenjin-cmd/agent-skills-launch-pack_)
* [DannyMac180/skills](https://github.com/DannyMac180/skills) - AI agent skills created by me: Dan McAteer
* [antfu/skills-npm](https://github.com/antfu/skills-npm) - Install agent skills from npm
* [ZeroPointRepo/awesome-hermes-skills](https://github.com/ZeroPointRepo/awesome-hermes-skills) - Hermes Agent skills and plugins: 350+ tools, memory providers, and guides for Nous Research's agent.
* [Dokhacgiakhoa/Agent-Skills-4-Vibe-Coding-CLI](https://github.com/Dokhacgiakhoa/Agent-Skills-4-Vibe-Coding-CLI)
* [mxyhi/ok-skills](https://github.com/mxyhi/ok-skills) - Curated AI coding agent skills and AGENTS.md playbooks for Codex, Claude Code, Cursor, OpenClaw, and other SKILL.md-compatible tools.
* [coleam00/skills](https://github.com/coleam00/skills) - The agent skills I actually use to build software with coding agents. The PIV loop, planning, worktrees, and the meta-skills for building your own AI Layer.
* [cosmicstack-labs/mercury-agent-skills](https://github.com/cosmicstack-labs/mercury-agent-skills) - A curated registry of reusable Mercury Agent, Open Claw or Hermes Agent skills designed for real developer workflows, persistent memory, and token-efficient execution.
* [AgentSkillOS/SkillAnything](https://github.com/AgentSkillOS/SkillAnything) - Making ANY Software Skill-Native -- Auto-generate production-ready AI Agent Skills for Claude Code, OpenClaw, Codex, and more.
* [ai-driven-dev/framework](https://github.com/ai-driven-dev/framework) - Marketplace Framework AI-Driven Dev : Context Engineering, Plugins, Agents, Skills, Hooks, Templates, SDLC
* [computerlovetech/agr](https://github.com/computerlovetech/agr) - Educational package-manager project for AI agent skills. Not actively maintained.
* [jabrena/plinth](https://github.com/jabrena/plinth) - Plinth is an AI-native engineering toolkit for modern Java enterprise SDLC, built around reusable Commands, Agents, Skills, and MCP Servers.
* [JuneYaooo/lineage-skill](https://github.com/JuneYaooo/lineage-skill) - Distill videos, PDFs, transcripts, and notes into source-backed teacher Agent Skills.
* [LinklyAI/best-skills](https://github.com/LinklyAI/best-skills) - Daily-updated Top 100 Agent Skills rankings — installs, growth, and social buzz aggregated from skills.sh, ClawHub, Tencent SkillHub, GitHub, X and 10+ communities. Open data (CSV).
* [disler/the-library](https://github.com/disler/the-library) - A Meta-Skill for Private-First Distribution of Agentics (Skills, Agents, and Prompts) across your Agents, Devices, and Teams.
* [sanjay3290/ai-skills](https://github.com/sanjay3290/ai-skills) - 24 cross-platform agent skills for Claude Code, Cursor, Codex & Gemini CLI — databases, messaging, research, TTS, DevOps, and Google Workspace
* [gotalab/skillport](https://github.com/gotalab/skillport) - Bring Agent Skills to Any AI Agent and Coding Agent — via CLI or MCP. Manage once, serve anywhere.
* [owainlewis/blueprint](https://github.com/owainlewis/blueprint) - The best agent skills in the world for software development.
* [joeseesun/qiaomu-meta-skill](https://github.com/joeseesun/qiaomu-meta-skill) - 把工作流变成可研究、可评测、可发布的乔木 Agent Skill | Turn workflows into researched, tested, release-ready agent skills.
* [DougTrajano/pydantic-ai-skills](https://github.com/DougTrajano/pydantic-ai-skills) - This package implements Agent Skills (https://agentskills.io) support with progressive disclosure for Pydantic AI. Supports filesystem and programmatic skills.
* [zhuyansen/agent-skills-hub](https://github.com/zhuyansen/agent-skills-hub) - Discover and compare open-source Agent Skills, tools & MCP servers — with quality scoring, trending analysis, and automated GitHub sync
* [cloudflare/agent-skills-discovery-rfc](https://github.com/cloudflare/agent-skills-discovery-rfc) - A mechanism for discovering Agent Skills using the .well-known URI path prefix as specified in RFC 8615 for discovering Agent Skills.
* [neutree-ai/openapi-to-skills](https://github.com/neutree-ai/openapi-to-skills) - OpenAPI to Agent Skill for context-efficient AI agents
* [zhukunpenglinyutong/ai-max](https://github.com/zhukunpenglinyutong/ai-max) - 一键给Claude Code 提高智商，包含生产级 agents、skills、hooks、commands、rules 和 MCP 配置
* [JetBrains/skills](https://github.com/JetBrains/skills) - Curated agent skills collection verified by JetBrains
* [amd/skills](https://github.com/amd/skills) - Official AMD catalog of AI agent skills. Empower your AI agents with AMD's optimized SW stack.
* [TanStack/intent](https://github.com/TanStack/intent) - A CLI for library maintainers to generate, validate, and ship Agent Skills alongside their npm packages.
* [mizchi/skills](https://github.com/mizchi/skills) - Agent skills by mizchi, distributed via APM
* [skilld-dev/skilld](https://github.com/skilld-dev/skilld) - Curated agent skills by humans. Search, run, install, and keep them current from one CLI.
* [MemTensor/skills-vote](https://github.com/MemTensor/skills-vote) - SkillsVote: Lifecycle Governance of Agent Skills from Collection, Recommendation to Evolution
* [chrlsio/agent-skills](https://github.com/chrlsio/agent-skills) - Lightweight, high-performance cross-platform desktop app to browse, sync, and manage AI agent skills across Claude Code, Cursor, Gemini CLI, Copilot, and more.（轻量高性能的跨平台 AI Agent Skills 管理工具）
* [intellectronica/agent-skills](https://github.com/intellectronica/agent-skills) - @intellectronica's agent skills
* [Leon-Drq/openagentskill](https://github.com/Leon-Drq/openagentskill) - The skill layer for AI agents: npm for AI Agent Skills.
* [qian-gugugaga/Character_Skill_Producer](https://github.com/qian-gugugaga/Character_Skill_Producer) - Character Skill Producer — distill anime characters into executable agent skills
* [hoodini/ai-agents-skills](https://github.com/hoodini/ai-agents-skills) - 🧠 AI Agent Skills Repository - A curated collection of specialized skills for AI coding agents (Claude Code, GitHub Copilot, Cursor, Windsurf). Created by Yuval Avidani using GitHub Copilot via VS Code Insiders.
* [Sven-Mirana/sublation](https://github.com/Sven-Mirana/sublation) - Local-first, multi-agent Skill governance, collaboration panel, and shadow routing (v5.0).
* [joshuadavidthomas/opencode-agent-skills](https://github.com/joshuadavidthomas/opencode-agent-skills) - An OpenCode plugin that provides tools for using agent skills
* [xigua-wang/skill-doctor](https://github.com/xigua-wang/skill-doctor) - Local-first inspector for coding-agent skills, conflicts, precedence, and risk analysis.
* [Qwen-Applications/Trace2Skill](https://github.com/Qwen-Applications/Trace2Skill) - Official codebase of the paper -- Trace2Skill: Distill Trajectory-Local Lessons into Transferable Agent Skills
* [cafe3310/public-agent-skills](https://github.com/cafe3310/public-agent-skills) - personal agent skills for better QoL
* [Misaka-Mikoto-Tech/agent-skills](https://github.com/Misaka-Mikoto-Tech/agent-skills) - Reusable AI agent skills for Codex, including a PowerShell skill for safe Windows command invocation and optional MCP utilities.
* [alvinunreal/lazyskills](https://github.com/alvinunreal/lazyskills) - mission control for agent skills
* [jdrhyne/agent-skills](https://github.com/jdrhyne/agent-skills) - A collection of AI agent skills for Clawdbot, Claude Code, Codex
* [osovv/grace-marketplace](https://github.com/osovv/grace-marketplace) - GRACE (Graph-RAG Anchored Code Engineering): open Agent Skills for contract-driven AI code generation with semantic markup, knowledge graphs, and support for Claude Code, Codex CLI, and Kilo Code.
* [agent-ecosystem/skill-validator](https://github.com/agent-ecosystem/skill-validator) - Validate Skill content against Agent Skill specification, with additional content density and quality checks.
* [NetEase/skills](https://github.com/NetEase/skills) - agent skills
* [gnipbao/dao-skill](https://github.com/gnipbao/dao-skill) - 道生万物：从混沌需求生成可运行、可验证、可进化的 Agent Skill
* [OdradekAI/bundles-forge](https://github.com/OdradekAI/bundles-forge) - An agentic skills framework & bundle-plugin engineering toolkit that works.
* [asgard-ai-platform/skills](https://github.com/asgard-ai-platform/skills) - 301 open-source coding agent skills across 22 domains — methodology, judgment & gotchas packaged as Claude Agent Skills for the Asgard AI Platform.
* [Kyure-A/agent-skills-nix](https://github.com/Kyure-A/agent-skills-nix) - Declarative management of Agent Skills on Nix
* [BuildGreatProducts/plaid](https://github.com/BuildGreatProducts/plaid) - Agent skill for the PLAID development methodology
* [golbin/agent-skills](https://github.com/golbin/agent-skills) - Reusable agent skills for Codex and compatible tools
* [NeverSight/learn-skills.dev](https://github.com/NeverSight/learn-skills.dev) - Curated high-quality AI Agent Skills. Search, install, copy and share. Works with Claude Code, Cursor, OpenClaw, and other AI coding tools.
* [davidliuk/graph-of-skills](https://github.com/davidliuk/graph-of-skills) - [EMNLP '26] Dependency-Aware Structural Retrieval for Massive Agent Skills
* [samber/cc-skills](https://github.com/samber/cc-skills) - 🧑‍🎨 A collection of agentic skills that works
* [SkyworkAI/Skywork-Skills](https://github.com/SkyworkAI/Skywork-Skills) - Skywork Agent Skills for AI office suites, including AI PPT, AI Document, AI Excel, AI Image, AI Search/DeepResearch and AI Music. These skills can be used by any skills-compatible agent, including Claude Code, Codex CLI and OpenClaw.
* [pproenca/dot-skills](https://github.com/pproenca/dot-skills) - A collection of AI agent skills following the Agent Skills open format
* [scottcwy/skill-kits](https://github.com/scottcwy/skill-kits) - Skill-kits is a zero-dependency, single-binary AI Agent Skills management tool for any LLM and multi-agent workflows.
* [thomast1906/github-copilot-agent-skills](https://github.com/thomast1906/github-copilot-agent-skills) - Repo containing my GitHub Copilot Agent & Skills - continually experimenting!
* [thedaviddias/skill-check](https://github.com/thedaviddias/skill-check) - Linter for agent skill files
* [william-garden/sync-skill](https://github.com/william-garden/sync-skill) - One-click synchronization tool for **AI Agent Skills** (`SKILL.md`) across coding agents and IDEs.
* [ZhanlinCui/Agent-Skills-Hunter](https://github.com/ZhanlinCui/Agent-Skills-Hunter) - Agent Skills 终极集合地，一站式装载，“让每一寸上下文都发挥到极致”🚀 The Ultimate Collection of 400+ High-Quality Agent Skills for Claude AI — Creative, Technical & Enterprise Workflows
* [CWS6206/ai-coding-starter-kit](https://github.com/CWS6206/ai-coding-starter-kit) - Kuratierte Agent Skills, Checklisten, Templates und Leitfäden für Schweizer Entwicklungsteams – direkt aus meinen Blog-Artikeln destilliert.
* [dylanfeltus/skills](https://github.com/dylanfeltus/skills) - A library of AI agent skills for research and design
* [Karanjot786/agent-skills-cli](https://github.com/Karanjot786/agent-skills-cli) - Universal CLI for Agent Skills. Access 200,000+ skills from SkillsMP and sync them to Cursor, Claude Code, GitHub Copilot, OpenAI Codex, and Antigravity.
* [nextlevelbuilder/skillx](https://github.com/nextlevelbuilder/skillx) - SkillX.sh — The Only Skill That Your AI Agent Needs. AI agent skills marketplace with semantic search, leaderboard, ratings, and CLI.
* [kairyou/agent-tools](https://github.com/kairyou/agent-tools) - Reusable Agent Skills, plus integrations (statusline, provider usage, vision) that install into Codex, Claude Code, and opencode.
* [seb1n/awesome-ai-agent-skills](https://github.com/seb1n/awesome-ai-agent-skills) - 103 ready-to-use AI agent skills for Claude Code, OpenAI Codex, Gemini CLI, Cursor, GitHub Copilot, Windsurf, and other Agent Skills-compatible tools. Complete SKILL.md workflows—not a link directory.
* [AgriciDaniel/skill-forge](https://github.com/AgriciDaniel/skill-forge) - Ultimate Claude Code skill creator — design, scaffold, build, review, evolve, and publish production-grade AI agent skills
* [danielvm-git/bigpowers](https://github.com/danielvm-git/bigpowers) - Agent skills synthesizing years of software engineering discipline into a prescriptive methodology for solo developers
* [KimYx0207/Kim_Service](https://github.com/KimYx0207/Kim_Service) - 面向 Claude Code、Codex 等 AI 编码助手的 Hook 与 Agent Skill 开源合集。
* [wednesday-solutions/ai-agent-skills](https://github.com/wednesday-solutions/ai-agent-skills) - Pre-configured agent skills for Vibe Coded projects. These skills provide AI coding assistants (Claude Code, Cursor, etc.) with specific guidelines for code quality and design standards.
* [microsoft/SkillLens](https://github.com/microsoft/SkillLens) - SkillLens: a framework for studying model-generated agent skills across the full raw experience generation → skill extraction → skill consumption lifecycle.
* [hqhq1025/skill-optimizer](https://github.com/hqhq1025/skill-optimizer) - Agent Skills lifecycle toolkit: mine repeated coding-agent workflows, audit and personalize skills, and generalize personal skills for public release.
* [davidYichengWei/agentic-engineering-framework](https://github.com/davidYichengWei/agentic-engineering-framework) - 开箱即用、可按项目定制的 AI Coding Agent Skills 框架：提供通用 Workflow、可扩展的项目私有知识、自我学习闭环和问题排查能力，适配任意技术栈和工程场景。兼容主流 Coding Agent。
* [swyxio/skills](https://github.com/swyxio/skills) - Agent skills for Claude Code and other AI agents
* [yofine/skills](https://github.com/yofine/skills) - yofine's agent skills
* [tilework-tech/nori-skillsets](https://github.com/tilework-tech/nori-skillsets) - System for managing collections of agent skills. Switch between skillsets seamlessly!
* [aahl/skills](https://github.com/aahl/skills) - AAHL's Agent Skills. 汇集了多种实用的智能体技能，涵盖Home Assistant智能家居控制、微软Edge TTS和智谱GLM-TTS文本转语音、DuckDuckGo搜索、DeepWiki文档检索、加密货币行情、天气预报、Lark/飞书、影视搜索、商品比价等功能
* [jwynia/agent-skills](https://github.com/jwynia/agent-skills)
* [lyndonkl/claude](https://github.com/lyndonkl/claude) - Agents, skills and anything else to use with claude
* [TerminalSkills/skills](https://github.com/TerminalSkills/skills) - Open-source library of AI agent skills — SKILL.md files for Claude Code, Codex, Gemini CLI, Cursor
* [Tencent/SkillHone](https://github.com/Tencent/SkillHone) - Continual agent skill evolution through persistent decision history. Whole-skill optimisation (SKILL.md + scripts + references) with every decision landing as a local Git issue / PR / wiki. Runs on any agentskills.io runtime — Claude Code, Codex, OpenClaw, Hermes.
* [instructa/agent-skills](https://github.com/instructa/agent-skills) - A curated collection of agent-skills
* [MassLab-SII/open-agent-skills](https://github.com/MassLab-SII/open-agent-skills) - We are dedicated to building a set of open agent skills that deliver superior performance, higher determinism, and greater consistency on targeted tasks, while operating at a lower cost and with reduced context usage.
* [sugarforever/01coder-agent-skills](https://github.com/sugarforever/01coder-agent-skills)
* [CodeAlive-AI/ai-driven-development](https://github.com/CodeAlive-AI/ai-driven-development) - Practices, protocols, and skills for AI-driven software development. Skills and safety hooks for Claude Code, Codex, OpenCode, Cursor, Antigravity, and any agent supporting the Agent Skills standard.
* [isjiamu/jiamu-skills](https://github.com/isjiamu/jiamu-skills) - 甲木常用的 Agent Skills 集合，包含日常工作流中积累的高效技能扩展。 / A curated collection of Agent Skills for daily productivity workflows.
* [rodydavis/agent-skills-generator](https://github.com/rodydavis/agent-skills-generator) - Generate agent skills from website documentation
* [dceoy/speckit-agent-skills](https://github.com/dceoy/speckit-agent-skills) - Agent skills for Spec Kit
* [JasonColapietro/suede-creator-skills](https://github.com/JasonColapietro/suede-creator-skills) - 74 open-source Agent Skills for Claude Code and Codex: AI SEO, AEO and GEO, code review with an A-F ship grade, CI gates, AI evals, design systems, conversion copy, Instagram growth, iOS and Android app shipping, creator rights, and consumer refund recovery.
* [nnnggel/skills-management](https://github.com/nnnggel/skills-management) - A CLI tool to manage and synchronize AI coding agent skills
* [apple-ouyang/book-to-skill](https://github.com/apple-ouyang/book-to-skill) - 把书拆成 AI Agent 可执行的 Skill，让书中的智慧变成你的决策副驾驶 | Turn books into executable AI Agent Skills
* [K-Dense-AI/mimeographs](https://github.com/K-Dense-AI/mimeographs) - Ready-to-use agent skills that clone the thinking of founders, philosophers, and scientists into your agent. Generated with K-Dense-AI/mimeo.
* [cchao123/skills-manager](https://github.com/cchao123/skills-manager) - A package manager for AI agent skills with cross-agent sharing, sync, and deployment.
* [mathbullet/skills](https://github.com/mathbullet/skills) - mathbullet Agent Skills
* [boristane/agent-skills](https://github.com/boristane/agent-skills)
* [carson2222/skills](https://github.com/carson2222/skills) - Agent skills I use in my own coding workflow, published for others to reuse.
* [EliasOulkadi/shokunin](https://github.com/EliasOulkadi/shokunin) - 職人 Shokunin 62 AI agent skills for OpenCode, Claude Code, Cursor, Windsurf. ChromaDB memory, MCP servers, declarative self-updates. Multi-model, open source, zero cost.
* [Peiiii/skild](https://github.com/Peiiii/skild) - The npm for Agent Skills — Discover, install, manage, and publish AI Agent Skills with ease
* [metaskills/skill-builder](https://github.com/metaskills/skill-builder) - Claude Code Agent Skills Builder
* [crafter-station/skills](https://github.com/crafter-station/skills) - Agent skills extracted from real work. Each one shipped something first.
* [neurofoo/agent-skills](https://github.com/neurofoo/agent-skills) - Agent Skills for Claude Code and OpenCode
* [luochang212/skill-zoo](https://github.com/luochang212/skill-zoo) - All-in-One Desktop Agent Skills Utility. Welcome to the Skill Zoo, where all your skills live!
* [ashutoshsinghpr7/wikiskill](https://github.com/ashutoshsinghpr7/wikiskill) - WikiSkill (arXiv:2608.27454) for Hermes Agent — self-evolving agent skills via a persistent knowledge wiki. Faithful Algorithm 1 implementation with real agent runs, isolated skill gating, and a documented live run log.
* [Hmbown/Wizards-of-the-Ghosts](https://github.com/Hmbown/Wizards-of-the-Ghosts) - Unofficial Hermes Agent skill pack built from fantasy spell and skill names
* [gnipbao/content-to-skill](https://github.com/gnipbao/content-to-skill) - Convert source material into executable Agent Skill packages
* [olorehq/olore](https://github.com/olorehq/olore) - Turn library docs into local Agent Skills
* [Teaonly/SKILL.mk](https://github.com/Teaonly/SKILL.mk) - Specification and Tools for Makefile-formatted Agent Skills.
* [gotalab/goal-setter-skill](https://github.com/gotalab/goal-setter-skill) - Shape rough requests into evidence-backed /goal completion contracts — an Agent Skill for Claude Code and Codex
* [mblode/agent-skills](https://github.com/mblode/agent-skills) - Skills for shipping better software.
* [EliasOenal/term-cli](https://github.com/EliasOenal/term-cli) - Interactive terminals for AI agents, built for what you can't --yes away. SSH+MFA, GRUB/U-Boot, debconf installers, SOL/serial consoles, fsck, cryptsetup, pdb/gdb, apt, certbot, pwsh and even Vim in tmux-backed sessions. Agent-driven, human-assisted for secrets/MFA. Single-file Python. Agent Skill. CI with 700+ tests. BSD License.
* [jdevalk/skills](https://github.com/jdevalk/skills) - Agent skills for GitHub repos and profiles, WordPress and EmDash plugins, Astro SEO, and content readability.
* [armelhbobdad/bmad-module-skill-forge](https://github.com/armelhbobdad/bmad-module-skill-forge) - A standalone BMAD module that transforms code repositories, documentation websites, and developer discourse into agentskills.io-compliant, version-pinned, provenance-backed agent skills.
* [it235/multica-best-practices](https://github.com/it235/multica-best-practices) - Copy. Paste. Run. — Production-tested Agent · Skill · Squad templates for Multica, bilingual (Chinese/English)
* [LearnPrompt/andrej-karpathy-skills](https://github.com/LearnPrompt/andrej-karpathy-skills) - Karpathy-inspired Agent Skills collection
* [agent-skills-hub/agent-skills-hub](https://github.com/agent-skills-hub/agent-skills-hub) - Agent Skills Hub is a global library of AI agent skills that work across OpenClaw, Claude Code, Gemini, Cursor, Antigravity, and more.
* [CaliCastle/skills](https://github.com/CaliCastle/skills) - A collection of Agent Skills by Cali Castle.
* [thiientv/godmode](https://github.com/thiientv/godmode) - Production-grade Agent Skills for AI coding agents—composable workflows for planning, TDD, debugging, review, UI/UX, releases, incidents, and evals.
* [devbrother2024/skills](https://github.com/devbrother2024/skills) - Reusable Agent Skills for AI coding workflows
* [lasoons/AgentSkillsManager](https://github.com/lasoons/AgentSkillsManager) - AgentSkills multi-IDE management extension: browse and install skill repositories for Antigravity, CodeBuddy, Cursor, Qoder, Trae, Windsurf (and VS Code), and search a cloud catalog (~58K skills) from https://claude-plugins.dev/.
* [pawbytes/skill-suites](https://github.com/pawbytes/skill-suites) - 50+ AI agent skills for Claude, Codex, OpenClaw etc — agentic marketing automation, AI creative agency, and developer productivity tools
* [MagicPathAI/agent-skills](https://github.com/MagicPathAI/agent-skills)
* [sergiodxa/agent-skills](https://github.com/sergiodxa/agent-skills) - My own agent skills for tools I use
* [spences10/claude-skills-cli](https://github.com/spences10/claude-skills-cli) - 🤖 CLI for creating Claude Agent Skills with progressive disclosure validation. Built for Claude Code to use when humans ask it to create skills.
* [jparkerweb/ai-assist-skills](https://github.com/jparkerweb/ai-assist-skills) - 🤖 A collection of AI agent skills that automate recurring engineering workflows that can be installed across multiple AI coding assistants.
* [wquguru/skills](https://github.com/wquguru/skills) - Practical Agent Skills — English-for-engineers coaching, Pi Agent setup, and more. Install via npx skills add.
* [mmlong818/skillforge](https://github.com/mmlong818/skillforge) - SkillForge — AI Agent Skills Generator. A structured 4-step prompt system that forges production-grade Agent Skills from scratch.
* [thedesignproject/agent-skills](https://github.com/thedesignproject/agent-skills) - A community-driven collection of skills, prompts, and workflows to help builders get the most out of Claude Code and other AI agents.
* [hnaymyh123-henry/skills-compat-manager](https://github.com/hnaymyh123-henry/skills-compat-manager) - Cross-platform compatibility layer for AI agent skills — pre-flight dependency checks, MCP-native, works with Claude Code, Cursor, Codex CLI, OpenCode and more
* [YiShu5/claude-skills](https://github.com/YiShu5/claude-skills) - Battle-tested coding-agent skills for product, content, writing, presentations, and workflow automation.
* [vasilyu1983/AI-Agents-public](https://github.com/vasilyu1983/AI-Agents-public) - Production-grade agent skills and Custom GPT prompts for ChatGPT, Claude Code, and Codex. 140 skills, 28 agents, Agent Skills spec compliant.
* [zapier/wade-skills](https://github.com/zapier/wade-skills) - The most frequently used agent skills of Wade Foster, CEO of Zapier
* [liuxingqitd/skills-hub](https://github.com/liuxingqitd/skills-hub) - A local dashboard to manage AI coding agent skills — sync, install, and organize skills across OpenClaw, Cursor, Claude Code, and more.
* [existential-birds/beagle](https://github.com/existential-birds/beagle) - Agent Skills marketplace: framework-aware skills for code review, documentation, test-plan generation, AI-writing detection, architectural analysis, and git workflows — for Python, Go, Rust, Elixir, React, Remix, and iOS/Swift. Works with Claude Code, Codex, and any agent that supports Agent Skills.
* [TestAny-io/testany-agent-skills](https://github.com/TestAny-io/testany-agent-skills) - Testany 公司的 Agent Skills 集合，提供产品研发流程中的各类专业技能
* [Innei/SKILL](https://github.com/Innei/SKILL) - This repository stores personal AI Agent skills in a scalable directory layout.
* [KerberosClaw/kc_ai_skills](https://github.com/KerberosClaw/kc_ai_skills) - AI Skills That Actually Do Things — 中文優先的 Claude Code / Codex agent skills 合集 · Reusable bilingual skills for any LLM workflow
* [klubinskak/skilldex](https://github.com/klubinskak/skilldex) - Skilldex is a local-first desktop dashboard for developers to discover, organize, and favourite their agent skills across global, project, and repo sources
* [ogulcancelik/agent-skills](https://github.com/ogulcancelik/agent-skills) - Small, opinionated, agent-agnostic skills for coding agents
* [simota/agent-skills](https://github.com/simota/agent-skills) - 90 specialist AI agents + 3 project-local extensions for Claude Code / Codex CLI / Antigravity CLI (agy). Anthropic Agent Skills spec-aligned, hub-spoke orchestration via Nexus with 49 Recipes and 11 Skill Packs. Covers development, security, design, testing, FinOps, compliance, observability, and AI/ML.
* [brianlovin/notion-skills](https://github.com/brianlovin/notion-skills) - Use Notion as your source of truth for agent skills
* [netresearch/agent-rules-skill](https://github.com/netresearch/agent-rules-skill) - Agent Skill for generating AGENTS.md files following the agents.md convention | Claude Code compatible
* [parallel-web/parallel-agent-skills](https://github.com/parallel-web/parallel-agent-skills)
* [AsyrafHussin/agent-skills](https://github.com/AsyrafHussin/agent-skills) - Skills for AI coding agents — Laravel, PHP, React, TypeScript, testing, security, and code quality.
* [eduardo-sl/go-agent-skills](https://github.com/eduardo-sl/go-agent-skills) - Curated AI agent skills for Go projects.
* [abcnuts/manus-skills](https://github.com/abcnuts/manus-skills) - My personal Manus AI agent skills library *(archived)*
* [PaulRBerg/agent-skills](https://github.com/PaulRBerg/agent-skills) - PRB's collection of agent skills
* [richtabor/agent-skills](https://github.com/richtabor/agent-skills) - Agent skills I use every day.
* [youzaiAGI/agent-skills-hub](https://github.com/youzaiAGI/agent-skills-hub) - Management of skill packages
* [magnus919/agent-skills](https://github.com/magnus919/agent-skills) - Curated collection of AI agent skills for Hermes and other agent frameworks
* [vanillagreencom/kendex](https://github.com/vanillagreencom/kendex) - Package manager for agents, skills, hooks, and extensions. Author once, install on every harness. QOL features included.
* [bitsky-tech/AmphiLoop](https://github.com/bitsky-tech/AmphiLoop) - Public agent skills based on Bridgic
* [compnew2006/Spec-Kit-Antigravity-Skills](https://github.com/compnew2006/Spec-Kit-Antigravity-Skills) - An Agentic Skill System for Antigravity, transforming Spec-Driven Development into autonomous AI capabilities for the entire SDLC.
* [lingbol088-spec/auto-skill-installer](https://github.com/lingbol088-spec/auto-skill-installer) - AI agent skill discovery and installer / AI 智能体技能自动发现与安装器
* [LingyiChen-AI/OpenSkills](https://github.com/LingyiChen-AI/OpenSkills) - An open-source Agent Skill framework implementing progressive disclosure architecture
* [pc-style/skill-view](https://github.com/pc-style/skill-view) - Local-only web GUI for inspecting agent skills (SKILL.md) across user, project, plugin, cache, and marketplace sources
* [Autoloops/upskill](https://github.com/Autoloops/upskill) - CLI + skill for the Autoloops upskill registry. Search, inspect, report on, and publish agent skills from your shell.
* [zunalabs/skills-manager](https://github.com/zunalabs/skills-manager) - A universal desktop app for managing AI agent skills across all major coding agents.
* [contentful/skill-kit](https://github.com/contentful/skill-kit) - TypeScript SDK for building agent skills as typed state machines — define steps, validate outputs, compile to self-contained executables.
* [CymChad/book-skill-generator](https://github.com/CymChad/book-skill-generator) - 从书籍中提取核心方法论，生成可执行的 Agent Skill
* [LOGIN-TB/claude-skills](https://github.com/LOGIN-TB/claude-skills) - Agent Skills von LOGIN zur freien Nutzung - SKILL.md-Format fuer Claude Code, Claude-App und API
* [DevelopersGlobal/ai-agent-skills](https://github.com/DevelopersGlobal/ai-agent-skills) - AI agent skills for production grade applications
* [openBitFun/skill_tree](https://github.com/openBitFun/skill_tree) - 为 AI coding agent（Claude Code / Codex CLI 等）打造的 Skill 分层路由树生成器。把臃肿的单体 Skill 拆分/聚合成 ROOT → ROUTER → SKILL 的树形结构，让 agent 根据用户意图按需加载子能力，避免一次性塞满上下文。支持单 Skill 拆树、多 Skill 聚合（含歧义消解）、增量扩展三种模式，兼容 .claude/skills 与 .agent/skills 双路径约定，纯 Markdown + Bash，零依赖。
* [valenovo/ai-agent-skills](https://github.com/valenovo/ai-agent-skills) - AI Agent的Skills 合集
* [Zhang-Henry/CoEvoSkills](https://github.com/Zhang-Henry/CoEvoSkills) - CoEvoSkills: Self-Evolving Agent Skills via Co-Evolutionary Verification — COLM 2026
* [microsoft/cat-agent-skills](https://github.com/microsoft/cat-agent-skills) - Skills for modern agents in Copilot Studio
* [tmchow/agent-skills](https://github.com/tmchow/agent-skills) - Cross-platform AI agent skills (SKILL.md) installable via npx skills / gh skills
* [ComeOnOliver/skillshub](https://github.com/ComeOnOliver/skillshub) - 🧠 The right skill, one API call. AI agent skills registry with token-efficient skill resolution. 5,000+ skills from 500+ top repos.
* [mudler/skillserver](https://github.com/mudler/skillserver) - A home for your agents skills. Create, manage, share skills between agents easily.
* [zeroclaw-labs/zeroclaw-skills](https://github.com/zeroclaw-labs/zeroclaw-skills) - Official skill registry for ZeroClaw — community-contributed AI agent skills, tools, and workflows
* [matyasstoch/david-skills](https://github.com/matyasstoch/david-skills) - Public archive of David's agent skills
* [palmier-io/palmier-skills](https://github.com/palmier-io/palmier-skills) - Agent Skills for Palmier Pro
* [kanyun-inc/reskill](https://github.com/kanyun-inc/reskill) - reskill - brings the npm experience to AI agent skills.
* [yzfly/Mind-Cloning-Engineering](https://github.com/yzfly/Mind-Cloning-Engineering) - MCE: Clone Human Souls with LLM Native Agent Skills | 基于 LLM Agent Skills 的心智克隆工程 | Agent Skills | Mind Skills | Mind Clone
* [hAcKlyc/MyAgents_skills](https://github.com/hAcKlyc/MyAgents_skills) - Curated open-source skills for AI agents (Claude Code compatible)
* [BulkPublish social-media-content-skills](https://github.com/azeemkafridi/bulkpublish-api/tree/main/skills/social-media-content-skills) - Reusable social media planning, adaptation, review, scheduling, and batch publishing skills for AI agents, with [API](https://app.bulkpublish.com/docs) and [MCP](https://mcp.bulkpublish.com/mcp) integrations.

### Memory and Context

* [muratcankoylan/Agent-Skills-for-Context-Engineering](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering) - A comprehensive collection of Agent Skills for context engineering, multi-agent architectures, and production agent systems. Use when building, optimizing, or debugging agent systems that require effective context management.
* [memodb-io/Acontext](https://github.com/memodb-io/Acontext) - Agent Skills as a Memory Layer
* [Astro-Han/karpathy-llm-wiki](https://github.com/Astro-Han/karpathy-llm-wiki) - Agent Skills-compatible LLM wiki for Claude Code, Cursor, and Codex. Build a Karpathy-style knowledge base from raw sources, citations, and linting.
* [lewislulu/llm-wiki-skill](https://github.com/lewislulu/llm-wiki-skill) - Karpathy-style LLM knowledge base Agent Skill for OpenClaw/Codex. Experimental — will iterate over time.
* [scaccogatto/okf-skills](https://github.com/scaccogatto/okf-skills) - The OKF toolkit for Claude Code — author, maintain, validate & visualize Open Knowledge Format bundles. Plugin, agent skills, and a GitHub Action.
* [iBlinkQ/project-cairn](https://github.com/iBlinkQ/project-cairn) - Turn project work into reusable knowledge — an AI-agent skill for Claude Code & Codex
* [entireio/skills](https://github.com/entireio/skills) - ✨ Cross-agent skills that help coding agents use Entire context from Checkpoints, sessions, and git history to search past work, explain code, and hand off sessions.
* [tigerless-labs/design-harness](https://github.com/tigerless-labs/design-harness) - Feed your agent papers and half-formed ideas — it links them into a system design you can defend. Markdown keeps the record; a visual canvas makes it readable. An Agent Skill for Claude Code & any SKILL.md-compatible agent.
* [metaevo-ai/meta-context-engineering](https://github.com/metaevo-ai/meta-context-engineering) - [ICML 2026] Meta Context Engineering via Agentic Skill Evolution
* [oliver-zehentleitner/keep-the-why](https://github.com/oliver-zehentleitner/keep-the-why) - Keep the Why: a repo-native convention and agent skill that preserves the reasoning behind a codebase as a byproduct of working with your agent — so it stops re-suggesting rejected approaches, gives better answers, speeds up onboarding, and makes legacy projects tractable again.
* [firefly-hefeng/VESTI-SKILLS](https://github.com/firefly-hefeng/VESTI-SKILLS) - Open agent skills by VESTI: vesti-memory and vesti-handoff
* [SherwinQ/karpathy-wiki](https://github.com/SherwinQ/karpathy-wiki) - 基于 [Andrej Karpathy]提出的 [LLM Wiki 模式]构建的 Agent Skill，通过四阶段流水线将碎片化信息转化为结构化、可检索、持续增长的个人知识库。
* [gviiisen/repo-context-ledger](https://github.com/gviiisen/repo-context-ledger) - 面向 AI 上下文管理的 Agent Skill：为 Codex 上下文管理、Cursor 上下文切换和 Claude 上下文管理提供跨窗口续接，用 Git 保存可验证的功能说明与变更记录。AI coding context management and agent handoffs.
* [CarlWangChina/zhigui-openclaw-ui-second-brain-skill](https://github.com/CarlWangChina/zhigui-openclaw-ui-second-brain-skill) - An advanced, UI-powered AI second brain Agent Skill for OpenClaw, Hermes Agent, WorkBuddy, TRAE, and QClaw. ZhiGui uses long-term memory to help you make better decisions, automatically plan tomorrow, resolve conflicting notes, and deliver each day's plan through your existing agent channels.
* [Tubo2333/obsidian-knowledge-brain](https://github.com/Tubo2333/obsidian-knowledge-brain) - AI agent skill that remembers every technical decision & bug fix across sessions — and learns from them. v4.0, MIT. | 跨会话记忆的AI编程助手知识大脑
* [HKUST-KnowComp/DeepRefine-Skill](https://github.com/HKUST-KnowComp/DeepRefine-Skill) - An agent skill to evolve the quality of LLM-Wiki (Graphify) at test time.
* [uussnn/second-brain](https://github.com/uussnn/second-brain) - Autonomous AI Agent Skill for Google AI Edge Gallery - self-evolving, 100% offline
* [NatsuFox/Tapestry](https://github.com/NatsuFox/Tapestry) - Tapestry - 基于 Agent Skill Bundle 的轻量级书签知识库
* [vanillaflava/llm-wiki-skills](https://github.com/vanillaflava/llm-wiki-skills) - Turn your markdown vault into a compounding knowledge wiki (Karpathy inspired). Six agent skills - knowledge grows with every conversation. Works with Obsidian, Logseq, etc. or just folders on your local drive. Compiled memory for your LLM sessions. Crossplatform. GUI install on Claude Desktop, no terminal, no code.
* [byenzyme/enzyme-skill](https://github.com/byenzyme/enzyme-skill) - Agent Skill for exploring Obsidian vaults with Enzyme — self-contained, cross-agent compatible

### Evaluation and Benchmarks

* [alibaba/skill-up](https://github.com/alibaba/skill-up) - An evaluation and evolution tool for Agent Skills.
* [modiqo/skillspec](https://github.com/modiqo/skillspec) - SkillSpec makes agent skills followable, testable, and provable with Doctor risk reports, guided imports, structured contracts, and alignment proof.
* [darkrishabh/agent-skills-eval](https://github.com/darkrishabh/agent-skills-eval) - A test runner for agentskills.io-style AI agent skills
* [mgechev/skillgrade](https://github.com/mgechev/skillgrade) - "Unit tests" for your agent skills
* [EverMind-AI/SkillCorpus](https://github.com/EverMind-AI/SkillCorpus) - Open-source infrastructure that turns scattered SKILL.md files into curated, retrieval-ready agent-skill corpora—with retrieval and evaluation tooling included.
* [NVIDIA/SkillEvaluator](https://github.com/NVIDIA/SkillEvaluator) - Multi-tier framework for evaluating AI agent skills with quality gates, semantic overlap detection, synthetic evaluation dataset generation, and live agent evaluation that measures how skills affect agent behavior.
* [langfuse/skills](https://github.com/langfuse/skills) - Agent Skills for Langfuse, the open source LLM engineering platform for tracing, prompt management, and evaluation
* [Evol-ai/SkillCompass](https://github.com/Evol-ai/SkillCompass) - Evaluate agent skill quality. Find the weakest link. Fix it. Prove it worked.
* [Raidriar7170/hermes-skilleval](https://github.com/Raidriar7170/hermes-skilleval) - Verification-gated skill routing and self-improvement harness for Hermes-style agent skills
* [StoKou/FACET-Terminal](https://github.com/StoKou/FACET-Terminal) - FACET synthesizes coherent and verifiable terminal tasks from reusable agent skills by preserving source intent and grounding all artifacts in a shared executable state.
* [agentvitals/checkup](https://github.com/agentvitals/checkup) - AgentVitals Checkup (/checkup) — an AI agent skill that gives your agent a professional health checkup: dual-axis Stability + Welfare scoring, a personality-style title, and a public cross-platform leaderboard. One-line install for Claude Code / OpenClaw / Codex / Coze. Bilingual EN/ZH.
* [pbshgthm/arc-skill](https://github.com/pbshgthm/arc-skill) - An agent skill that plays ARC-AGI-3. One rule: say what an action will do before you spend it. Claude Code on Opus 5 finished all 25 public games at 100.00 RHAE in 7,645 actions.
* [gilbertwuu/Auto-Optimize](https://github.com/gilbertwuu/Auto-Optimize) - An Agent Skill for vibe coding and AI workflow development。Built for when you hit these walls:Vague requirements → no baseline, endless rework、Only one prompt phrasing → can't tell if the problem is you or the model、Model says "looks good" → but features are missing 、great output last time, no idea how to reproduce it.
* [cxcscmu/SkillLearnBench](https://github.com/cxcscmu/SkillLearnBench) - [COLM'26] SkillLearnBench is the first benchmark for evaluating continual learning methods that automatically generate agent skills.
* [crafter-station/skill-kit](https://github.com/crafter-station/skill-kit) - local-first analytics for AI agent skills
* [smixs/mentor](https://github.com/smixs/mentor) - mentor — a session-insights skill for AI coding agents. This skill reads your local Claude Code and OpenAI Codex history and writes an /insights-style HTML report on how you work: what you build, where you lose time, and concrete fixes. An agent skill for Claude Code, Codex, and any skills-capable agent.
* [AndrewNgGirl/SkillLens](https://github.com/AndrewNgGirl/SkillLens) - Open-source self-hosted web tool for evaluating Agent Skills with rubric scores, Deep Review, and improvement suggestions.
* [protectskills/MaliciousAgentSkillsBench](https://github.com/protectskills/MaliciousAgentSkillsBench) - A Security Benchmark for Claude Code Agent Skills
* [adewale/skill-eval-harness](https://github.com/adewale/skill-eval-harness) - Agent Skill evaluation harness for paired variants, trace artifacts, and runner adapters
* [wandb/skills](https://github.com/wandb/skills) - Official Agent Skills for Weights & Biases Models and Weave
* [callstackincubator/skillgym](https://github.com/callstackincubator/skillgym) - Prove your agent skills work before you ship them.
* [cobibean/soul-grader-skill](https://github.com/cobibean/soul-grader-skill) - Hermes Agent skill for grading SOUL.md identity files with a research-backed rubric and public-safe field guide.

## Networking and Distributed

### Cloud and Infrastructure

* [vercel-labs/agent-skills](https://github.com/vercel-labs/agent-skills) - Vercel's official collection of agent skills
* [google/skills](https://github.com/google/skills) - Agent Skills for Google products and technologies
* [itsmostafa/aws-agent-skills](https://github.com/itsmostafa/aws-agent-skills) - AWS Skills for Agents
* [BagelHole/DevOps-Security-Agent-Skills](https://github.com/BagelHole/DevOps-Security-Agent-Skills) - Agent-ready DevOps, security, infrastructure, and compliance knowledge base with 80+ skills across Kubernetes, Terraform, AWS/Azure/GCP, AI platform operations, container hardening, SOC2/ISO27001, and incident response—plus ready-to-run scripts, templates, and playbooks for SRE, platform, and security teams.
* [hashicorp/agent-skills](https://github.com/hashicorp/agent-skills) - A collection of Agent skills and Claude Code plugins for HashiCorp products.
* [MicrosoftDocs/Agent-Skills](https://github.com/MicrosoftDocs/Agent-Skills) - Curated Agent Skills for Microsoft & Azure – giving AI coding assistants structured, real-time expertise from Microsoft Learn docs.
* [firebase/agent-skills](https://github.com/firebase/agent-skills) - Agent Skills for Firebase
* [disler/agent-sandbox-skill](https://github.com/disler/agent-sandbox-skill) - An agent skill for managing isolated execution environments
* [zxkane/aws-skills](https://github.com/zxkane/aws-skills) - Claude Code plugins and agent skills for AWS development — IaC(CDK/SST), serverless, cost ops, and Bedrock AgentCore
* [railwayapp/railway-skills](https://github.com/railwayapp/railway-skills) - Agent skills for interacting with Railway
* [fluxcd/agent-skills](https://github.com/fluxcd/agent-skills) - Skills to transform AI Agents into GitOps Engineers
* [tensorlakeai/tensorlake-skills](https://github.com/tensorlakeai/tensorlake-skills) - Coding agent skill for Tensorlake. Routes Claude Code, OpenAI Codex, and other AI agents to live Tensorlake docs for sandboxes, orchestration, and SDK usage.
* [open-infra-skills/infra-skills](https://github.com/open-infra-skills/infra-skills) - Open, portable agent skills for AI infrastructure engineering.
* [harness/harness-skills](https://github.com/harness/harness-skills) - A collection of structured AI agent skills that enable Claude Code, Cursor, GitHub Copilot, and other AI coding assistants to create, operate, debug, and govern Harness CI/CD workflows through natural language.
* [labring/sealos-skills](https://github.com/labring/sealos-skills) - AI agent skills for Sealos — deploy any project, provision databases, object storage & more with one command. Works with Claude Code, Gemini CLI, Codex.
* [render-oss/skills](https://github.com/render-oss/skills) - Render Agent Skills
* [TencentCloudBase/skills](https://github.com/TencentCloudBase/skills) - Production Ready Backend Development （CloudBase）Agent Skills
* [ricmmartins/azure-sre-agent-skills](https://github.com/ricmmartins/azure-sre-agent-skills) - Custom proactive skills for Azure SRE Agent — governance, cost intelligence, architecture quality, AI workload posture
* [pulumi/agent-skills](https://github.com/pulumi/agent-skills) - Official Pulumi Agent Skills for writing, migrating, and operating infrastructure with AI coding agents
* [chaterm/terminal-skills](https://github.com/chaterm/terminal-skills) - Public Agent Skills for Terminal and Kubernetes

## User Interface

### Mobile

* [twostraws/SwiftUI-Agent-Skill](https://github.com/twostraws/SwiftUI-Agent-Skill) - SwiftUI agent skill for Claude Code, Codex, and other AI tools.
* [AvdLee/SwiftUI-Agent-Skill](https://github.com/AvdLee/SwiftUI-Agent-Skill) - Add expert SwiftUI Best Practices guidance to your AI coding tool (Agent Skills open format).
* [expo/skills](https://github.com/expo/skills) - A collection of AI agent skills for working with Expo projects and Expo Application Services
* [callstackincubator/agent-skills](https://github.com/callstackincubator/agent-skills) - A collection of agent-optimized React Native skills for AI coding assistants.
* [truongduy2611/app-store-preflight-skills](https://github.com/truongduy2611/app-store-preflight-skills) - AI agent skill to scan iOS/macOS projects for App Store rejection patterns before submission
* [dpearson2699/swift-ios-skills](https://github.com/dpearson2699/swift-ios-skills) - Agent Skills for iOS 26+, Swift 6.3, SwiftUI, and modern Apple frameworks
* [new-silvermoon/awesome-android-agent-skills](https://github.com/new-silvermoon/awesome-android-agent-skills) - A collection of standardized Agent Skills to teach GitHub Copilot, Claude, Gemini and Cursor about modern Android development (Kotlin, Jetpack Compose, etc.).
* [Appllama/appllama-skills](https://github.com/Appllama/appllama-skills) - A builder, not just a researcher. Agent skills that turn top-grossing app patterns into native-quality mobile screens.
* [aldefy/compose-skill](https://github.com/aldefy/compose-skill) - Jetpack Compose Agent Skill — AI-powered coding guidance with actual androidx/androidx source code receipts. Works with Claude Code, Codex CLI, Gemini CLI, Cursor, Copilot, Windsurf, and more.
* [skydoves/compose-performance-skills](https://github.com/skydoves/compose-performance-skills) - ⚡️ A curated library of Agent Skills focused on Jetpack Compose performance.
* [superagents-lab/xcode27-skills](https://github.com/superagents-lab/xcode27-skills) - Apple's official Agent Skills exported from Xcode 27 — SwiftUI, UIKit modernization, Swift Testing, C bounds-safety, and security hardening for AI coding agents.
* [Meet-Miyani/compose-skill](https://github.com/Meet-Miyani/compose-skill) - AI agent skill for Jetpack Compose & Compose Multiplatform (KMP/CMP). MVI architecture, Navigation 3, Koin/Hilt, Ktor, Room, DataStore, Paging 3, Coil, coroutines/Flow, animations, performance, accessibility, testing, and cross-platform patterns. Works with Codex, Cursor, Claude Code.
* [dadederk/iOS-Accessibility-Agent-Skill](https://github.com/dadederk/iOS-Accessibility-Agent-Skill) - Add expert iOS Accessibility Best Practices guidance to your AI coding tool (Agent Skills open format).
* [margelo/react-native-skills](https://github.com/margelo/react-native-skills) - The best react-native Agent Skills. Forget 10x, this is 100x.
* [axiaoge2/Apple-Hig-Designer](https://github.com/axiaoge2/Apple-Hig-Designer) - A Agent Skill for designing professional interfaces following Apple Human Interface Guidelines 一项用于设计苹果前端交互界面的代理技能
* [kevmoo/dash_skills](https://github.com/kevmoo/dash_skills) - Agent Skills for Dart and Flutter ecosytem
* [Code-with-Beto/skills](https://github.com/Code-with-Beto/skills) - Agent Skills and plugins to help mobile devs ship better apps faster with AI assistance
* [Drjacky/claude-android-ninja](https://github.com/Drjacky/claude-android-ninja) - Agent Skill for Android development with Kotlin and Jetpack Compose, covering modular architecture, Navigation3, Gradle conventions, dependency management, and testing best practices.
* [ameyalambat128/swiftui-skills](https://github.com/ameyalambat128/swiftui-skills) - Agent skills for SwiftUI, built from Apple's Xcode AI documentation.
* [Livsy90/iOS-Performance-Agent-Skills](https://github.com/Livsy90/iOS-Performance-Agent-Skills) - A collection of AI-agent skills for reviewing, diagnosing, and improving performance in iOS applications.
* [kamranbekirovyz/flutterskills.md](https://github.com/kamranbekirovyz/flutterskills.md) - 🤖 Agentic skills for building beautiful Flutter apps
* [skydashnet/material-design-3-ui-skill](https://github.com/skydashnet/material-design-3-ui-skill) - A reusable Agent Skill for designing, reviewing, and implementing UI/UX with Google Material Design 3, Material You, M3 Expressive, accessibility, adaptive layouts, and semantic design tokens.
* [MADTeacher/mad-agents-skills](https://github.com/MADTeacher/mad-agents-skills) - Collection of agent skills for AI assistants working with Dart and Flutter projects
* [anhvt52/jetpack-compose-skills](https://github.com/anhvt52/jetpack-compose-skills) - Agent skill for modern Android development with Jetpack Compose — best practices for code generation and review
* [harryworld/Xcode26-Agent-Skills](https://github.com/harryworld/Xcode26-Agent-Skills)
* [tayormi/flutter-map](https://github.com/tayormi/flutter-map) - A Flutter agent skill and toolchain that produces a visual navigation map of a Flutter app
* [PasqualeVittoriosi/swift-accessibility-skill](https://github.com/PasqualeVittoriosi/swift-accessibility-skill) - Agent Skill for accessibility across SwiftUI, UIKit, and AppKit. Covers all 9 App Store Nutrition Labels + WCAG 2.2.
* [ayush016/android-lead-agent-skills](https://github.com/ayush016/android-lead-agent-skills) - AI coding skills and prompts for Android lead engineers, works with Claude, GitHub Copilot, Gemini, and Cursor. Covers Jetpack Compose, shared element transitions, beautiful UI, architecture decisions, code reviews, and MCP integration.
* [keremerkan/asc-screenshots](https://github.com/keremerkan/asc-screenshots) - AI agent skill that generates production-ready App Store screenshots for iPhone and iPad. Exports in asc-client compatible format.
* [LeeHueeng/store-screenshots](https://github.com/LeeHueeng/store-screenshots) - 🖼️ AI agent skill for Claude Code & Codex — turns raw app screenshots into store-ready App Store & Google Play marketing images: device frames (iPhone·iPad·Galaxy·Fold·Flip), app-matched backgrounds, marketing copy, exact store sizes. 앱스토어·플레이스토어 마케팅 스크린샷 자동 생성
* [mmiani/kotlin-kmp-claude-agent-skills](https://github.com/mmiani/kotlin-kmp-claude-agent-skills) - Public AI agent skills for Kotlin Multiplatform projects, grounded in official Android, Kotlin Multiplatform, Compose, navigation, testing, and modularization guidance.
* [efremidze/swift-architecture-skill](https://github.com/efremidze/swift-architecture-skill) - Agent Skill for Swift architecture design and implementation patterns.

### Applications and End User Tools

* [xingkongliang/skills-manager](https://github.com/xingkongliang/skills-manager) - A lightweight desktop app to manage, sync, and organize AI agent skills across 50+ coding tools — Claude Code, Codex, Cursor, Copilot, Gemini CLI, and more.
* [u14app/neo-chat](https://github.com/u14app/neo-chat) - A local-first AI chat workspace for models, agents, skills, plugins, search, RAG, voice, memory, and artifacts.
* [skalesapp/skales](https://github.com/skalesapp/skales) - Personal AI desktop agent for Windows, macOS, Linux, Android & iOS. Set a goal, it works on its own. Teams (pair two desktops, agents + humans), Agent2Agent, Workflows, Codework, multi-agent orgs, desktop + browser automation. 15+ AI providers, BYOK. No Docker, no terminal. Agent Skills (SKILL.md). Migration importer. Recurring autonomous tasks.
* [ai4s-research/open-science](https://github.com/ai4s-research/open-science) - Open Science Desktop — local-first, model-agnostic AI research workbench for macOS, Windows & Linux. Open-source Claude Science desktop alternative built on Tauri + MCP + agent skills.
* [qufei1993/skills-hub](https://github.com/qufei1993/skills-hub) - A cross-platform desktop app to manage Agent Skills in one place and sync them to multiple AI coding tools’ global skills directories — “Install once, sync everywhere”.
* [Shpigford/chops](https://github.com/Shpigford/chops) - Your AI agent skills, finally organized. A macOS app to browse, edit, and manage skills across Claude Code, Cursor, Codex, Windsurf, and Amp.
* [jiweiyeah/Skills-Manager](https://github.com/jiweiyeah/Skills-Manager) - Free, open-source desktop manager for AI Agent Skills. Write a skill once, sync it to 32 AI coding tools (Claude Code, Codex, Cursor, Gemini CLI, and more) via symlinks. Local-first, MIT licensed. macOS, Windows, Linux.
* [liyupi/yupi-hot-monitor](https://github.com/liyupi/yupi-hot-monitor) - 2026 年编程导航 AI 编程实战新项目，基于 Node.js + Express + React + OpenRouter 的 AI 热点监控工具，支持多信息源聚合抓取（Twitter / Bing / HackerNews / B 站等 7+ 平台）、AI 查询扩展、AI 真假识别与相关性分析、WebSocket 实时推送、邮件通知、多维度筛选排序，并将热点监控能力封装为 Agent Skills 技能包。覆盖 Prisma + SQLite 数据库、Socket.io 实时通信、Axios + Cheerio 网页爬虫、OpenRouter 大模型接入、Aceternity UI 炫酷前端、node-cron 定时任务、VSCode Copilot Vibe Coding + MCP
* [alfredxw/denova](https://github.com/alfredxw/denova) - An AI creative platform for novel writing and AI generated RPG, with built-in support for AI agents, Skills, subagent workflows, automations, image generation, and version control. 一个面向小说创作与 AI 角色扮演游戏的 AI 创作平台，内置支持 AI Agents、Skills、Subagent Workflows、Automations、图像自动生成与项目版本管理等核心能力
* [skillhub-club/skillhub-desktop](https://github.com/skillhub-club/skillhub-desktop) - One desktop to manage your agent skills
* [crossoverJie/SkillDeck](https://github.com/crossoverJie/SkillDeck) - Native macOS SwiftUI app for managing multiple AI code agent skills
* [Castor6/tactus](https://github.com/Castor6/tactus) - The first browser AI Agent extension to support Agent Skills, enabling AI to perform complex tasks through an expandable skill system. 🌟 Star if you like it! | 首个支持 Agent Skills 的浏览器 AI Agent 扩展，让 AI 通过可扩展技能系统执行复杂任务 🌟 如果喜欢请点个 Star！
* [DavidBB-L/cinema-manager](https://github.com/DavidBB-L/cinema-manager) - Hermes Agent skill - Movie/TV resource search + Quark cloud drive auto-save
* [XimilalaXiang/DeLive](https://github.com/XimilalaXiang/DeLive) - System audio capture + multi-provider ASR + local-first AI review workspace. Floating live captions, 12 ASR backends, 60+ languages, AI summary/chat/mindmap, Open API, MCP server, and Agent Skill.
* [kunchenguid/whathappened](https://github.com/kunchenguid/whathappened) - Agent skill: adaptive X-only briefing of what happened + public opinion + debates
* [mingchen666/Reviva](https://github.com/mingchen666/Reviva) - Local-first AI learning workspace — ask, note, review and create around your own materials. Wiki KB, Agents, Skills, creation tools.AI 学习工作台，围绕你的资料完成问答、笔记、复习和创作输出。本地优先，多模型，Wiki 知识库，AI Agent，创作工具。
* [hiyeshu/trip-map-builder](https://github.com/hiyeshu/trip-map-builder) - 旅行行程规划技能：规划 → 小红书调研 → 交互式地图页面 | Agent Skill for trip planning with 小红书 research and interactive map generation
* [SerhiiKorniienko/bullshit-detector](https://github.com/SerhiiKorniienko/bullshit-detector) - Agent skills that fact-check the internet: claim-by-claim verification with sources and a 0-10 BS score for any YouTube video, article, tweet, or PDF
* [CWS6206/EasyLastSkill](https://github.com/CWS6206/EasyLastSkill) - EasyLastSkill ist eine deutschsprachige Codex-/Agent-Skill fuer schnelle Recherchen zu den letzten Tagen eines Themas. Standardmaessig betrachtet sie die letzten 30 Tage und erstellt einen kompakten Bericht mit Quellen, Relevanzscore und Unsicherheiten.
* [Ciao1019/Petrichor](https://github.com/Ciao1019/Petrichor) - A self-hosted knowledge platform for humans and AI agents — publish wikis, blogs, and portable Agent Skills.
* [NimaChu/my-wiki](https://github.com/NimaChu/my-wiki) - Local-first AI knowledge app and Agent Skill with evidence-backed Wiki, an interactive knowledge universe, Viki Q&A, and shareable knowledge galaxies.
* [manhai934/novel-harness](https://github.com/manhai934/novel-harness) - 一个旨在用 AI 辅助引导老书虫落地网文/小说故事，自带小说管理网页Dashboard，使用了 Harness 架构思想，多个专项 Agent + Skills，同时维护了小说知识包市场
* [Sarai-Chinwag/wp-openclaw](https://github.com/Sarai-Chinwag/wp-openclaw) - AI-managed WordPress, out of the box. OpenClaw + WordPress + Data Machine + Agent Skills.
* [iamzhihuix/skills-manage](https://github.com/iamzhihuix/skills-manage) - Desktop app to manage AI coding agent skills across Claude Code, Cursor, Gemini CLI, Codex, and 20+ platforms from one place.

## Graphics and Media

### Graphics and Rendering

* [tt-a1i/archify](https://github.com/tt-a1i/archify) - Agent skill for beautiful, verifiable architecture, workflow, sequence, data-flow, and lifecycle diagrams—self-contained HTML with motion and crisp export.
* [imxv/Pretty-mermaid-skills](https://github.com/imxv/Pretty-mermaid-skills) - AI Agent Skill to generate and render beautiful Mermaid diagrams as SVG or terminal ASCII — 15 themes, 6 diagram types, batch CLI, no browser.
* [adithya-s-k/manim_skill](https://github.com/adithya-s-k/manim_skill) - Agent skills for Manim to create 3Blue1Brown style animations.
* [scottstts/Threejs-Awesome-Graphics-Agent-Skills](https://github.com/scottstts/Threejs-Awesome-Graphics-Agent-Skills) - A three.js agent skills for producing awesome graphics for scenes and games
* [meodai/skill.color-expert](https://github.com/meodai/skill.color-expert) - Agent skill for color science expertise. Many references covering color spaces, accessibility (APCA, WCAG), palette generation, pigment mixing, and historical color theory. Works with Claude Code, Codex, Cursor, Copilot & others.
* [bentossell/visualise](https://github.com/bentossell/visualise) - Agent skill for rendering inline interactive visuals — SVG diagrams, HTML widgets, charts, and explainers — in agent conversations.
* [inkboard/system-atlas](https://github.com/inkboard/system-atlas) - An agent skill that turns an architecture discussion into an explorable isometric atlas: one data file, an interactive map and a generated SYSTEM.md
* [Will-hxw/drawio-diagram-builder](https://github.com/Will-hxw/drawio-diagram-builder) - Portable agent skill for research-style editable draw.io diagrams and screenshot-driven refinement
* [CesiumGS/cesiumjs-skills](https://github.com/CesiumGS/cesiumjs-skills) - Curated agent skills for CesiumJS development.
* [jaccen/Awesome-Gaussian-Skills](https://github.com/jaccen/Awesome-Gaussian-Skills) - 图形学与3DGS、空间智能持续更新论文；AI Agent Skills for 3D Gaussian Splatting, NeRF & Computer Graphics Research. 700+ methods, 25categories, 12skills. OpenClaw / Claude Code compatible.
* [v2space-labs/shader-for-interfaces](https://github.com/v2space-labs/shader-for-interfaces) - Agent Skill for designing, building, debugging, and validating focused GPU effects in product interfaces.
* [meshy-dev/meshy-3d-agent](https://github.com/meshy-dev/meshy-3d-agent) - AI agent skills for Meshy AI 3D generation platform
* [CesiumGS/cesium-ai-integrations](https://github.com/CesiumGS/cesium-ai-integrations) - Cesium AI Integrations is a collection of reference integrations and experiments connecting the Cesium ecosystem with AI systems including Model Context Protocol (MCP) tools, retrieval pipelines, and agent skills.
* [mapbox/mapbox-agent-skills](https://github.com/mapbox/mapbox-agent-skills)
* [cloudy-liu/cloudy-tech-diagrams-skill](https://github.com/cloudy-liu/cloudy-tech-diagrams-skill) - AI agent skill for warm HTML and SVG technical diagrams
* [Agents365-ai/mermaid-skill](https://github.com/Agents365-ai/mermaid-skill) - Agent skill: generate Mermaid diagrams (.mmd), validate via Kroki-first loop, export PNG/SVG/PDF via mmdc or Kroki. Mermaid.live handoff, repo-survey batch mode, vision self-check, 17+ diagram types.

### Game Development

* [majidmanzarpour/threejs-game-skills](https://github.com/majidmanzarpour/threejs-game-skills) - Agent skills for building playable, polished Three.js browser games with gameplay, AAA-style graphics, UI, QA, and optional AI-generated 3D, image, and audio assets.
* [FlameskyDexive/Legends-Of-Heroes](https://github.com/FlameskyDexive/Legends-Of-Heroes) - A battle of balls game, lol style, AI Agents base, support agent skills & unityMCP. 基于ET 10的双端C#游戏框架(.net10 + Unity2022.3.62, EUI+Luban+YooAsset)，包含战斗系统（技能/buff/行为树），内置LOL风格球球大战demo
* [gamedev-skills/awesome-gamedev-agent-skills](https://github.com/gamedev-skills/awesome-gamedev-agent-skills) - 67 game-dev skills for AI coding agents — Godot, Unity, Unreal, Phaser, PixiJS, three.js, Bevy, pygame, LÖVE, Roblox. Portable SKILL.md Agent Skills (the format Anthropic launched as Claude Skills), with a router that loads the right skill for your engine and task. Runs in Claude Code, Cursor, Kiro, Codex, Copilot, Gemini CLI and more.
* [zenstory-ai/novel-to-game](https://github.com/zenstory-ai/novel-to-game) - Agent Skills that turn novels into source-grounded, fully playable games for Claude Code, Codex, and Kimi Code(K3).
* [jame581/GodotPrompter](https://github.com/jame581/GodotPrompter) - Agentic skills framework for Godot 4.x. Domain-specific skills for AI coding agents (Claude Code, Copilot, Antigravity, Cursor)
* [thedivergentai/GD-Agentic-Skills](https://github.com/thedivergentai/GD-Agentic-Skills) - The official "Long-Term Memory" for Godot 4.7+ AI Agents. A high-density library of 99 expert skills and 27 genre blueprints, providing audited, strictly typed GDScript patterns, automated persona orchestration (Analyst, Auditor, Builder), and production-grade game engineering.
* [quodsoler/unreal-engine-skills](https://github.com/quodsoler/unreal-engine-skills) - Unreal Engine C++ skills for AI coding agents. 27 skills covering gameplay, rendering, networking, animation, and more. Works with Claude Code, Cursor, Windsurf, and any agent supporting the Agent Skills spec.
* [ybuild-ai/ai-game-art-pipeline-skill](https://github.com/ybuild-ai/ai-game-art-pipeline-skill) - Agent skill from Y Build for turning AI images and videos into playable game art assets
* [niaka3dayo/agent-skills-vrc-udon](https://github.com/niaka3dayo/agent-skills-vrc-udon) - Skills, rules, and validation hooks that teach AI coding agents to generate correct UdonSharp code
* [meta-quest/agentic-tools](https://github.com/meta-quest/agentic-tools) - Agent Skills for Meta Quest/Horizon OS VR Development
* [WU-HAOTIAN34/2dimg2motion](https://github.com/WU-HAOTIAN34/2dimg2motion) - Agent skill for converting 2D character into style-consistent transparent animation sequences and spritesheets for game engines | 用于将静态 2D 角色/物体图片，通过 agent 转化为一致的透明背景游戏动画序列帧。
* [guiguiyan930-source/game-ui-design-workflow](https://github.com/guiguiyan930-source/game-ui-design-workflow) - 一套面向游戏 UI 设计的 Cursor Agent Skills 工作流，覆盖原型视觉生成、风格切换、页面延展与组件拆解，并通过 Spec-Kit 文档、视觉契约和资源清单保证多页面一致性与可交付性。
* [chongdashu/vibejam-starter-pack](https://github.com/chongdashu/vibejam-starter-pack) - Free Vibe Jam starter pack — battle-tested ThreeJS and Phaser agent skills, starter projects, and prompts.
* [godot-fun/godot-agent](https://github.com/godot-fun/godot-agent) - A lightweight Godot framework + agent skills for building and shipping games
* [Jahrome907/minecraft-agent-skills](https://github.com/Jahrome907/minecraft-agent-skills) - Minecraft AI agent skills and dual-target plugin bundle for Codex and Claude Code.
* [gary149/h3-game-sprites](https://github.com/gary149/h3-game-sprites) - Agent Skill: turn AI-generated video into 2D game sprite sheets (the Mortal Kombat method, with MiniMax H3 as the actor)
* [chongdashu/threejs-toonshooter](https://github.com/chongdashu/threejs-toonshooter) - A vibe coded threejs shooter arena using threejs agent skills
* [mcpads/create-retro-game-kr-patch](https://github.com/mcpads/create-retro-game-kr-patch) - 레트로 게임 한글 패치 제작 전 파이프라인 에이전트 스킬 · Agent skill for end-to-end Korean (Hangul) fan-translation patches for retro games
* [Yuki001/game-dev-skills](https://github.com/Yuki001/game-dev-skills) - My personal agent skill repository, primarily focused on game development.

### Image and Video

* [calesthio/OpenMontage](https://github.com/calesthio/OpenMontage) - World's first open-source, agentic video production system. 12 production pipelines, 100+ tools, 700+ agent skill and production-knowledge files. Turn your AI coding assistant into a full video production studio.
* [wuyoscar/GPT-Image2-Skill](https://github.com/wuyoscar/GPT-Image2-Skill) - GPT Image 2 prompt gallery, image prompt library, agentic skill, and CLI for OpenAI image generation/editing
* [s1dashu/ip-as-logo-skill](https://github.com/s1dashu/ip-as-logo-skill) - A compact Agent Skill for highly simplified, rounded, subtly neo-skeuomorphic IP mascot logos.
* [remotion-dev/skills](https://github.com/remotion-dev/skills) - Agent Skills
* [0x0funky/agent-sprite-forge](https://github.com/0x0funky/agent-sprite-forge) - Agent Skill for generating 2D sprite sheets and map, transparent PNG frames, and animated GIFs from prompts.
* [eternityspring/shuohao-skills](https://github.com/eternityspring/shuohao-skills) - AI 短剧制作的 skill 集合：拆角色、排大纲、出场景与道具设定、写剧本、切分镜 | Agent skills for AI short-drama production — character bibles, adaptation outlines, art bibles, screenplays, storyboards. Runs in Claude Code & codex.
* [NarratorAI-Studio/narrator-ai-cli-skill](https://github.com/NarratorAI-Studio/narrator-ai-cli-skill) - AI 解说大师 — Agent skill；封装 narrator-ai-cli 供 Claude/Codex 等工具调用
* [gnipbao/story-to-handdrawn-video](https://github.com/gnipbao/story-to-handdrawn-video) - Agent skill: convert Chinese story copy or ordered images into a hand-drawn diary-comic animation (silent MP4 picture track).
* [Alisa0808/vox-director](https://github.com/Alisa0808/vox-director) - Turn one topic into a finished Vox-style paper-collage explainer/ad video — automated end to end on Atlas Cloud + ffmpeg. An agent skill.
* [0xsline/OpenChatCut](https://github.com/0xsline/OpenChatCut) - Open-source, local-first conversational AI video editor with a professional multi-track timeline, Agent Skills, MCP integration, and Remotion rendering.
* [pyang5166/gbro-collage-broll](https://github.com/pyang5166/gbro-collage-broll) - 半调纸拼贴 B-roll 生成 skill：三闸门审批，Gemini Omni Flash 首尾帧组装动画 | Editorial halftone paper-collage B-roll agent skill
* [vibe-motion/skills](https://github.com/vibe-motion/skills) - agent skills for vibe motion
* [pexoai/pexo-skills](https://github.com/pexoai/pexo-skills) - A collection of open-source Agent Skills for content creation — images, audio, and video.
* [Vincentwei1021/video-talkcraft](https://github.com/Vincentwei1021/video-talkcraft) - Agent skill that turns Claude Code / Codex into a motion-design studio for voiceover-driven explainer videos — word-level voiceover sync, 78 motion recipe cards, an anti-slideshow camera system, Remotion rendering.
* [nuyoah-ai-works/nuyoah-xiezhen-prompt](https://github.com/nuyoah-ai-works/nuyoah-xiezhen-prompt) - 南鸢写真提示词 Agent Skill
* [JimLiu/baocut](https://github.com/JimLiu/baocut) - Open-source Agent Skill that drives the BaoCut macOS app CLI (transcribe · subtitle · translate · cut) from Claude Code, Codex, and other agents
* [geekjourneyx/hyperframes-motion-director](https://github.com/geekjourneyx/hyperframes-motion-director) - Agent Skill for Chinese-first HyperFrames motion-video production from articles, products, websites, and README files.
* [heygen-com/skills](https://github.com/heygen-com/skills) - HeyGen AI agent skills — avatar creation and video production via the v3 Video Agent pipeline
* [Yacey/agnes-ai-generation-skill](https://github.com/Yacey/agnes-ai-generation-skill) - Agent Skill for Agnes AI text, image, and video generation APIs.
* [GongLingRui/screen-creative-skills](https://github.com/GongLingRui/screen-creative-skills) - Skills for Film and Television Creation Agents|31 个影视创作评估策划Agent Skills｜AI影视自动化工作流｜竖屏短剧长剧IP改编
* [tmchow/illo-skill](https://github.com/tmchow/illo-skill) - illo skill — an AI agent skill that turns ideas and articles into original print-style editorial illustrations, starring a recurring mascot. 30+ characters packs, with ability to create your own.
* [mediastormDev/dream-to-video-skill](https://github.com/mediastormDev/dream-to-video-skill) - AI agent skill that transforms dream descriptions into cinematic videos — auto-generates prompts, submits to Jimeng via browser automation, and downloads finished videos with post-processing effects.
* [leeguooooo/chatgpt-imagegen](https://github.com/leeguooooo/chatgpt-imagegen) - Use your ChatGPT subscription to generate images from the command line — no OPENAI_API_KEY, no gateway, no daemon. Zero-dep Python CLI + AI-agent skill.
* [Mr-funny/hbg-classical-poem-silk-video](https://github.com/Mr-funny/hbg-classical-poem-silk-video) - Agent Skill for turning Chinese classical poems into vertical Chinese-art videos with ImageGen stills, Docker I2V, calligraphy captions, retained ambience, BGM and final MP4 QA.
* [2998980-hue/surreal-pop-collage](https://github.com/2998980-hue/surreal-pop-collage) - 把照片变成超现实波普拼贴的 AI agent skill：黑白现实锚点 + 平涂色形 + 全图只有一个不可能的巨物。An agent skill that turns photos into surreal pop collages.
* [NanmiCoder/open-image-prompts](https://github.com/NanmiCoder/open-image-prompts) - Open, local-first visual prompt archive with traceable prompt-image references and installable Agent Skills.
* [hypersocialinc/shots](https://github.com/hypersocialinc/shots) - Claude Code/Agent Skill for making App Store screenshots with GPT Image 2 that you can upload. Give it your App Store link & screenshots of your app and it will produce beautiful app store screenshots ready to upload to Apple (or Google)
* [dean9703111/ai-agent-skill-for-video-workflow](https://github.com/dean9703111/ai-agent-skill-for-video-workflow) - 這是一個專為影片字幕處理設計的 AI Agent Skills 集合，提供從音訊轉字幕、優化字幕、設計字卡到生成社群媒體摘要的完整工作流程。
* [MapleShaw/yt-dlp-downloader-skill](https://github.com/MapleShaw/yt-dlp-downloader-skill) - Cursor Agent Skill for downloading videos using yt-dlp
* [Kianzzz/book-sales-video](https://github.com/Kianzzz/book-sales-video) - 中文图书带货视频 Agent Skill：飞书取稿、书籍核验、配音、配图、双语字幕与 OpenChatCut 自动剪辑
* [chengyi-ai/native-subtitle-quote-image](https://github.com/chengyi-ai/native-subtitle-quote-image) - 保留视频内嵌字幕，精确取帧并生成 3:4 社交长图的 Agent Skill
* [Anil-matcha/vox-ai-motion-graphics-generator](https://github.com/Anil-matcha/vox-ai-motion-graphics-generator) - 🎬 Turn any topic into a finished Vox-style paper-collage explainer / motion graphics video — script, collage keyframes, animation, voice-over, music & captions, all automated. An agent skill for Claude Code, Codex & other coding agents.
* [AtlasCloudAI/awesome-seedance-2.5-prompts-skills](https://github.com/AtlasCloudAI/awesome-seedance-2.5-prompts-skills) - 100+ curated Seedance 2.5 prompts with real video previews, plus an installable Agent Skill that optimizes prompts, creates storyboards, and generates videos via Seedance models.
* [adrianpunk/punk-ip-illustrations](https://github.com/adrianpunk/punk-ip-illustrations) - Punk personal IP article illustration Agent Skill
* [erduo1998-cell/erduo-broll-loop-engineering](https://github.com/erduo1998-cell/erduo-broll-loop-engineering) - SRT 驱动的双后端 B-roll Agent Skill：自动路由 HyperFrames / Remotion，集成 152 张 Shotcraft 镜头卡
* [Square-Zero-Labs/video-prompting-skill](https://github.com/Square-Zero-Labs/video-prompting-skill) - AI Agent Skill for Prompting Video Models
* [SpaceZephyr/design-buddy](https://github.com/SpaceZephyr/design-buddy) - Design Buddy: visual production Agent Skills for brand design systems, GPT-image-2 images, diagrams, infographics, logos, slide decks, WeChat layouts and social images
* [xianxie6/stamp-edge-skill](https://github.com/xianxie6/stamp-edge-skill) - Agent skill: turn any image into a postage-stamp style card with perforated edges and true transparent background
* [calesthio/generative-media-skills](https://github.com/calesthio/generative-media-skills) - Research-backed agent skills and tools for premium image, video, audio, voice, and generative media production across AI coding assistants.
* [CattleZ/dance-video-to-prompt](https://github.com/CattleZ/dance-video-to-prompt) - 本地短视频反推 AI 视频生成提示词：抽帧、清晰度、节奏卡点、Agent Skill
* [Alisa0808/vibe-creating-skill](https://github.com/Alisa0808/vibe-creating-skill) - Open-source, bilingual AI video-prompt skill — rewrite ideas into model-ready text-to-video prompts. A portable Agent Skill (Claude Code, Codex, OpenClaw, Hermes); generate via Atlas Cloud — Seedance 2.0, Kling, Veo, Hailuo, Wan, Vidu, Gemini Omni, Grok Imagine.
* [Mr-funny/hbg-life-simulation](https://github.com/Mr-funny/hbg-life-simulation) - HBG Agent Skill for Chinese life-simulation narrative videos with consistent comic IP, rapid multi-life openings, Edge TTS, synchronized captions, zoom/pan motion and final MP4 QA.
* [BAIKEMARK/happy-figure-skill](https://github.com/BAIKEMARK/happy-figure-skill) - Happy Figure Agent Skill for generating structured scientific figure prompts from research content.
* [zhanghaonan777/Seedance2-skill](https://github.com/zhanghaonan777/Seedance2-skill) - Seedance2 视频创意技能包：100+ 镜头词库、Seedance 2.0 全模态 API CLI，兼容 OpenClaw / Cursor / 任意 Agent 平台。AI Agent skill for ByteDance Seedance video generation. Creativity gate (memorability / surprise / emotion / narrative), zero-copy ideation from images, 100+ cinematography terms, Seedance 2.0 multimodal API CLI. Works with OpenClaw, or any agent platform.
* [haidrrrry/claude-remotion-skill](https://github.com/haidrrrry/claude-remotion-skill) - Open-source Claude agent skill that teaches Claude Code, Claude Desktop & Claude AI to create and edit professional motion graphics videos with Remotion. AI video editing, B-roll, captions, sound design — from one prompt.
* [runesleo/claude-video-kit](https://github.com/runesleo/claude-video-kit) - Agent Skill + Remotion pipeline: brief/script → review receipt → narrated 9:16 explainer. RC: video-explainer skill.
* [znyupup/ai-video-editing-skill](https://github.com/znyupup/ai-video-editing-skill) - AI Agent Skill for automated vlog editing. Feed raw footage, get a finished video. Powered by ffmpeg + Whisper + Vision API.
* [black-forest-labs/skills](https://github.com/black-forest-labs/skills) - Official agent skills from Black Forest Labs for FLUX image and video generation — prompting guides and API integration patterns for Claude Code, Codex, and any agentskills.io-compatible agent.
* [jiahuiqu17/paper-signal](https://github.com/jiahuiqu17/paper-signal) - Subject-aware minimal-zine image production for Agent Skills: art direction, generation, series, evidence, and real-bitmap QA.
* [machina-exm/film-studio-skills](https://github.com/machina-exm/film-studio-skills) - 7 installable agent skills that run the pipeline behind $2M AI video productions — script to locked, generation-ready shot prompts. Claude Code · Codex · Hermes · OpenCode
* [aedev-tools/adobe-agent-skills](https://github.com/aedev-tools/adobe-agent-skills) - AI agent skills for Adobe After Effects automation — describe what you want, and we'll generate and execute the code.
* [kwhi6693-web/photo-abstract-editorial](https://github.com/kwhi6693-web/photo-abstract-editorial) - Turn photos into source-faithful editorial artworks with an Agent Skill — adaptive layouts, controlled abstraction, and a Strict Fidelity composition path.
* [heloraai/Seedance2.0-Prompt-Optimizer-skill](https://github.com/heloraai/Seedance2.0-Prompt-Optimizer-skill) - Agent skill for generating cinematic, compliant video prompts for Jimeng Seedance 2.0 | 即梦Seedance 2.0 视频提示词生成 Skill
* [pascalorg/skills](https://github.com/pascalorg/skills) - Agent skill to extract color palettes from images — screenshots, Figma exports, design mockups. Installable via npx skills add pascalorg/image-analysis
* [BIAsia/voxel-icon](https://github.com/BIAsia/voxel-icon) - Voxel Icon — free 3D voxel icon pack plus an agent skill that generates matching icons with GPT Image 2
* [hassancs91/claude-image-generation](https://github.com/hassancs91/claude-image-generation) - Connect Claude to image generation with Agent Skills. Three levels: a zero-cost code-based design engine, a Three.js 3D renderer, and a real diffusion model on Cloudflare. Plus an AI Storybook pipeline that turns a plain-English story into an illustrated, narrated HTML book.
* [wzj177/shop-tryon-skill](https://github.com/wzj177/shop-tryon-skill) - 一个用于 AI 虚拟试衣的 Agent Skill。用户可以通过“上传服装图/模特图”或“文字描述”快速生成试穿效果图，并可继续生成多角度素材和展示视频。
* [sugarforever/boring-video-studio](https://github.com/sugarforever/boring-video-studio) - 小木头的个人视频流水线 Agent Skill - VerySmallWoods Video
* [moonlin1213/muted-zine-poster-v01](https://github.com/moonlin1213/muted-zine-poster-v01) - A muted, poetic paper-poster Agent Skill for low-saturation zine-style image generation.
* [nuyoah-ai-works/nuyoah-image-reverse-prompt](https://github.com/nuyoah-ai-works/nuyoah-image-reverse-prompt) - 南鸢图片反推 Agent Skill：把参考图拆解为结构字段、参考色卡和可直接生成的中文提示词。
* [Wan-Video/Wan-skills](https://github.com/Wan-Video/Wan-skills) - AI Agent Skills for Wan — Enable your AI Agent to easily leverage Wan's AIGC capabilities.
* [keepongo/video-summarizer](https://github.com/keepongo/video-summarizer) - An AI agent skill that extracts subtitles/transcripts from video platforms and generates structured summary notes with keyframe screenshots. Works with **Cursor** and **Claude Code**.
* [runwayml/skills](https://github.com/runwayml/skills) - for Runway coding agent skills
* [kangarooking/director-skills](https://github.com/kangarooking/director-skills) - 导演Skill：面向 AI 视频创作的开源 Agent Skills | Director Skills: Open-source Agent Skills for AI video creation.
* [PixVerseAI/skills](https://github.com/PixVerseAI/skills) - Agent skill library for PixVerse CLI — helps AI agents (Claude Code, Cursor, Codex, etc.) generate videos and images through structured, composable workflows.

## Security

### Security Tools

* [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) - Security scanner for AI agent skills. Detect vulnerabilities, malicious patterns, security risks, prompt injection, data exfiltration, and supply-chain risks in Claude Code, Codex, and MCP skills before you install them.
* [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill) - A coding-agent skill for multi-phase security audits with independently verified, machine-readable findings
* [ljagiello/ctf-skills](https://github.com/ljagiello/ctf-skills) - Agent skills for solving CTF challenges - web exploitation, binary pwn, crypto, reverse engineering, forensics, OSINT, and more
* [snyk/agent-scan](https://github.com/snyk/agent-scan) - Security scanner for AI agents, MCP servers and agent skills.
* [cisco-ai-defense/skill-scanner](https://github.com/cisco-ai-defense/skill-scanner) - Security Scanner for Agent Skills
* [akto-api-security/akto](https://github.com/akto-api-security/akto) - Akto is the fastest growing AI Security platform for your teams to secure AI agents, MCPs, LLMs, Agent skills, Gen AI apps in your organization.
* [utkusen/sast-skills](https://github.com/utkusen/sast-skills) - Collection of agent skills to find vulnerabilities inside your web/mobile apps.
* [raroque/vibe-security-skill](https://github.com/raroque/vibe-security-skill) - Agent skill that audits vibe-coded apps for common security vulnerabilities introduced by AI coding assistants
* [berabuddies/Semia](https://github.com/berabuddies/Semia) - Semia, security audit for AI agent skills.
* [bruc3van/agent-skills-guard](https://github.com/bruc3van/agent-skills-guard) - 一款提供Agent Skills安全扫描和可视化管理的桌面应用 | A desktop application that provides security scanning and visual management for Agent Skills.
* [Batman0506/openclaw-sec-skills](https://github.com/Batman0506/openclaw-sec-skills) - 🛡️ 网络安全/AI Agent Skills 集合 | Cybersecurity Security Skills Collection
* [Nova-Hunting/nova-proximity](https://github.com/Nova-Hunting/nova-proximity) - Nova-Proximity is a MCP and Agent Skills security scanner powered with NOVA
* [OWASP/www-project-agentic-skills-top-10](https://github.com/OWASP/www-project-agentic-skills-top-10) - OWASP Foundation web repository
* [forefy/.context](https://github.com/forefy/.context) - AI Agent Skills, Goals and Dynamic Workflows for Security Auditing, Pentesting and Research
* [Fangcun-AI/SkillWard](https://github.com/Fangcun-AI/SkillWard) - Security scanner for Agent Skills — uncover hidden threats before deployment.
* [pillar-labs/sail-skill](https://github.com/pillar-labs/sail-skill) - SAIL V2 (Secure AI Lifecycle) as an agent skill — the full 91-risk catalog for AI/agent gap assessments, security roadmaps, and compliance checklists. Installs on Claude Code, Codex, ChatGPT, Antigravity, and any SKILL.md-compatible agent.
* [resemble-ai/detect-skill](https://github.com/resemble-ai/detect-skill) - Agent skill for deepfake detection & media safety — detect AI-generated audio, images, and video with Resemble AI
* [shaniidev/bug-reaper](https://github.com/shaniidev/bug-reaper) - Web2 bug bounty Agent Skill — evidence-based, no AI slop. Covers 18 vulnerability classes across HackerOne, Bugcrowd, Intigriti, and YesWeHack.
* [yoanbernabeu/supabase-pentest-skills](https://github.com/yoanbernabeu/supabase-pentest-skills) - 24 AI Agent Skills for professional security auditing of Supabase applications. Detection, key extraction, RLS testing, storage audit, IDOR detection, and comprehensive reporting. Works with Claude Code, Cursor, Windsurf, and 30+ AI agents.
* [alice-dot-io/caterpillar](https://github.com/alice-dot-io/caterpillar) - Caterpillar is a security scanning library for AI agent skill files (e.g., Claude Code skills) for dangerous or malicious behavior
* [ax128/AegisGate](https://github.com/ax128/AegisGate) - Open-source security gateway for LLM APIs — prompt injection detection, PII redaction, dangerous response sanitization, and audit logging. OpenAI/Claude compatible, MCP & Agent SKILL support. Drop-in proxy for AI coding agents (Cursor, Claude Code, Codex).
* [pors/skill-audit](https://github.com/pors/skill-audit) - Security auditing CLI for AI agent skills - detects prompt injection, secrets, and dangerous code patterns.
* [YARAHQ/yara-rule-skill](https://github.com/YARAHQ/yara-rule-skill) - LLM Agent Skill for YARA rule authoring and review

## Testing and Quality

### Testing

* [AvdLee/Swift-Testing-Agent-Skill](https://github.com/AvdLee/Swift-Testing-Agent-Skill) - An agent skill focused entirely on Swift Testing, helping you write better tests, migrate from XCTest, improve test architecture, and adopt modern Swift testing patterns with confidence.
* [twostraws/Swift-Testing-Agent-Skill](https://github.com/twostraws/Swift-Testing-Agent-Skill) - Swift Testing agent skill for Claude Code, Codex, and other AI tools.
* [LambdaTest/agent-skills](https://github.com/LambdaTest/agent-skills) - AI agent skills for TestMu AI (Formerly LambdaTest).
* [shenli/distributed-system-testing](https://github.com/shenli/distributed-system-testing) - AI-agent skills for distributed-systems testing
* [naodeng/awesome-qa-skills](https://github.com/naodeng/awesome-qa-skills) - Awesome QA Skills — a bilingual (zh/en) AI testing Agent Skills library for Codex, Cursor, Claude Code, Kiro, OpenCode, and Trae. Ships 4 testing workflows and 25 testing-type skills (58 skill folders with language parity): independently installable, composable, and eval-ready with skill-up. Covers requirements, strategy, cases, API/performance/sec
* [workersio/skills](https://github.com/workersio/skills) - Agent skills to find and fix software bugs
* [petrkindlmann/qa-skills](https://github.com/petrkindlmann/qa-skills) - 50 QA and test-automation skills for Claude Code, Codex, Cursor, and any Agent Skills Standard runtime.
* [bocato/swift-testing-agent-skill](https://github.com/bocato/swift-testing-agent-skill) - Agent Skill providing expert Swift Testing guidance for AI coding tools: covering test doubles, fixtures, async patterns, XCTest migration, and testing best practices.
* [hegeldev/hegel-skill](https://github.com/hegeldev/hegel-skill) - An agent skill for writing Hegel tests

## Utilities

### Command Line Tools

* [googleworkspace/cli](https://github.com/googleworkspace/cli) - Google Workspace CLI — one command-line tool for Drive, Gmail, Calendar, Sheets, Docs, Chat, Admin, and more. Dynamically built from Google Discovery Service. Includes AI agent skills.
* [larksuite/cli](https://github.com/larksuite/cli) - The official Lark/飞书 CLI tool, maintained by the larksuite team — built for humans and AI Agents. Covers core business domains including Messenger, Docs, Base, Sheets, Calendar, Mail, Tasks, Meetings, and more, with 200+ commands and 20+ AI Agent Skills.
* [jacob-bd/gemini-notebook-mcp-cli](https://github.com/jacob-bd/gemini-notebook-mcp-cli) - Programmatic access to Gemini Notebook - via command-line interface (CLI), Model Context Protocol (MCP) server, and AI agent skills.
* [chenxin-yan/crust](https://github.com/chenxin-yan/crust) - A TypeScript CLI framework that ships your commands as a CLI, agent skills, and MCP.
* [basecamp/hey-cli](https://github.com/basecamp/hey-cli) - HEY CLI and Agent Skills
* [basecamp/fizzy-cli](https://github.com/basecamp/fizzy-cli) - Fizzy CLI and Agent Skills
* [officecli/officecli](https://github.com/officecli/officecli) - OfficeCLI is AI document generation CLI for PPTX, DOCX, XLSX, Reports, and Images. Generate editable Office files from prompts with npm install, hosted trial, and optional agent skills.
* [gmickel/sheets-cli](https://github.com/gmickel/sheets-cli) - Composable Google Sheets CLI for humans and agents. Read, write, update cells by key—with Agent Skills for Claude Code and OpenAI Codex.
* [leeguooooo/wechat-use](https://github.com/leeguooooo/wechat-use) - macOS pure-background WeChat send CLI — no UI flash. Agent skill via npx skills.

### Text Processing

* [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills) - Agent skills for Obsidian. Teach your agent to use Obsidian CLI and open formats including Markdown, Bases, JSON Canvas.
* [blader/humanizer](https://github.com/blader/humanizer) - Agent skill that removes signs of AI-generated writing from text
* [isjiamu/gzh-design-skill](https://github.com/isjiamu/gzh-design-skill) - 把 Markdown 一键排成可直接粘进公众号编辑器的精致 HTML —— 6 套精选主题 + 主题生成器 + 双关卡校验。An AI-agent skill that turns Markdown into paste-ready WeChat article HTML.
* [AminBlg/SimpleEnglish](https://github.com/AminBlg/SimpleEnglish) - Agent skill: make LLMs write docs in ASD-STE100 Simplified Technical
* [Nanako0129/sepia](https://github.com/Nanako0129/sepia) - De-AI writing skill for any Agent Skills-compatible agent (77+ via the Skills CLI), with native plugins for Claude Code, Codex, Grok Build, and Antigravity. Narrative-architecture repair for fiction, venue-matched rules for professional prose. Based on StoryScope (arXiv:2604.03136).
* [larashero3-dotcom/writing-dna-skill](https://github.com/larashero3-dotcom/writing-dna-skill) - 写作蒸馏器.skill｜蒸馏复刻任意写作风格的 agent skill | Writing DNA Distiller - distill and recreate any writing style as an agent skill
* [orange2ai/renwei-writing](https://github.com/orange2ai/renwei-writing) - 人味儿写作 · An AI agent skill: edit people's words without erasing the person behind them
* [coji/natural-japanese](https://github.com/coji/natural-japanese) - 仕事の日本語を、読みやすくわかりやすく書く・直すための Agent Skill です。
* [QuZhan51496/paper2anything](https://github.com/QuZhan51496/paper2anything) - An agent skills pack that turns an academic paper PDF into slides, a poster, a webpage, a Xiaohongshu post, or a WeChat article (paper2slides/poster/html/xhs/wechat)
* [Chenruishuo/posterly](https://github.com/Chenruishuo/posterly) - Build academic conference posters as a single HTML/CSS file, rendered to print-ready PDF via headless Chromium. A coding-agent skill.
* [tizzy916/humanities-writing-companion](https://github.com/tizzy916/humanities-writing-companion) - End-to-end humanities writing assistant — an Agent Skill (open SKILL.md format). 11 modes from Socratic research-question sharpening through AI-use disclosure. Bilingual (EN/中文), discipline-aware (literature/history/philosophy/art/religion/linguistics + cross-disciplinary). Four-layer critique, calibratable devils advocate, voice preservation.
* [theclaymethod/unslop](https://github.com/theclaymethod/unslop) - An agent skill to de-AI your writing
* [bowenliang123/markdown-exporter](https://github.com/bowenliang123/markdown-exporter) - An Agent Skill and Dify plugin to transform Markdown to files of DOCX, PPTX, XLSX, PNG, PDF, HTML, MD, CSV, JSON, XML.
* [ferdinandobons/brand-docs](https://github.com/ferdinandobons/brand-docs) - BrandDocs is a set of agent skills that learn your existing Word, PowerPoint and Excel templates and generate new on-brand documents from them. Unlike generic AI document generators, it preserves brand, structure, styles and formulas by construction. Built for Claude Code, Codex and compatible AI agents.
* [thvroyal/kimi-skills](https://github.com/thvroyal/kimi-skills) - AI agent skills for professional document generation (DOCX, PDF, XLSX) extracted from Kimi. Designer-quality outputs with native charts, validation pipelines, and full OpenXML control
* [luoling8192/technical-writing](https://github.com/luoling8192/technical-writing) - 中文内部技术写作的 agent skill，约束设计文档 / 评审稿 / postmortem / 分享稿场景的语气、句法、结构
* [EveryInc/hands-on-deck](https://github.com/EveryInc/hands-on-deck) - Agent-native PowerPoint manipulation — one CLI lets AI agents inspect, edit, create, and verify .pptx files through atomic JSON patches. Packaged as an Agent Skill.
* [apcamargo/typst-skills](https://github.com/apcamargo/typst-skills) - Agent skills that guide AI agents to write Typst code
* [lovstudio/any2pdf](https://github.com/lovstudio/any2pdf) - Markdown to professionally typeset PDF — an agent skill for AI coding assistants
* [danjdewhurst/story-skills](https://github.com/danjdewhurst/story-skills) - Agent Skills for end-to-end story writing in markdown, packaged as Codex and Claude Code plugins.
* [gapmiss/obsidian-plugin-skill](https://github.com/gapmiss/obsidian-plugin-skill) - Agent SKILL for Obsidian.md plugin development
* [addyosmani/clarity](https://github.com/addyosmani/clarity) - Clarity - an Agent skill for clearer writing
* [content-designer/ux-writing-skill](https://github.com/content-designer/ux-writing-skill) - Agent Skill for systematic UX writing — scale content quality through AI-powered design system enforcement. Works with Claude and Codex.
* [STRYXTN/awesome-ai-research-writing](https://github.com/STRYXTN/awesome-ai-research-writing) - 来自顶尖研究机构的 AI 论文写作 Prompt 模板库与 Agent Skills 集合 ✨
* [heptameta/heptabase-cli-skills](https://github.com/heptameta/heptabase-cli-skills) - Agent skills for Heptabase CLI.
* [helpfeel/cosense-cli](https://github.com/helpfeel/cosense-cli) - Cosenseのページを読み・調べ・編集する為のAgent Skillとそのハーネス
* [hajimi-kun/latex-to-word-workflow](https://github.com/hajimi-kun/latex-to-word-workflow) - Agent Skill for polished LaTeX-to-Word conversion with live Zotero citations
* [libnyx/LT2MD](https://github.com/libnyx/LT2MD) - AI-agent skill producing reusable Markdown from PDFs. It turns flowcharts, diagrams, and charts into text beside each caption instead of empty links. It checks an earlier conversion against the PDF and fixes misread or missing parts. Long PDFs run in small saved batches with an independent review pass, each paragraph tagged with its page.
* [Hyacehila/humanizer-zh-next](https://github.com/Hyacehila/humanizer-zh-next) - 去除中文文本中 AI 写作痕迹的 Agent Skill（基于 blader/humanizer 与 op7418/humanizer-zh）
* [zxyasfas/paper_format_agent](https://github.com/zxyasfas/paper_format_agent) - DOCX formatter for academic papers with a content-fingerprint guard: proves your text is never altered, only the formatting. Also installable as an agent skill. 毕业论文、学位论文的 Word 自动排版：按格式要求改字体字号、行距、缩进、标题和题注；指纹校验保证只改格式、不动正文，也可做格式检查评分。
* [run-llama/llamaparse-agent-skills](https://github.com/run-llama/llamaparse-agent-skills) - LlamaParse Agent Skills
* [trussary/vietnamese-language-skill](https://github.com/trussary/vietnamese-language-skill) - Agent Skills that make Claude write Vietnamese a Vietnamese professional would actually ship.
* [anshaneja5/markscrub](https://github.com/anshaneja5/markscrub) - CLI + agent skill to scrub AI provenance marks from text and files
* [pickle-an/md-to-docx-skill](https://github.com/pickle-an/md-to-docx-skill) - Markdown 自动转正式 Word格式的Agent Skill
* [Hasasasa/html-to-editable-pptx](https://github.com/Hasasasa/html-to-editable-pptx) - Convert HTML slide decks to truly editable PPT / .pptx - text stays native PowerPoint textboxes, not screenshots. Agent Skill (Claude Code / Cursor / Codex / opencode) + plain Python CLI.

### Automation and Scripting

* [jarrodwatts/claude-code-config](https://github.com/jarrodwatts/claude-code-config) - My personal Claude Code configuration - rules, hooks, agents, skills, and commands
* [LAVARONG/wechat-automation-api](https://github.com/LAVARONG/wechat-automation-api) - 微信 Windows 版自动化发送服务（支持 4.0+ 版本） 基于 Flask + uiautomation 的 HTTP API 服务，通过 UI 自动化控制微信客户端发送消息。 支持文本、图片、批量发送和队列管理。非 HOOK、非协议，安全可靠。已支持Agent Skill，可让openclaw安装。
* [gokapso/agent-skills](https://github.com/gokapso/agent-skills) - Kapso agent skills for WhatsApp.
* [genggng/hermes-arxiv-agent](https://github.com/genggng/hermes-arxiv-agent) - 一个基于 Hermes 的 agent skill：每天自动从 arXiv 抓取论文，用 AI 生成中文摘要和作者单位，推送到飞书，并提供本地静态阅读网站。
* [raja-patnaik/obsidian-agent](https://github.com/raja-patnaik/obsidian-agent) - A complete system for managing Obsidian vaults with Claude Code and Cowork. Designed for two vaults (work and personal) with consistent structure, frontmatter schemas, agent skills, automation hooks, and migration tooling.
* [Zsun79/ConferenceWatch](https://github.com/Zsun79/ConferenceWatch) - An Agent Skill to watch the deadlines of latest AI conference.
* [liangdabiao/lark-workflow-feishu-cli](https://github.com/liangdabiao/lark-workflow-feishu-cli) - # 飞书 AI 效率系统 — 20 大工作流 Skill > 基于 Claude Agent/OpenClaw Skill + 飞书 CLI (lark-cli) 构建的个人 AI 效率基础设施。 > 将 Claude Agent/OpenClaw 10 大实战用例完整迁移到飞书生态，适合 Claude Agent Skill 和 OpenClaw，用飞书各模块实现所有工作流功能。
* [tomascortereal/claude-code-setup](https://github.com/tomascortereal/claude-code-setup) - My full Claude Code configuration — agents, skills, hooks, plugins, and global instructions
* [michalzubkowicz/nixos-management-skill](https://github.com/michalzubkowicz/nixos-management-skill) - AI Agent Skills for NixOS generated from docs and websites with best practices

## Systems and Hardware

### Embedded and Firmware

* [aklofas/kicad-happy](https://github.com/aklofas/kicad-happy) - AI coding agent skills for KiCad electronics design. Works with Claude Code and OpenAI Codex. Analyze schematics, review PCB layouts, EMC pre-compliance, SPICE simulation, download datasheets, source components, and prep boards for fabrication.
* [mc3545dada/mspm0-skill](https://github.com/mc3545dada/mspm0-skill) - 面向电赛的 MSPM0 + SysConfig Agent Skill
* [zhoushoujianwork/easyeda-agent](https://github.com/zhoushoujianwork/easyeda-agent) - 嘉立创EDA专业版(EasyEDA Pro)自动化：给 AI harness 装上画板的「手」—— 一套 typed 原理图/PCB 动作，CLI / Agent Skill / stdio MCP 三形态融合接入。承接嘉立创「不以卖板赚钱，以培养中国工程师为己任」 | EasyEDA Pro automation: the hands of your AI harness — typed schematic/PCB actions via CLI, Agent Skill and stdio MCP.
* [Eriemon/verilog-generator](https://github.com/Eriemon/verilog-generator) - Agent skill for Verilog-2001 RTL generation and FPGA design workflows.
* [NVIDIA-AI-IOT/jetson-device-skills](https://github.com/NVIDIA-AI-IOT/jetson-device-skills) - Foundational Agent Skills for NVIDIA Jetson Device
* [Adancurusul/serial-mcp-server](https://github.com/Adancurusul/serial-mcp-server) - Rust MCP server and CLI for serial/UART devices, with JSON macro automation and agent skills for repeatable timed workflows.
* [allocnode/oh-my-sage](https://github.com/allocnode/oh-my-sage) - 🛠️ 米家自动化极客版 AI Agent (SKILL & MCP)- 用自然语言创建复杂自动化规则
* [Arcadia-1/analog-agents](https://github.com/Arcadia-1/analog-agents) - 12 agentic skills for analog IC design — architecture, sizing, verification, cross-model review, knowledge graph, and self-evolution. Works with or without EDA.
* [beriberikix/zephyr-agent-skills](https://github.com/beriberikix/zephyr-agent-skills) - A complete catalog of Agent Skills (agentskills.io) for Zephyr RTOS development.

## Business and Domain

### Finance and Trading

* [internet-court/internet-court-skill](https://github.com/internet-court/internet-court-skill) - The trust layer for agent-to-agent commerce — natural-language mandates, ERC-7710 delegated permissions, x402 payments, escrow, and dispute resolution as one open, catch-all Agent Skill / Claude Code plugin.
* [muxuuu/serenity-skill](https://github.com/muxuuu/serenity-skill) - Serenity-inspired Agent Skill for supply-chain bottleneck stock research
* [RKiding/Awesome-finance-skills](https://github.com/RKiding/Awesome-finance-skills) - A collection of Awesome Finance Agent Skills for free and easy to start | 一系列开源免费的金融分析Agent Skills
* [lyra81604/zhengxi-views](https://github.com/lyra81604/zhengxi-views) - 可溯源的郑希(易方达基金经理)投研 Agent Skill——基于他全部公开观点原文 + 有原话佐证的投资方法 + 全市场基金真实数据，能溯源问答、按他框架给基金打分，绝不杜撰。⚠️仅研究学习辅助，不构成投资建议‼️website是郑希主页！
* [liangdabiao/amazon-sorftime-research-MCP-skill](https://github.com/liangdabiao/amazon-sorftime-research-MCP-skill) - 亚马逊选品 之 Listing全维度穿透分析报告 加上 全品类分析 ，关键词分析，差评分析 ，市场调研 等等。codex/claude code agent skill, amazon sorftime MCP/西柚mcp/sif mcp/卖家精灵sellersprite 智能体skill. 亚马逊跨境电商skill工具集。
* [komako-workshop/digital-oracle](https://github.com/komako-workshop/digital-oracle) - AI agent skill that answers macro questions — housing, gold, BTC, geopolitics — with probability estimates mined from 13 financial data sources (Polymarket, Kalshi, CFTC, SEC & more). For Claude Code / Cursor / Codex / OpenClaw. | 让 AI Agent 从金融数据中挖掘宏观趋势的数字先知
* [gadicc/yahoo-finance2](https://github.com/gadicc/yahoo-finance2) - Unofficial API for Yahoo Finance with CLI, MCP and Agent Skill
* [tourmind-com/Tourmind-Booking-Skills](https://github.com/tourmind-com/Tourmind-Booking-Skills) - AI agent skill for end-to-end hotel search and booking—compare live rates across leading OTAs and hotel suppliers, verify availability, book stays, and manage reservations, cancellations, and payments via the TourMind API.
* [nexscope-ai/Amazon-Skills](https://github.com/nexscope-ai/Amazon-Skills) - Free AI agent skills for Amazon sellers— keyword research, competitor analysis, listing audit & more. Works with OpenClaw, Claude Code, Cursor, Windsurf, Codex and any agent that supports the Skills format.
* [agiprolabs/claude-trading-skills](https://github.com/agiprolabs/claude-trading-skills) - 68 trading, DeFi, and quantitative finance Agent Skills. Works with Claude Code, Cursor, Codex, Gemini CLI, and 30+ other tools.
* [lzwme/finance-quant-skills](https://github.com/lzwme/finance-quant-skills) - 一个面向金融量化交易领域的 Agent Skills 技能维护仓库，主要聚焦A股量化交易。
* [coolqoo/1click-ecom-detailpage](https://github.com/coolqoo/1click-ecom-detailpage) - 一键生成高转化跨境电商主图与商品详情页的 AI Agent Skill
* [ALAGENT-HKU/x2strategy](https://github.com/ALAGENT-HKU/x2strategy) - Extract structured strategy specifications from quantitative finance research papers — Agent Skill for GitHub Copilot & Claude Code
* [bitget-wallet-ai-lab/bitget-wallet-skill](https://github.com/bitget-wallet-ai-lab/bitget-wallet-skill) - AI agent skill for Bitget Wallet — token swap, cross-chain bridge, and gasless transactions via Order Mode API. Supports 7 EVM chains + Solana.
* [second-state/payment-skill](https://github.com/second-state/payment-skill) - Agentic skill for requesting and accepting payments from / to humans and agents
* [medusajs/medusa-agent-skills](https://github.com/medusajs/medusa-agent-skills) - Agent skills and commands for Medusa best practices and conventions.
* [machina-sports/sports-skills](https://github.com/machina-sports/sports-skills) - Open-source agent skills for live sports data and prediction markets. Football, F1, Kalshi, Polymarket. Zero API keys. SKILL.md format.
* [Superior-Trade/superior-skills](https://github.com/Superior-Trade/superior-skills) - Open agent skills and tool schemas for Superior Trade — build, backtest, and deploy trading strategies on Hyperliquid
* [agentii-ai/agentii-investment-intelligence](https://github.com/agentii-ai/agentii-investment-intelligence) - Claude-type skills for institutional equity research — 25 AI agent skills with SEC filings, XBRL financials, earnings calendars, DCF/comps/LBO models, and PPT generation. Powered by agentii.ai data plane. Works with Claude Code, OpenCode, Codex, OpenClaw, Goose.
* [joutaojian/arkvol-skill](https://github.com/joutaojian/arkvol-skill) - Arkvol Skill 将 arkvol.com 的数据查询与解读能力接入兼容 Agent Skills 的 AI Agent。安装后，可以直接用自然语言查询 A 股与科技板块、港股、基金与 ETF、美股中期趋势及七巨头轮动等数据，并获得包含数据日期、关键指标和风险边界的分析结果。
* [Polymarket/agent-skills](https://github.com/Polymarket/agent-skills) - Public repository for Polymarket Agent Skills
* [40RTY-ai/shopify-admin-skills](https://github.com/40RTY-ai/shopify-admin-skills) - Community-maintained AI agent skills for operating Shopify stores — workflows, optimization, reports and more
* [zach22-1999/amazon-skills](https://github.com/zach22-1999/amazon-skills) - Open-source Agent Skills for Amazon sellers: product research, feature validation, listing audits, ads search-term analysis, and CVR diagnostics. 亚马逊跨境电商 Skills。
* [okx/agent-skills](https://github.com/okx/agent-skills) - Plug-and-play AI agent skills for OKX — letting any LLM agent trade, manage portfolios, query live market data, and run grid/DCA bots through a single okx CLI, no API wiring required.
* [cloudQuant/backtrader](https://github.com/cloudQuant/backtrader) - High-performance Python backtesting & live-trading framework: 45%+ faster than upstream, 50+ indicators, tick-to-daily strategies, plus an AI-native workflow (MCP server, agent skills, web platform).
* [dfkai/xtquantai](https://github.com/dfkai/xtquantai) - 迅投 QMT 量化 AI 技能集（Agent Skills）：研报因子回测脚本生成等，适用于 Claude Code / Cursor / Codex / Kimi 等 70+ AI 编程工具
* [hikari0511/awesome-amazon-ec-skills](https://github.com/hikari0511/awesome-amazon-ec-skills) - 亚马逊跨境电商场景下的 Claude / AI Agent Skills 合集（中文优先，聚焦 Amazon 出海 + 1688 供货上游）
* [aronhy/tiktok-agent-skills](https://github.com/aronhy/tiktok-agent-skills) - 搭配 KSS MCP 使用的 TikTok Shop 运营 Skill，支持商品选品、店铺分析、爆款视频发现、达人匹配、字幕提取和行动方案生成。
* [alpacahq/alpaca-skills](https://github.com/alpacahq/alpaca-skills) - Agent skills for Alpaca's Trading API and Broker API: drop-in SKILL.md files for AI coding assistants
* [Senpi-ai/senpi-skills](https://github.com/Senpi-ai/senpi-skills) - Open-source AI agent skills + 80+ strategy templates for autonomous trading on Hyperliquid — build, deploy, and protect strategies across crypto, equities, commodities & indices, with two-phase trailing-stop (DSL) exits.
* [trading212-labs/agent-skills](https://github.com/trading212-labs/agent-skills) - ✨ Supercharge your AI agent with the power of the Trading 212 API
* [pseudo-longinus/quant-buddy-skills](https://github.com/pseudo-longinus/quant-buddy-skills) - A股·港股·美股量化分析 Agent Skill。支持行情、估值、财务查询、选股筛选、因子计算、策略回测。Quant agent skill for A-share, HK & US stocks — market data, fundamentals, screening, factor & backtest.
* [Qiushen-first/cn-investment-banking-skills](https://github.com/Qiushen-first/cn-investment-banking-skills) - Agent Skills for Chinese IPO sponsor execution: diligence, filing production, pre-submission QC, regulatory inquiries, and filing refresh.
* [lanfuli/aleabito-serenity-skills](https://github.com/lanfuli/aleabito-serenity-skills) - Claude/Codex agent skills distilled from @aleabitoreddit (Serenity)'s full public archive — track her, analyze like her, anticipate her next focus. Bilingual 中文/English.
* [mjunaidca/polymarket-skills](https://github.com/mjunaidca/polymarket-skills) - Composable Agent Skills for Polymarket prediction market trading. Paper-trading-first, security-audited. Works with Claude Code, OpenClaw, NanoClaw, Codex, Cursor.
* [leionion/ClawForge](https://github.com/leionion/ClawForge) - OpenClaw AI trading agents - Skill Forge, Chat, BankrBot, Polyclaw, Alpaca, Kalshi, Whale TrackingOpenClaw AI trading agents OpenClaw AI trading agents
* [jup-ag/agent-skills](https://github.com/jup-ag/agent-skills) - Skills for AI coding agents to integrate with the Jupiter ecosystem.
* [gaaiyun/joinquant-skill](https://github.com/gaaiyun/joinquant-skill) - AI agent skill for generating quantitative strategy code on JoinQuant platform - Cursor / Claude Code compatible
* [Shopify/agent-skills](https://github.com/Shopify/agent-skills) - Shopify skills for agent collaboration
* [afu-it/malaysia-payment-gateway](https://github.com/afu-it/malaysia-payment-gateway) - Agent skills for implementing Malaysia payment gateway integrations.
* [SerendipityOneInc/ZooData-Skills](https://github.com/SerendipityOneInc/ZooData-Skills) - ZooData Skills - AI Agent skills for e-commerce data intelligence across Amazon, TikTok & beyond, plus open-web extraction
* [asterdex/aster-skills-hub](https://github.com/asterdex/aster-skills-hub) - A set of Agent skills for the Aster Futures API: depositing funds from a wallet, and for both v1 (HMAC) and v3 (EIP-712) — auth, public market data, account/balance/positions, order placement and management, WebSocket streams, and error/rate-limit handling.
* [kangise/ecommerce-ai-skills](https://github.com/kangise/ecommerce-ai-skills) - Cross-border e-commerce AI knowledge base, designed to be read by people and installed by agents. 69 trilingual guides, 878 structured prompts, a 94-entity / 318-constraint domain ontology, and 9 agent skills served over MCP. Factual claims are dated and CI-verified; prompts declare their data requirements and failure boundaries. CC0.
* [elliottech/lighter-agent-kit](https://github.com/elliottech/lighter-agent-kit) - Agent Skill to let AI Agents trade on Lighter
* [algoderiv/agent-skills](https://github.com/algoderiv/agent-skills) - Claude Code skills for China quant trading

### Business and Productivity

* [phuryn/pm-skills](https://github.com/phuryn/pm-skills) - PM Skills Marketplace: 100+ agentic skills, commands, and plugins — from discovery to strategy, execution, launch, and growth.
* [jangviktor-web/nihaixia](https://github.com/jangviktor-web/nihaixia) - 倪海厦视角的中医Agent Skill，基于倪海厦教学资料开发，蒸馏倪师伤寒论、金匮要略、黄帝内经、神农本草经、针灸篇等，人纪/医案/经方思维，六经辨证，八纲辨证，天机道，天纪，紫微斗数，易经，阴阳，八卦，五行，风水，地纪等，总结8个诊断公式+快速诊断流程图+脉舌速查+七步走思维模式，蒸馏129条伤寒论 · 23篇金匮 · 72篇黄帝内经 · 神农本草经374种本草（上137/中110/下127） · 1257 例结构化案例 + 243 例叙事医案 · 2,452页讲义。
* [Paramchoudhary/ResumeSkills](https://github.com/Paramchoudhary/ResumeSkills) - A collection of AI agent skills focused on resume optimization, job applications, and career development. Built for job seekers, career changers, and professionals who want Claude Code to help with resume writing, ATS optimization, interview prep, and strategic job search.
* [wondelai/skills](https://github.com/wondelai/skills) - Wondel.ai Agent Skills — Business, Marketing, UX & Coding Frameworks from Bestselling Books. 50 skills + 12 guided journeys for Claude Code, Codex, Cursor & other agentskills.io agents.
* [ScrapeCreators/social-media-research-skills](https://github.com/ScrapeCreators/social-media-research-skills) - AI agent skills for social media research. Outlier posts, comment mining, competitor teardowns, ad libraries & trends across TikTok, Instagram, YouTube, Reddit, X, LinkedIn & more. Powered by ScrapeCreators. Works with Claude Code, Cursor, Codex, Gemini CLI.
* [JuneYaooo/nihaisha-nishi-tcm](https://github.com/JuneYaooo/nihaisha-nishi-tcm) - 倪海厦中医课程资料的 Agent Skill：支持课程检索、方证穴位辨析、学习笔记整理与板书截图证据索引。 | An Agent Skill for Ni Haisha TCM course study, formula-pattern lookup, acupoint reference, and screenshot evidence indexing.
* [Eronred/aso-skills](https://github.com/Eronred/aso-skills) - AI agent skills for App Store Optimization (ASO) and app marketing. Built for indie developers, app marketers, and growth teams who want Cursor, Claude Code, or any Agent Skills-compatible AI assistant to help with keyword research, metadata optimization, competitor analysis, and app growth.
* [ReScienceLab/opc-skills](https://github.com/ReScienceLab/opc-skills) - Agent Skills for Solopreneurs
* [krusemediallc/arcads-claude-code](https://github.com/krusemediallc/arcads-claude-code) - Arcads external API: agent skills, prompting library, and Cursor/Claude workspace
* [mohitagw15856/pm-claude-skills](https://github.com/mohitagw15856/pm-claude-skills) - 1098 professional Agent Skills for Claude, ChatGPT, Gemini, Cursor & Codex — from PRDs and postmortems to appealing a disability benefit, building a go-bag, and settling into a new country. Plain-markdown, MIT, in Anthropic's official plugin directory. Free in-browser or 'npx pm-claude-skills add'.
* [ziguishian/xhs-visual-director-skill](https://github.com/ziguishian/xhs-visual-director-skill) - 这是一个用于规划小红书图文的 Agent Skill。它不是普通文案助手，而是一个“视觉导演”：先判断内容任务，再选择适合的视觉风格，最后输出完整图文结构、逐页视觉方案、图像生成提示词、发布文案和自检清单。
* [SpaceZephyr/creator-buddy](https://github.com/SpaceZephyr/creator-buddy) - Creator Buddy: orchestrated Agent Skills for cross-platform content search, creator analysis, and viral trend research
* [SeanJ1ang/design-judge-skills](https://github.com/SeanJ1ang/design-judge-skills) - Evidence-driven Agent Skills for design award research, evaluation, award matching, entry writing, and submission readiness.
* [forcedotcom/sf-skills](https://github.com/forcedotcom/sf-skills) - Salesforce's curated collection of agent skills for building applications. Optimized for Agentforce Vibes, compatible with all AI tools.
* [kostja94/marketing-skills](https://github.com/kostja94/marketing-skills) - Agent Skills for Marketing — SEO, Social, Influencer & More. 160+ open-source skills for SEO, content, 40+ page types, paid ads, channels, and strategies. Add project context; get tailored, production-ready output. Cursor, Claude Code, OpenClaw — no lock-in.
* [ferdinandobons/startup-skill](https://github.com/ferdinandobons/startup-skill) - AI agent skills for startup validation, competitive intelligence, and planning
* [coreyhaines31/makerskills](https://github.com/coreyhaines31/makerskills) - AI agent skills for the personal operator's craft — decisions, research, second-brain, content rotation, scenario modeling, and meta-skills to author more. Works with Claude Code, Codex, Cursor.
* [JeffLi1993/seo-audit-skill](https://github.com/JeffLi1993/seo-audit-skill) - SEO agent skill for OpenClaw,Claude Code, and AI agents. Generate beginner SEO audits and advanced technical SEO reports for any page.
* [GarethManning/education-agent-skills](https://github.com/GarethManning/education-agent-skills) - 165 evidence-grounded AI skills for teachers, school leaders and EdTech builders—pedagogy, learning science, curriculum, assessment and regeneration. Claude, Codex and Hermes.
* [zarazhangrui/beautiful-feishu-whiteboard](https://github.com/zarazhangrui/beautiful-feishu-whiteboard) - 35 curated colour palette styles for building beautiful, editable Feishu / Lark (飞书) whiteboards. An agent skill.
* [lawve-ai/awesome-legal-skills](https://github.com/lawve-ai/awesome-legal-skills) - A curated list of awesome Agent Skills for automating legal work
* [Affitor/affiliate-skills](https://github.com/Affitor/affiliate-skills) - 50 AI agent skills for affiliate marketing. Research trending content, write data-backed posts, generate infographics, build landing pages, deploy — full flywheel with social intelligence. Works with Claude Code, Pi, ChatGPT, Gemini, Cursor, Windsurf, any AI.
* [Varnan-Tech/opendirectory](https://github.com/Varnan-Tech/opendirectory) - AI Agent Skills built for Founders who hate Marketing
* [MetaInFLow/Enterprise-ai-scenario-map-skill](https://github.com/MetaInFLow/Enterprise-ai-scenario-map-skill) - 咨询AI Agent Skill - 为任何企业自动生成 AI 应用场景地图报告 | Auto-generate AI scenario map reports for any enterprise
* [aitytech/agentkits-marketing](https://github.com/aitytech/agentkits-marketing) - Enterprise-grade AI marketing automation for Claude Code, Cursor, GitHub Copilot, and any AI assistant supporting agents & skills
* [7toCR/paper2patent](https://github.com/7toCR/paper2patent) - 📄→💡 Paper2Patent：面向科研成果转化的论文转专利智能模板库，提供 Flash/Pro Prompt、专利附图生成与 Agent Skills，辅助规范生成中国发明专利申请文本。
* [ayi-ai/nie-grassroots-logic](https://github.com/ayi-ai/nie-grassroots-logic) - 聂·基层运行逻辑 · Agent Skill：基于聂辉华《基层中国的运行逻辑》的方法论工具箱（不含原书全文）
* [tryproduck/produck-skills](https://github.com/tryproduck/produck-skills) - Agent skills to help you build products your users love.
* [blacktwist/social-media-skills](https://github.com/blacktwist/social-media-skills) - AI agent skills for social media content strategy, creation, and analysis across text-first platforms
* [GresonKwan/JobOK](https://github.com/GresonKwan/JobOK) - Job OK: 面向中文求职者的证据驱动求职 Agent Skill，支持优势挖掘、岗位匹配、简历优化、面试训练和投递跟踪。
* [shuyicc/MathLens](https://github.com/shuyicc/MathLens) - MathLens 是一个专注于数学题目视频讲解的 Agent Skill。你只需粘贴一道数学题（图片或文字），它就能自动完成从题目分析、可视化讲解、配音脚本到 Manim 动画视频的全流程制作。单条视频1-10 分钟，成本 0.2-1 元以内。
* [mysticaltech/marketingskills](https://github.com/mysticaltech/marketingskills) - Marketing skills for AI agents (Agent Skills spec). Fork of coreyhaines31/marketingskills with pre-built .skill files for easy installation.
* [shawnpang/startup-founder-skills](https://github.com/shawnpang/startup-founder-skills) - AI agent skills for tech startup founders — fundraising, sales, product, recruiting, engineering, legal, ops, and growth. Works with Claude Code, Cursor, Codex, and any Agent Skills-compatible tool.
* [kunchenguid/vision](https://github.com/kunchenguid/vision) - Agent skill that mines your repo's history to draft a VISION.md, stress-tests it with hard hypotheticals, and iterates with you on an interactive review board.
* [readwiseio/readwise-skills](https://github.com/readwiseio/readwise-skills) - Agent skills for your Readwise and Reader data, powered by the Readwise MCP server/CLI. Triage your inbox, quiz yourself on what you've read, build a personalized now-reading page, and more.
* [AaravKashyap12/advise-project-approach](https://github.com/AaravKashyap12/advise-project-approach) - A portable project-planning skill for Codex, Claude Code, pi, Hermes, and Agent Skills-compatible harnesses. Evidence before build advice.
* [Aperivue/medsci-skills](https://github.com/Aperivue/medsci-skills) - Agent Skills for medical research — literature search, reporting-guideline & citation checks, statistics, publication figures, submission. Works with Claude Code, Codex, Cursor & GitHub Copilot. Built by a physician-researcher, tested on real publications. MIT.
* [ZeKaiNie/universal-examprep-skill](https://github.com/ZeKaiNie/universal-examprep-skill) - Last-night exam-cram coach as a Claude Agent Skill: turns your slides, notes and past papers into a chaptered knowledge base + quiz bank, teaches only what's in your materials, and never fabricates (measured 100% out-of-scope abstention). Bilingual EN/中文 — the 期末极速备考 skill.
* [basecamp/basecamp-cli](https://github.com/basecamp/basecamp-cli) - Basecamp CLI and Agent Skills
* [AIDevGTM/gtm-cofounder](https://github.com/AIDevGTM/gtm-cofounder) - #1 Product of The Day @ Product Hunt. The GTM co-founder you don't have. Open-source GTM Agent Skills for developer tools and AI products, for founders, GTM hires, and founding AEs: positioning, first users, launch, pricing. Sharpened by Frankl & Czakon. MIT.
* [twhsi/skills](https://github.com/twhsi/skills) - AI Agent Skills for Chinese Knowledge Workers: iMandalArt, FIRE, planning, and publishing workflows for Claude Code, Codex, and LLM agents.
* [ersinkoc/project-architect](https://github.com/ersinkoc/project-architect) - Documentation-first project planning agent skill. Generates specs, implementation plans, tasks, and single-shot prompts for coding agents. Compatible with Claude Code, Cursor, Codex, and 40+ agents via agentskills.io.
* [Google-Health-API/google-health-cli](https://github.com/Google-Health-API/google-health-cli) - Google Health CLI — one command-line tool for the Google Health API. Includes AI agent skills.
* [vishalsachdev/canvas-mcp](https://github.com/vishalsachdev/canvas-mcp) - Canvas LMS MCP server — 80+ tools and 5 agent skills for students & educators. Works with Claude, Cursor, Codex, and 40+ agents.
* [nicobailon/grill-for-unknowns](https://github.com/nicobailon/grill-for-unknowns) - Agent skill for finding unknowns, grilling plans, and reaching shared understanding before implementation
* [ttfake92-lab/skills](https://github.com/ttfake92-lab/skills) - AI Agent Skills for content creators — install via npx skills add
* [aaron-he-zhu/seo-geo-claude-skills](https://github.com/aaron-he-zhu/seo-geo-claude-skills) - Signpost → the 16 SEO/GEO agent skills live in aaron-marketing-skills; this repo's standalone 20-skill line is preserved at tag v9.9.12. Install: npx skills add aaron-he-zhu/aaron-marketing-skills
* [flamingoTOM/Auto-CV](https://github.com/flamingoTOM/Auto-CV) - 一个基于 LaTeX 的中文简历模板，配合 Claude Code 的 /Auto-CV Agent Skill，支持导入简历，自动提取内容并转换和交互式自然语言描述制作简历两个功能
* [yan-labs/yan-skills](https://github.com/yan-labs/yan-skills) - Yan's agent skills collection — Google Trends SEO workflows, AI news, autopilot, and more. For Claude Code / Codex / Cursor.
* [sudokar/openspec-plus](https://github.com/sudokar/openspec-plus) - OpenSpec Plus — Agentic skills that enhance OpenSpec's Spec-Driven Development through better discovery, requirements, design decisions, execution planning and execution. Works with Claude Code, OpenCode, Github Copilot and any other AI coding agents
* [liangdabiao/GEO-Content-Optimizer-Skill](https://github.com/liangdabiao/GEO-Content-Optimizer-Skill) - GEO（Generative Engine Optimization）是面向 AI 搜索引擎的内容优化方法论。就像 SEO 优化 Google 排名，GEO 优化你的内容在 ChatGPT、Perplexity、Gemini、Google AI Overview 等 AI 引擎中的引用率。 本项目提供3个 Agent Skill，覆盖 GEO 全流程：
* [davidpc007/openclaw-marketing-skills](https://github.com/davidpc007/openclaw-marketing-skills) - openclaw marketing skills which ships 38 agent skills covering CRO, copywriting, SEO, paid ads, growth, and GTM
* [Arman-Kudaibergenov/1c-ai-development-kit](https://github.com/Arman-Kudaibergenov/1c-ai-development-kit) - Comprehensive AI agents, skills and rules toolkit for 1C:Enterprise development in Cursor IDE
* [yaojingang/GEOHub](https://github.com/yaojingang/GEOHub) - GEOHub: open, evidence-bounded GEO and SEO agent skills for AI Search, with research-grounded discovery, diagnosis, content, measurement, and one-line SEO planning.
* [Jichengyuuuuu/resume-builder-skill](https://github.com/Jichengyuuuuu/resume-builder-skill) - AI resume skill，适用于任何 Agent 或 LLM —— 可以基于模糊的背景信息快速生成专业中文简历（HTML + DOCX），支持 ATS 优化、岗位定制技能、高阶顾问建议，无需反复调整。AI Agent Skill | Chinese Resume Builder | 简历生成 | Resume Optimization
* [Golden2002/legal-research-skill](https://github.com/Golden2002/legal-research-skill) - 本项目提供一套专业的法律检索 Agent Skill，可用于 Cursor、Claude Code、OpenCode 等 AI 编程工具。无论是非法律专业人士需要了解法律知识，还是法律从业者进行法律检索，都能提供系统性的法律规范查找与整理服务。
* [aleksandr-alhoff/seo-landing](https://github.com/aleksandr-alhoff/seo-landing) - SEO Landing: Give your AI coding agent the capabilities of a senior Technical SEO engineer. An agent skill for building high-performance, technically optimized SEO landing pages. Turn an AI coding agent into a technical SEO specialist. Build and improve landing pages with: • 🚀 100/100 Google PageSpeed target • ⚡ Core Web Vitals optimization
* [autumnseasonism/lark-todo](https://github.com/autumnseasonism/lark-todo) - AI Agent Skill - 扫描飞书全平台待办事项，智能排序，直接处理或创建任务
* [deepakness/google-ai-search-optimization](https://github.com/deepakness/google-ai-search-optimization) - Unofficial Agent Skill based on Google Search guidance for AI Overviews, AI Mode, and SEO audits.
* [seranking/seo-skills](https://github.com/seranking/seo-skills) - Claude SEO Skills — production Claude Agent Skills for the SE Ranking MCP server. Content briefs, AI Search share of voice, audits, backlink gaps, keyword clusters, schema, sitemap, GEO, and more.
* [N1arko/redaktura-skills](https://github.com/N1arko/redaktura-skills) - Agent Skills for Russian editing, writing, editorial policy, promo copy, posts, and UX copy.
* [unclecatvn/agent-skills](https://github.com/unclecatvn/agent-skills) - Odoo Skills Documentation
* [gmapsscraper/google-maps-agent-skills](https://github.com/gmapsscraper/google-maps-agent-skills) - Claude Code / OpenClaw skills for Google Maps lead generation. Scrape businesses, extract emails, analyze competitors, write cold outreach — powered by gmapsscraper.io API.
* [sandbaseai/sandbase-skills](https://github.com/sandbaseai/sandbase-skills) - 88 installable open-source Agent Skills for research, social intelligence, marketing, and business workflows—compatible with Codex, Claude Code, Cursor, Gemini CLI, and DeepSeek Harness.
* [wrsmith108/linear-claude-skill](https://github.com/wrsmith108/linear-claude-skill) - Agent skill for managing Linear issues, projects, and teams. MCP tools, SDK automation, GraphQL API patterns.
* [stvlynn/dingtalk-wukong-skills](https://github.com/stvlynn/dingtalk-wukong-skills) - 钉钉生态与专业文档处理的 Agent 技能精选集。A curated collection of Agent Skills for DingTalk and professional document processing.
* [Rimagination/good-story](https://github.com/Rimagination/good-story) - Agent skill for evidence-faithful scientific storytelling
* [felipelobomotta-blip/book-genesis-v4](https://github.com/felipelobomotta-blip/book-genesis-v4) - An open-source writing runner that turns an idea into a manuscript, preserves the work, and sends it through a blind editorial read.
* [Forlives/21-day-self-interview](https://github.com/Forlives/21-day-self-interview) - 🪞 An AI existential-psychology counselor asks you 3 meaningful questions every night for 21 days — and remembers, reflecting your own words back to you. Bilingual zh/en. A Hermes Agent skill. 每晚三个问题，一面慢慢显影的镜子。
* [Yila-AI/awesome-research-skills](https://github.com/Yila-AI/awesome-research-skills) - Open-source Agent Skills for planning, drafting, revising, and polishing SCI/SSCI papers—while preserving evidence, citations, and claim strength.
* [joshua-zyy/academic-paper-writer](https://github.com/joshua-zyy/academic-paper-writer) - 面向 CS / AI / ML 领域的证据驱动、分节推进的论文写作 Agent Skill。
* [clay-run/agent-plugins](https://github.com/clay-run/agent-plugins) - Build with Clay in your AI coding agent - skills, MCP tools, and the clay CLI for Claude Code, Codex, and Cursor. Search companies and people, run enrichment routines, and query tables from natural language.
* [daniel-p-green/nbj-write-clearly](https://github.com/daniel-p-green/nbj-write-clearly) - A clear-writing agent skill grounded in the Google Developer Documentation Style Guide.
* [KurosawaGeeker/femboy-skill](https://github.com/KurosawaGeeker/femboy-skill) - 面向 MTF、crossdresser 与性别多元成年人的中文 Agent Skill，基于生如夏花知识库并加入医学安全护栏。
* [onepixelaway/frontend-textbooks](https://github.com/onepixelaway/frontend-textbooks) - A coding-agent skill for generating designed HTML textbooks and print-ready PDFs
* [abullaisi/upwork-skills](https://github.com/abullaisi/upwork-skills) - AI agent skills for Upwork freelancers, from a real Top Rated Plus playbook. Free, open, community-written. Not affiliated with Upwork.
* [Mr-potato-123/cumcm-paper-hand-skill](https://github.com/Mr-potato-123/cumcm-paper-hand-skill) - Agent Skill for CUMCM
* [SankaiAI/ats-optimized-resume-agent-skill](https://github.com/SankaiAI/ats-optimized-resume-agent-skill) - This is an agent skill for coding agents like Claude code to use to tailor your resume, avoiding AI-generated wordings and automatically generate a concise and completely well-formatted resume in Docx for you.
* [imfangli/mediastorm-copywriter](https://github.com/imfangli/mediastorm-copywriter) - 一个生成 「影视飓风(Mediastorm)」风格中文口播稿 的 Claude Code / Agent Skill。
* [kgraph57/mckinsey-style-visualization-skill](https://github.com/kgraph57/mckinsey-style-visualization-skill) - Agent Skill that turns messy notes into rendered strategy-consulting visuals, with SVG examples and validation.
* [vyralcontent/content-skills](https://github.com/vyralcontent/content-skills) - A free Agent Skill for writing short-form hooks, scripts, and carousels for TikTok, Reels, and YouTube Shorts.
* [RealZYZhang/paper-reader-heilmeier](https://github.com/RealZYZhang/paper-reader-heilmeier) - Agent skill: read STEM papers that answers Heilmeier's Catechism, so you get the big picture in one minute.
* [hezkvectory/hermes-edu-skills](https://github.com/hezkvectory/hermes-edu-skills) - 中文教育 Agent Skill Pack：教材同步、备考复习、拍照答疑、错题复盘、亲子陪学、阅读写作和教师工具，Hermes Agent 可直接使用，也可导出到 OpenClaw/Codex/Cursor/Claude Code。
* [squirrelscan/skills](https://github.com/squirrelscan/skills) - Agent skills for squirrelscan website audit tool
* [jonathimer/devmarketing-skills](https://github.com/jonathimer/devmarketing-skills) - Claude Code and AI Agents Skills for Developer Marketing.
* [gnipbao/knowledge-cat-ppt-skill](https://github.com/gnipbao/knowledge-cat-ppt-skill) - Story-first Agent Skill for creating, routing, and QA-checking PPT, HTML, and image-first presentation decks
* [geekjourneyx/travel-guidebook](https://github.com/geekjourneyx/travel-guidebook) - AI agent skill that generates beautifully typeset travel guidebook PDFs — from research to print, powered by parallel agents and Amap MCP.
* [nelsonwerd/idea-to-ship-skills](https://github.com/nelsonwerd/idea-to-ship-skills) - Composable Agent Skills (Claude + OpenAI Codex) for taking an idea from fuzzy → validated → sequenced build → shipped — a manual tier (ideate, deep-dive, prompt-pack) and an autonomous tier (autopilot, build-loop, audit-and-fix).
* [chadboyda/agent-gtm-skills](https://github.com/chadboyda/agent-gtm-skills) - 18 AI agent skills for go-to-market. Turn any coding agent into a GTM operator.
* [Upload-Post/viraloop](https://github.com/Upload-Post/viraloop) - OpenClaw AI agent skill for automated TikTok and Instagram carousel growth. Pass any website URL to analyze brand, competitors, colors, value proposition. Generates 6 visually coherent slides and auto-publishes with trending music via upload-post API. Built-in analytics and learning loop. Free tier, no credit card. Larry alternative.
* [jiankang1991/nsfc-benzi-audit](https://github.com/jiankang1991/nsfc-benzi-audit) - 一个用于国家自然科学基金（NSFC/国自然）申请书初稿诊断的 Agent Skill
* [liangdabiao/weekend-city-trip](https://github.com/liangdabiao/weekend-city-trip) - claude code / codex skill , 一个让 AI 帮你 5 分钟深度调研任意中国城市周末玩法的agent skill, 寻找精神旷野：户外消费告别长途远行、装备内卷，转向日常低成本微沉浸；菜市场、城市老街成为年轻人精神微旅行目的地，CityWalk 演化成主题探索路线，日常场景即可实现情绪解压。
* [BENZEMA216/ai-ecommerce-agent-skills](https://github.com/BENZEMA216/ai-ecommerce-agent-skills) - AI 电商 Agent Skills - OpenClaw 技能包：生图、电商设计、竞品分析、审美记忆系统
* [JangHyun-bin/korean-report-skills](https://github.com/JangHyun-bin/korean-report-skills) - Claude가 만든 한국어 문서가 어딘가 이상할 때 — 문장 표현과 디자인을 보완하는 Agent Skills
* [fei0810/bear-research-skills](https://github.com/fei0810/bear-research-skills) - 我在学术科研工作中的一些思路和方法，以 Agent Skill 形式沉淀下来和你分享。by 熊言熊语
* [xunhe730/ZotPilot](https://github.com/xunhe730/ZotPilot) - AI-powered Zotero research assistant — MCP server + agent skill
* [basecamp/skills](https://github.com/basecamp/skills) - AI agent skills for Basecamp
* [ZeoxCode/gaokao-advisor-skill](https://github.com/ZeoxCode/gaokao-advisor-skill) - 站在孩子和家长一边的高考志愿决策 Agent Skill
* [ibuildwith-ai/cody-product-builder](https://github.com/ibuildwith-ai/cody-product-builder) - Cody Product Builder is a guided workflow (agent skill) that helps knowledge workers and domain experts turn ideas into real products with AI. It structures your thinking from idea to shipped version so you can build without becoming a developer and without the work collapsing into chaos.
* [millwright-labs/minto-pyramid-skill](https://github.com/millwright-labs/minto-pyramid-skill) - Agent Skill: make Claude write in Barbara Minto's Pyramid Principle - answer first, grouped reasons, evidence under each.
* [ZongziForu/cn-law-hub](https://github.com/ZongziForu/cn-law-hub) - 中国法条与法律法规检索 Agent Skill｜Chinese legal research Agent Skill for retrieving and verifying Chinese laws from official sources｜支持具体法条检索、现行有效核验、10 个官方法律数据源
* [deancourse/agent-skill-lecture-builder](https://github.com/deancourse/agent-skill-lecture-builder) - 提供主題 or Markdown 講稿，透過 Agent Skills 單一 HTML 課程頁面。
* [zarazhangrui/lark-minutes-tasks](https://github.com/zarazhangrui/lark-minutes-tasks) - AI agent skill: read Lark meeting transcripts, extract action items, and actually get them done
* [NEU-ZHA/legal-ai-skills](https://github.com/NEU-ZHA/legal-ai-skills) - Open-source legal AI agent skills for PKULaw, citations, and DOCX workflows
* [Astro-wen/yongge-restaurant-skill](https://github.com/Astro-wen/yongge-restaurant-skill) - 勇哥餐饮.skill — 用勇哥（梁朝勇）方法论武装的餐饮创业决策 Agent Skill。含完整语料库、30+ 案例、保本线计算器、快招识别器、街景 360° 打分模型。
* [kangarooking/X-growth-skills](https://github.com/kangarooking/X-growth-skills) - 15 practical Agent skills for launching, growing, and monetizing an X account.
* [nostrband/ServiceGraph](https://github.com/nostrband/ServiceGraph) - AI Agent skills to access structured datasets for startup founders
* [LZheng0411/Lzheng-fitness](https://github.com/LZheng0411/Lzheng-fitness) - Lzheng的开源健身 Agent Skill 知识库
* [color4-alt/CiteCheck](https://github.com/color4-alt/CiteCheck) - Agent Skill: Check academic paper citations for format, queryability, thematic relevance, and semantic accuracy.
* [shanselman/nightscout-cgm-skill](https://github.com/shanselman/nightscout-cgm-skill) - GitHub Copilot Agent Skill for Nightscout CGM blood glucose analysis

## Science and Math

### Scientific Computing

* [K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) - Turn any AI agent into an AI Scientist. The #1 Agent Skills library for science, used by 190,000+ scientists worldwide. 165 ready-to-use validated skills plus 100+ scientific databases covering biology, chemistry, medicine, and drug discovery. Compatible with Cursor, Claude Code, Codex, Pi, Antigravity, and the open Agent Skills standard.
* [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad) - A library of agent skills for CAD, CAE and CAM
* [brycewang-stanford/Auto-Empirical-Research-Skills](https://github.com/brycewang-stanford/Auto-Empirical-Research-Skills) - 🔬 A curated collection of 23,000+ agent skills for empirical research across 8 social science disciplines. | 精选 23,000+ AI Agent 技能库，覆盖8大社会科学学科的实证研究。CoPaper.AI 20分钟完成一篇可复现的规范实证论文，并支持用户上传 Skills。-- Maintained by CoPaper.AI from Stanford REAP.
* [NVIDIA/skills](https://github.com/NVIDIA/skills) - Agent Skills for NVIDIA products — install into Claude Code, Codex, and other coding agents to run Physical AI, robotics, simulation, CUDA, and RAG workflows end to end.
* [aipoch/medical-research-skills](https://github.com/aipoch/medical-research-skills) - Hundreds of agent skills for medical research, including protocol design, data analysis, evidence insights, and academic writing.
* [PrathamLearnsToCode/paper2code](https://github.com/PrathamLearnsToCode/paper2code) - Agent skill to turn any arxiv paper into a working implementation
* [huangkiki/dailypaper-skills](https://github.com/huangkiki/dailypaper-skills) - 用Agent skills打造我的论文流水线
* [ClawBio/ClawBio](https://github.com/ClawBio/ClawBio) - 🦖 ClawBio - The first bioinformatics-native AI agent skill library. Local-first. Reproducible. Open. Free.
* [917Dhj/DeepPaperNote](https://github.com/917Dhj/DeepPaperNote) - DeepPaperNote is an agent skill for deep-reading a single paper and generating high-quality Obsidian-style research notes. Works with Claude Code, Codex, Cursor, Copilot, Gemini CLI, and more.
* [ForgeCAD/forgecad-public-kit](https://github.com/ForgeCAD/forgecad-public-kit) - Public companion kit for ForgeCAD: examples, agent skills, docs links, and issue tracking. The hosted CAD app and core source live elsewhere.
* [LeonChaoX/qinyan-academic-skills](https://github.com/LeonChaoX/qinyan-academic-skills) - A curated, multilingual library of 182 installable AI agent skills for end-to-end academic research—spanning literature discovery, scientific writing, grant development, bioinformatics, drug discovery, clinical research, machine learning, and data analysis.
* [luwill/research-skills](https://github.com/luwill/research-skills) - Some commonly used research experiences and processes are encapsulated into Agent skills.
* [labarba/sciwrite](https://github.com/labarba/sciwrite) - Agent Skill for AI-assisted manuscript writing review, based on Dr. Kristin Sainani's "Writing in the Sciences" methodology.
* [bioMate-AI/biomate-bioconductor-kb](https://github.com/bioMate-AI/biomate-bioconductor-kb) - BioMate-KB Bioconductor Skills — 200 packages (top 100 by downloads + 100 rising stars) as vignette-grounded Claude/agent skills, with per-package workflow recipes
* [hanlulong/econ-writing-skill](https://github.com/hanlulong/econ-writing-skill) - Agent Skill that transforms AI assistants into expert economics paper writers. Synthesizes 50+ guides by Cochrane, McCloskey, Shapiro, Head, Bellemare, Goldin, Kremer. Compatible with Claude Code and OpenAI Codex.
* [InternScience/Awesome-Scientific-Skills](https://github.com/InternScience/Awesome-Scientific-Skills) - An open, curated collection of Agent Skills for scientific research — clone it, use it, extend it!
* [njzjz/nsfc-agent-skills](https://github.com/njzjz/nsfc-agent-skills) - 用于写NSFC本子的Agent Skills
* [Boom5426/Nature-Paper-Skills](https://github.com/Boom5426/Nature-Paper-Skills) - Agent skills for drafting, revising, auditing, and resubmitting Nature-style journal manuscripts.
* [puran-water/autocad-mcp](https://github.com/puran-water/autocad-mcp) - MCP server for AutoCAD LT v3.1: freehand AutoLISP execution, 8 consolidated tools, File IPC + ezdxf backends, focus-free dispatch, undo/redo, P&ID symbols, and robust IPC with ESC prefix and UTF-8 fallback. Companion agent skill: puran-water/autocad-drafting
* [jaechang-hits/SciAgent-Skills](https://github.com/jaechang-hits/SciAgent-Skills) - 197 bioinformatics & life science skills for Claude Code and AI agents — BixBench 92.0% accuracy. RNA-seq, single-cell, drug discovery, proteomics, and more. Powers OmicsHorizon.
* [arpitg1304/robotics-agent-skills](https://github.com/arpitg1304/robotics-agent-skills) - Agent skills that make AI coding assistants write production-grade robotics software. ROS1, ROS2, design patterns, SOLID principles, and testing — for Claude Code, Cursor, Copilot, and any SKILL.md-compatible agent.
* [Rimagination/good-question](https://github.com/Rimagination/good-question) - A portable agent skill for sharpening research questions.
* [wooly99/geng-academic-fraud-detector](https://github.com/wooly99/geng-academic-fraud-detector) - 耿同学skill，学术论文打假检测 agent skill，致敬耿同学讲故事
* [k-telux/OpticalModeler](https://github.com/k-telux/OpticalModeler) - Evidence-gated Agent Skill for reconstructing 2D photonics schematics as physically auditable Blender optical tables with CAD, beam-path, mechanics, and render proof.
* [ai4s-research/ai4s-skills](https://github.com/ai4s-research/ai4s-skills) - Open-source agent skills for AI for Science: topic exploration, literature survey, experiments, paper writing, and integrity audit — driven by any coding agent.
* [matlab/agent-skills-playground](https://github.com/matlab/agent-skills-playground) - A sandbox for prototyping and demonstrating Agent Skills for MATLAB and Simulink work.
* [tigerless-labs/paper-radar](https://github.com/tigerless-labs/paper-radar) - Finds the AI papers 28 tech companies put on arXiv over any date range, and splits lead authorship from bylines. A SKILL.md agent skill — no ML, no state, stdlib only.
* [dbwls99706/ros2-engineering-skills](https://github.com/dbwls99706/ros2-engineering-skills) - Agent skill for production-grade ROS 2 development. Progressive-disclosure SKILL.md covering workspace, nodes, executors, QoS, ros2_control, Nav2, MoveIt 2, real-time, and deployment. Works with Claude Code, Codex, Cursor, Gemini CLI.
* [jinzhezenggroup/computational-chemistry-agent-skills](https://github.com/jinzhezenggroup/computational-chemistry-agent-skills) - Agent skills to run computational-chemistry tasks, used in OpenClaw
* [NVlabs/ASPIRE](https://github.com/NVlabs/ASPIRE) - ASPIRE: Agentic /Skills Discovery for Robotics
* [Arcadia-1/gmoverid-skill](https://github.com/Arcadia-1/gmoverid-skill) - Agent skill for simulating gmoverid characteristics and gmoverid-based design
* [RConsortium/pharma-skills](https://github.com/RConsortium/pharma-skills) - A collection of agent skills for BioPharma use cases GSDBench Intake https://rconsortium.github.io/pharma-skills/gsdbench-intake/
* [Tyche-MKR/scientific-agent-skills](https://github.com/Tyche-MKR/scientific-agent-skills) - Turn any AI agent into an AI Scientist. The #1 Agent Skills library for science, used by 190,000+ scientists worldwide. 165 ready-to-use validated skills plus 100+ scientific databases covering biology, chemistry, medicine, and drug discovery. Compatible with Cursor, Claude Code, Codex, Pi, Antigravity, and the open Agent Skills standard.
* [SciMate-AI/HPC-Skills](https://github.com/SciMate-AI/HPC-Skills) - Portable agent skills for High Performance Computing workflows across OpenFOAM, SU2, LS-DYNA, FEniCS, CalculiX, ElmerFEM, PETSc, hypre, Trilinos, LAMMPS, GROMACS, Quantum ESPRESSO, VASP, Gaussian, ParaView, and Gmsh, plus MPI, GPU, Spack, reproducible toolchains, and cluster orchestration.
* [telekinesis-ai/telekinesis-examples](https://github.com/telekinesis-ai/telekinesis-examples) - Telekinesis Agentic Skill Library: build AI-powered Computer Vision, Robotics and Physical AI applications.
* [jaakla/openmapstack](https://github.com/jaakla/openmapstack) - AI-agent skill for reproducible, validated GIS analysis — from authoritative data discovery to interactive maps, on an open-first geospatial stack (OSM, Overture, STAC, DuckDB, PostGIS, QGIS, MapLibre).
* [HeshamFS/materials-simulation-skills](https://github.com/HeshamFS/materials-simulation-skills) - Agent Skills for computational materials science -- numerical stability, solvers, meshing, convergence, and simulation workflows.
* [Power-Agent/PowerSkills](https://github.com/Power-Agent/PowerSkills) - PowerSkills are some Agent Skills for power system analysis. This repository provides AI agents with specialized knowledge and instructions for performing power system simulations, analysis, and optimization using various power system software tools.
* [AlterLab-IEU/AlterLab-Academic-Skills](https://github.com/AlterLab-IEU/AlterLab-Academic-Skills) - 239 evaluated academic Claude/agent skills across 17 research domains (bioinformatics, data science, clinical, social-science methods, Turkish academia & more). Executable eval per skill, deterministic citation verifier, research→write→review→publish pipeline, and a skill-finder front door. Claude Code, Cursor, Codex, Gemini CLI & Copilot.
* [variomeanalytics/bioinformatics-agent-skills](https://github.com/variomeanalytics/bioinformatics-agent-skills) - MCP server for bioinformatics agent skills — query a knowledge graph of 78 bioinformatics workflows directly from Claude Code

## Other

* [Shubhamsaboo/awesome-llm-apps](https://github.com/Shubhamsaboo/awesome-llm-apps) - 100+ AI Agents, Agent Skills and RAG Apps - Free and Open Source.
* [teng-lin/notebooklm-py](https://github.com/teng-lin/notebooklm-py) - Unofficial Python API and agentic skill for Google Gemini Notebook. Full programmatic access to NotebookLM's features—including capabilities the web UI doesn't expose—via Python, CLI, and AI agents like Claude Code, Codex, and OpenClaw.
* [jihe520/MathModelAgent](https://github.com/jihe520/MathModelAgent) - 🤖📐专为数学建模设计的 Agent & skills ,自动完成数学建模，生成一份完整的可以直接提交的论文。 An Agent Designed for Mathematical Modeling ,Automatically complete mathmodel and generate a complete paper ready for submission.
* [addyosmani/web-quality-skills](https://github.com/addyosmani/web-quality-skills) - Agent Skills for optimizing web quality based on Lighthouse and Core Web Vitals.
* [jeremylongshore/tons-of-skills-marketplace](https://github.com/jeremylongshore/tons-of-skills-marketplace) - Model-agnostic agent-skills platform with a harness-free canonical layer, verified adapters, and the ccpi package manager. Explore at tonsofskills.com.
* [FrancyJGLisboa/agent-skills-platform](https://github.com/FrancyJGLisboa/agent-skills-platform) - Build tested agent skills and govern their lifecycle through a user-defined marketplace: evidence, discovery, updates, rollback, quarantine, and 17-platform distribution.
* [yetone/native-feel-skill](https://github.com/yetone/native-feel-skill) - An Agent Skill for designing cross-platform desktop apps that feel native — distilled from Raycast's 2.0 deep-dive and reverse engineering of Raycast Beta.app. Eight architectural tenets, four-layer architecture, WebKit/WebView2 survival guide, 75-item ship audit.
* [nateherkai/scroll-craft](https://github.com/nateherkai/scroll-craft) - An agent skill for building premium, immersive, scroll-driven websites. Works with Codex, Claude Code, and other coding agents. Also available as a Claude Code plugin.
* [AvdLee/Swift-Concurrency-Agent-Skill](https://github.com/AvdLee/Swift-Concurrency-Agent-Skill) - Add expert Swift Concurrency guidance to your AI coding tool (Agent Skills open format): safe concurrency, performance optimization, and Swift 6 migration.
* [deusyu/translate-book](https://github.com/deusyu/translate-book) - Agent skill for Codex, Claude Code, and OpenClaw that translates entire books (PDF/DOCX/EPUB) into any language using parallel subagents.
* [AvdLee/Xcode-Build-Optimization-Agent-Skill](https://github.com/AvdLee/Xcode-Build-Optimization-Agent-Skill) - An Agent Skill helping you to optimize Xcode incremental and clean builds by running benchmarks and optimizing build settings.
* [863401402/she-love-me](https://github.com/863401402/she-love-me) - 她不一样 恋情分析室 — 微信聊天记录恋爱分析 Agent Skill （曾用名：她爱我吗？）
* [fayazara/macos-app-skills](https://github.com/fayazara/macos-app-skills) - AI coding agent skills for building, shipping, and maintaining native macOS apps
* [elastic/agent-skills](https://github.com/elastic/agent-skills) - Official Elastic Skills
* [twostraws/Swift-Concurrency-Agent-Skill](https://github.com/twostraws/Swift-Concurrency-Agent-Skill) - Swift Concurrency agent skill for Claude Code, Codex, and other AI tools.
* [VikashLoomba/copilot-mcp](https://github.com/VikashLoomba/copilot-mcp) - A VSCode extension that lets you find and install Agent Skills and MCP Apps to use with GitHub Copilot, Claude Code, and Codex CLI.
* [google-ai-edge/litert-samples](https://github.com/google-ai-edge/litert-samples) - LiteRT and LiteRT-LM sample apps, model recipes, agent skills and utilities.
* [TheQtCompanyRnD/agent-skills](https://github.com/TheQtCompanyRnD/agent-skills) - Official Qt AI engineering skills for Claude Code, Codex, Copilot, Gemini,and other AI coding tools
* [twostraws/SwiftData-Agent-Skill](https://github.com/twostraws/SwiftData-Agent-Skill) - SwiftData agent skill for Claude Code, Codex, and other AI tools.
* [K-Dense-AI/claude-skills-mcp](https://github.com/K-Dense-AI/claude-skills-mcp) - MCP server for searching and retrieving Scientific Agent Skills using vector search
* [AvdLee/Core-Data-Agent-Skill](https://github.com/AvdLee/Core-Data-Agent-Skill) - An Agent Skill focused on Apple’s Core Data framework, helping with data modeling, fetch requests, performance, and common persistence patterns.
* [jlevy/simple-modern-uv](https://github.com/jlevy/simple-modern-uv) - A powerful, minimal agent skill and template for modern Python projects with uv
* [CodeDrobe/skills](https://github.com/CodeDrobe/skills) - Agent Skills for theming AI desktop apps: reference image → reversible Codex/WorkBuddy skin → verify, repair, publish. | 给 AI 桌面应用换肤的 Agent Skills：参考图 → 可逆皮肤 → 验证、修复、发布。
* [awp-core/awp-skill](https://github.com/awp-core/awp-skill) - Agent skill for AWP RootNet protocol (testnet) — query, stake, govern, and monitor on-chain
* [qdrant/skills](https://github.com/qdrant/skills) - Agent skills for Qdrant vector search: scaling, performance optimization, search quality, monitoring, deployment, model migration, version upgrades, and SDK usage across Python, TypeScript, Rust, Go, .NET, Java
* [miunasu/IDA-Skill](https://github.com/miunasu/IDA-Skill) - 使用skill让 AI Agent 像安全分析师一样分析恶意样本 | AI Agent skill for automated malware analysis using IDA Pro
* [baidu-netdisk/bdpan-storage](https://github.com/baidu-netdisk/bdpan-storage) - Agent Skill for Baidu Netdisk (百度网盘) — upload, download, transfer, share, search files via natural language. Works with Claude Code, Cursor, Codex, Gemini CLI, OpenClaw.
* [bybit-exchange/svg-diagram](https://github.com/bybit-exchange/svg-diagram) - Agent skill that draws architecture, flowchart, sequence, data-flow and lifecycle diagrams as hand-placed SVG, to one linted house style.
* [OpenZeppelin/openzeppelin-skills](https://github.com/OpenZeppelin/openzeppelin-skills) - Agent skills for secure smart contract development with OpenZeppelin Contracts libraries
* [mohitmishra786/low-level-dev-skills](https://github.com/mohitmishra786/low-level-dev-skills) - A curated suite of AI agent skills for systems and low-level programming with C/C++, Rust, and Zig toolchains, covering compilers, debuggers, profilers, build systems, sanitizers, and binary analysis
* [shizhilya/yuan](https://github.com/shizhilya/yuan) - Yuan (元) — a unified destiny-reading skill for Codex, Claude Code, and Agent Skills runtimes. One input surface, six methods (BaZi / Cheng Gu / Numerology / Western / Vedic / Zi Wei), production-grade output.
* [ystemsrx/sql_to_ER](https://github.com/ystemsrx/sql_to_ER) - 【在线免费使用】 简单快速将SQL或DBML转换为美观的ER图（支持 Agent Skill）/ The best SQL to ER Diagram converter (Support Agent Skill).
* [modular/skills](https://github.com/modular/skills) - Agent Skills for Mojo and MAX development
* [resend/resend-skills](https://github.com/resend/resend-skills) - Agent Skills for working with Resend to send and receive emails.
* [sweetcornna/mathodology](https://github.com/sweetcornna/mathodology) - 专为数学建模竞赛设计的数模 Agent Skills：MCM/ICM 美赛、CUMCM 国赛、华数杯、M3、HiMCM 等，面向 Claude Code 与 Codex 的获奖级建模工作流。Math modeling contest skills for Claude Code & Codex.
* [ascend-ai-coding/awesome-ascend-skills](https://github.com/ascend-ai-coding/awesome-ascend-skills) - A comprehensive knowledge base for Huawei Ascend NPU development, structured as distributed Agent Skills. https://ascend-ai-coding.github.io/awesome-ascend-skills/
* [daman-ovo-0404/tarot-skill](https://github.com/daman-ovo-0404/tarot-skill) - AI 塔罗占卜 Agent Skill — 78 牌完整牌义、6 种牌阵、牌间关系理论体系、真随机抽牌脚本
* [datadog-labs/agent-skills](https://github.com/datadog-labs/agent-skills) - Public repository for Datadog Agent Skills
* [tech-shrimp/agent-skills-examples](https://github.com/tech-shrimp/agent-skills-examples)
* [paulp-o/ask-user-questions-mcp](https://github.com/paulp-o/ask-user-questions-mcp) - Better 'AskUserQuestion' - A lightweight MCP server/OpenCode plugin/Agent Skills + CLI interface which allows parallel AI agents ask questions to you. Be the human in the human-in-the-loop!
* [yzlnew/infra-skills](https://github.com/yzlnew/infra-skills) - A collection of specialized agent skills for AI infrastructure development, enabling Claude Code to write, optimize, and debug high-performance systems.
* [liyupi/github-global](https://github.com/liyupi/github-global) - 2026 年编程导航 AI 编程实战新项目，基于 Next.js 15 + GitHub App + OpenRouter 的 GitHub 仓库 AI 文档翻译 SaaS 平台，支持可视化翻译配置、一键多语言翻译、自动创建 PR、Webhook 增量翻译、自定义大模型等。覆盖 GitHub App OAuth 认证、GitHub REST API 对接、OpenRouter 多模型接入、Prisma + MySQL 全栈开发、Vercel 部署、Ngrok 内网穿透、Cursor Vibe Coding + MCP + Agent Skills 等核心技术。用一套教程掌握 AI 编程全流程，从需求调研到部署上线，不到一周学完，给你的简历增加竞争力
* [smartcontractkit/chainlink-agent-skills](https://github.com/smartcontractkit/chainlink-agent-skills) - [PUBLIC] Repository for Chainlink Skills that implement https://agentskills.io/specification
* [JimmyLv/bibigpt-skill](https://github.com/JimmyLv/bibigpt-skill) - OpenClaw / Claude Code / Codex Agent skill for summarizing videos/audio via BibiGPT CLI (bibi)
* [sonilo-ai/skills](https://github.com/sonilo-ai/skills) - Agent skills for Sonilo's licensed music, sound-effects, dubbing, and audio-ducking API
* [UditAkhourii/cdaf](https://github.com/UditAkhourii/cdaf) - CDAF (Cached Descriptive Asset Files) - open sidecar format for video so AI agents stop re-analyzing the same footage. Spec, CLI, agent skill, reproducible benchmark.
* [apollographql/skills](https://github.com/apollographql/skills) - Apollo GraphQL Agent Skills
* [Dimon94/skills](https://github.com/Dimon94/skills) - 个人 agent skill 库 — skills/ 为唯一真相源，agent 目录经 symlink 消费
* [kar2phi/video-lens](https://github.com/kar2phi/video-lens) - video-lens is a coding agent skill that fetches a YouTube transcript and generates a structured HTML report: executive summary, key points, analysis, takeaway, timestamped topic outline, and an embedded in-page player. No API keys, no external services beyond the coding agent itself.
* [weaviate/agent-skills](https://github.com/weaviate/agent-skills) - Agent Skills to empower developers building AI applications with Weaviate.
* [intellectronica/gemini-cli-skillz](https://github.com/intellectronica/gemini-cli-skillz) - Gemini CLI extension for Anthropic-style Agent Skills via skillz MCP server
* [ollygarden/opentelemetry-agent-skills](https://github.com/ollygarden/opentelemetry-agent-skills) - Vendor-neutral OpenTelemetry skills for AI coding agents, grounded in upstream sources
* [trustwallet/tw-agent-skills](https://github.com/trustwallet/tw-agent-skills)
* [rstackjs/agent-skills](https://github.com/rstackjs/agent-skills) - A collection of Agent Skills for Rstack.
* [ahacker-1/cre-agent-skills](https://github.com/ahacker-1/cre-agent-skills) - Commercial real estate AI agent skills for CRE underwriting, due diligence, financing, brokerage, legal and closing workflows - standalone prompts for Claude Code, ChatGPT, Cursor, and other LLMs.
* [monte-carlo-data/mc-agent-toolkit](https://github.com/monte-carlo-data/mc-agent-toolkit) - Official Monte Carlo toolkit for AI coding agents. Skills and plugins that bring data and agent observability — monitoring, triaging, troubleshooting, health checks — into Claude Code, Cursor, and more.
* [dash0hq/agent-skills](https://github.com/dash0hq/agent-skills) - OpenTelemetry skills and reference documentation for AI coding assistants - instrumentation patterns, telemetry quality guides, and Dash0 integration
* [hookdeck/webhook-skills](https://github.com/hookdeck/webhook-skills) - Webhook integration skills for AI coding agents (Claude Code, Cursor, Copilot). Step-by-step guidance for setting up webhook receivers, signature verification, and event handling for Stripe, Shopify, GitHub, and more. Built on the Agent Skills specification.
* [zeke/faster-chrome-devtools-skill](https://github.com/zeke/faster-chrome-devtools-skill) - Agent skill that makes Chrome DevTools faster
* [JustSteveKing/api-skill](https://github.com/JustSteveKing/api-skill) - An opinionated agent skill that encodes production-ready patterns for building REST APIs in Laravel 13+.
* [qkycir-123/dsh-run2skill](https://github.com/qkycir-123/dsh-run2skill) - Automatically turn successful DeepSeek Harness sessions into reusable, reviewable Agent Skills.
* [Ronvaknins/ableton-extensions-skill](https://github.com/Ronvaknins/ableton-extensions-skill) - An Agent Skill that teaches an AI coding agent how to scaffold, write, build, and package Ableton Live extensions with the Ableton Extensions SDK (@ableton-extensions/sdk, TypeScript).
* [Waybox-AI/roadtrip-skill](https://github.com/Waybox-AI/roadtrip-skill) - An AI agent skill that turns "start + days" into a road trip you can actually drive.
* [DigitalArchivst/Open-Genealogy](https://github.com/DigitalArchivst/Open-Genealogy) - GPS-aligned AI prompts and Agent Skills for genealogical research (CC-BY-NC-SA-4.0)
* [kitze/council](https://github.com/kitze/council) - 🏛 Agent skill: your coding agent must convene the other agent CLIs on your machine and deliberate for X turns before giving you a plan
* [xiaofeng-928/chinese-longnovel-skill](https://github.com/xiaofeng-928/chinese-longnovel-skill) - 面向 Codex / Claude Code 的中文长篇网络小说写作 Skill：分层上下文组装、50章分阶段规划、状态回证、伏笔追踪与回收、一致性审查和自动修复。Chinese web novel writing agent skill.
* [dripips/plain-prose](https://github.com/dripips/plain-prose) - Agent skill that removes AI writing patterns from English, Russian and German prose. Merges stop-slop and avoid-ai-writing, adds a zero-dependency checker.
* [youdotcom-oss/agent-skills](https://github.com/youdotcom-oss/agent-skills) - You.com skills and plugins for web search, content extraction, research, finance, and integration discovery, helping AI agents build with up-to-date web context.
* [brunoborges/jdb-agentic-debugger](https://github.com/brunoborges/jdb-agentic-debugger) - Agent Skill for debugging Java applications in real time using JDB (Java Debugger CLI)
* [HLND2T/CS2_VibeSignatures](https://github.com/HLND2T/CS2_VibeSignatures) - Generate CS2 signatures via Agent SKILLS with ida-pro-mcp
* [Hanyuyuan6/remote-gpu-trainer](https://github.com/Hanyuyuan6/remote-gpu-trainer) - An Agent Skill for the DL experiment lifecycle: RUN (a GPU you own or rent) → VERIFY the number is real → DELIVER reproducible, single-source figures and tables.
* [GordenSun/Math2GGB](https://github.com/GordenSun/Math2GGB) - A Cursor Agent Skill that turns math problems (esp. geometry) into faithful + interactive GeoGebra .ggb files by driving the real GeoGebra engine.
* [jinhanbuilds/bushiershi](https://github.com/jinhanbuilds/bushiershi) - 对抗模型输出不良表达习惯的 Agent Skill
* [Jerry-del975/ai-zemax-optical-design](https://github.com/Jerry-del975/ai-zemax-optical-design) - Automated optical design agent skill for Ansys Zemax OpticStudio via ZOS-API — AI-driven requirements parsing, lens modeling, staged optimization, and design reporting.
* [likweitan/abap-skills](https://github.com/likweitan/abap-skills) - Agent Skills for ABAP Developers
* [maxedapps/agent-skills](https://github.com/maxedapps/agent-skills)

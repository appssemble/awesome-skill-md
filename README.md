# Awesome SKILL.md [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of the most-starred, community-loved [Agent Skills](https://www.anthropic.com/news/agent-skills) — repositories built around `SKILL.md` files that teach AI coding agents (Claude Code, Codex, Cursor, Gemini CLI, and others) new capabilities.

**Agent Skills** are folders containing a `SKILL.md` file — a Markdown document with YAML frontmatter that packages reusable instructions, scripts, and resources an agent loads on demand. This list collects **241 hand-vetted repositories**: individual skills, curated collections, official vendor skills, and the tooling around them.

## Contents

- [Frameworks & Methodology](#frameworks--methodology)
- [Official & Vendor](#official--vendor)
- [Curated Lists](#curated-lists)
- [Tooling & Management](#tooling--management)
- [Security](#security)
- [Software Engineering](#software-engineering)
- [Web & Frontend](#web--frontend)
- [UI/UX & Design](#uiux--design)
- [Diagrams & Visualization](#diagrams--visualization)
- [Docs, Slides & Office](#docs-slides--office)
- [Writing & Anti-Slop](#writing--anti-slop)
- [Marketing, SEO & Growth](#marketing-seo--growth)
- [Product & Project Management](#product--project-management)
- [Research & Science](#research-science)
- [Knowledge Management](#knowledge-management)
- [Browser Automation](#browser-automation)
- [Media: Image & Video](#media-image--video)
- [Mobile & Apple](#mobile--apple)
- [Self-Improving Skills](#self-improving-skills)
- [Domain-Specific](#domain-specific)
- [Learning & Guides](#learning--guides)
- [Contributing](#contributing)

---
### Frameworks & Methodology

- **[obra/superpowers](https://github.com/obra/superpowers)** — Make your coding agent follow a disciplined TDD, debugging, and review workflow
- **[affaan-m/ECC](https://github.com/affaan-m/ECC)** — Agent harness optimization framework with skills, memory, security, and research-first workflows.
- **[msitarzewski/agency-agents](https://github.com/msitarzewski/agency-agents)** — Specialized AI agency agent collection with personality- and workflow-driven specialists.
- **[garrytan/gstack](https://github.com/garrytan/gstack)** — Opinionated Claude Code setup for engineering leadership and execution roles.
- **[bytedance/deer-flow](https://github.com/bytedance/deer-flow)** — Long-horizon SuperAgent harness for research, coding, and autonomous multi-stage tasks.
- **[shanraisshan/claude-code-best-practice](https://github.com/shanraisshan/claude-code-best-practice)** — Practical guidance for moving from quick coding prompts to engineered agentic workflows.
- **[Yeachan-Heo/oh-my-claudecode](https://github.com/Yeachan-Heo/oh-my-claudecode)** — Teams-first multi-agent orchestration for Claude Code.
- **[muratcankoylan/Agent-Skills-for-Context-Engineering](https://github.com/muratcankoylan/Agent-Skills-for-Context-Engineering)** — Apply context-engineering and multi-agent patterns to larger workflows
- **[jnMetaCode/superpowers-zh](https://github.com/jnMetaCode/superpowers-zh)** — Use the superpowers methodology in Chinese
- **[tw93/Waza](https://github.com/tw93/Waza)** — Encode your engineering habits as repeatable agent workflows
- **[gotalab/cc-sdd](https://github.com/gotalab/cc-sdd)** — Drive spec-driven development across multiple coding agents
- **[HughYau/qiushi-skill](https://github.com/HughYau/qiushi-skill)** — Give the agent structured thinking frameworks for tough decisions
- **[SnailSploit/Claude-Red](https://github.com/SnailSploit/Claude-Red)** — Agent skill repository.
- **[DenisSergeevitch/agents-best-practices](https://github.com/DenisSergeevitch/agents-best-practices)** — Follow best practices for building production-safe harnesses
- **[elementalsouls/Claude-OSINT](https://github.com/elementalsouls/Claude-OSINT)** — Agent skill repository.
- **[xu-xiang/everything-claude-code-zh](https://github.com/xu-xiang/everything-claude-code-zh)** — Use a full Claude Code configuration system in Chinese
- **[wondelai/skills](https://github.com/wondelai/skills)** — Apply 60+ product, design, and engineering methodology skills
- **[tjboudreaux/cc-thinking-skills](https://github.com/tjboudreaux/cc-thinking-skills)** — Apply 18 mental models and critical-thinking frameworks
- **[sno-ai/mda](https://github.com/sno-ai/mda)** — Agent skill repository.
- **[gamedev-skills/awesome-gamedev-agent-skills](https://github.com/gamedev-skills/awesome-gamedev-agent-skills)** — Agent skill repository.
- **[K-Dense-AI/mimeo](https://github.com/K-Dense-AI/mimeo)** — Agent skill repository.


### Official & Vendor

- **[anthropics/skills](https://github.com/anthropics/skills)** — Learn the official SKILL.md format from Anthropic's reference examples and template
- **[anthropics/claude-plugins-official](https://github.com/anthropics/claude-plugins-official)** — Install vetted plugin and skill bundles from Anthropic's official directory
- **[google/skills](https://github.com/google/skills)** — Use Google's official skills for Google Cloud and Gemini
- **[huggingface/skills](https://github.com/huggingface/skills)** — Let agents work the Hugging Face Hub and run ML tasks
- **[google-labs-code/stitch-skills](https://github.com/google-labs-code/stitch-skills)** — Design and build UIs with Google Labs' Stitch skills
- **[OpenSenseNova/SenseNova-Skills](https://github.com/OpenSenseNova/SenseNova-Skills)** — Automate office tasks — images, PPT, and data — with SenseNova skills
- **[google-gemini/gemini-skills](https://github.com/google-gemini/gemini-skills)** — Build against the Gemini API with Google's official skills
- **[microsoft/skills](https://github.com/microsoft/skills)** — Ground coding agents in Azure SDK skills and configs
- **[supabase/agent-skills](https://github.com/supabase/agent-skills)** — Build database and backend features with official Supabase skills
- **[expo/skills](https://github.com/expo/skills)** — Build, deploy, and debug Expo apps with official skills
- **[cloudflare/skills](https://github.com/cloudflare/skills)** — Build on Cloudflare Workers with official skills
- **[WordPress/agent-skills](https://github.com/WordPress/agent-skills)** — Build WordPress blocks, themes, and plugins correctly
- **[microsoft/skills-for-fabric](https://github.com/microsoft/skills-for-fabric)** — Build on Microsoft Fabric with official skill bundles
- **[hashicorp/agent-skills](https://github.com/hashicorp/agent-skills)** — Work with Terraform, Packer, and HCL using HashiCorp's skills
- **[solana-foundation/solana-dev-skill](https://github.com/solana-foundation/solana-dev-skill)** — Build on Solana with the foundation's official skill
- **[microsoft/power-platform-skills](https://github.com/microsoft/power-platform-skills)** — Build Power Platform Pages, Apps, and Canvas
- **[posit-dev/skills](https://github.com/posit-dev/skills)** — Develop R, Shiny, and Quarto projects with Posit's skills


### Curated Lists

- **[ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills)** — Browse a vetted directory when hunting for a ready-made Claude skill or plugin
- **[VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills)** — A curated collection of 5,000+ OpenClaw skills with installer tooling and workflows.
- **[sickn33/antigravity-awesome-skills](https://github.com/sickn33/antigravity-awesome-skills)** — Install from a large aggregated library of ready-to-use skill playbooks
- **[sickn33/agentic-awesome-skills](https://github.com/sickn33/agentic-awesome-skills)** — Large installable catalog of Claude Code and agentic SKILL files with workflow tooling.
- **[github/awesome-copilot](https://github.com/github/awesome-copilot)** — Community-contributed instructions, agents, skills, and configurations to help you make the most of GitHub Copilot.
- **[tech-leads-club/agent-skills](https://github.com/tech-leads-club/agent-skills)** — Install from a security-reviewed catalog of verified skills
- **[libukai/awesome-agent-skills](https://github.com/libukai/awesome-agent-skills)** — Use as a guide and resource hub for getting started with skills
- **[rohitg00/awesome-claude-code-toolkit](https://github.com/rohitg00/awesome-claude-code-toolkit)** — Browse a big toolkit of Claude Code agents, plugins, and skills
- **[bergside/awesome-design-skills](https://github.com/bergside/awesome-design-skills)** — Find design-focused SKILL.md and DESIGN.md files
- **[Prat011/awesome-llm-skills](https://github.com/Prat011/awesome-llm-skills)** — Browse a catalog of LLM and agent skills and resources
- **[daymade/claude-code-skills](https://github.com/daymade/claude-code-skills)** — Browse a marketplace of 64+ production skills with a skill-creator
- **[Gentleman-Programming/Gentleman-Skills](https://github.com/Gentleman-Programming/Gentleman-Skills)** — Pull community best-practice coding skills for frameworks
- **[JackyST0/awesome-agent-skills](https://github.com/JackyST0/awesome-agent-skills)** — Find Agent Skills that work across Cursor, Claude Code, and Copilot
- **[nicepkg/ai-workflow](https://github.com/nicepkg/ai-workflow)** — Install 170+ prebuilt skills organized as AI workflows
- **[crystian/skills](https://github.com/crystian/skills)** — Open collection of AI agent skills — reusable, framework-agnostic SKILL.md packages for Claude Code and beyond. Install with npx skills add crystian/skills
- **[michaelboeding/skills](https://github.com/michaelboeding/skills)** — Personal collection of agent skills using the open SKILL.md standard. Works with Claude (claude.ai, Claude Code, API), Cursor, and other AI assistants.


### Tooling & Management

- **[openclaw/openclaw](https://github.com/openclaw/openclaw)** — Cross-platform AI assistant runtime with skill-driven agent workflows.
- **[Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify)** — AI coding assistant skill ecosystem that turns code and documents into a queryable knowledge graph.
- **[code-yeongyu/oh-my-openagent](https://github.com/code-yeongyu/oh-my-openagent)** — Codex/OpenCode-oriented coding agent harness with tooling integrations.
- **[HKUDS/CLI-Anything](https://github.com/HKUDS/CLI-Anything)** — CLI-Anything turns many native apps and CLIs into agent-native SKILL-driven tooling.
- **[abhigyanpatwari/GitNexus](https://github.com/abhigyanpatwari/GitNexus)** — Client-side knowledge-graph tool for repository and codebase exploration.
- **[wshobson/agents](https://github.com/wshobson/agents)** — Multi-harness agentic plugin marketplace for Claude Code, Codex CLI, Cursor, OpenCode, GitHub Copilot, and Gemini CLI
- **[sipeed/picoclaw](https://github.com/sipeed/picoclaw)** — Deployable skill tooling bundle for lightweight Claude Code automation.
- **[googleworkspace/cli](https://github.com/googleworkspace/cli)** — Google Workspace CLI — one command-line tool for Drive, Gmail, Calendar, Sheets, Docs, Chat, Admin, and more. Dynamically built from Google Discovery Service. Includes…
- **[yusufkaraaslan/Skill_Seekers](https://github.com/yusufkaraaslan/Skill_Seekers)** — Convert your docs, repos, or PDFs into installable Agent Skills
- **[microsoft/SkillOpt](https://github.com/microsoft/SkillOpt)** — Train and refine reusable skill documents automatically
- **[numman-ali/openskills](https://github.com/numman-ali/openskills)** — Install skills universally across multiple agent platforms
- **[virgiliojr94/book-to-skill](https://github.com/virgiliojr94/book-to-skill)** — Turn a technical book into a study-ready agent skill
- **[refly-ai/refly](https://github.com/refly-ai/refly)** — The first open-source agent skills builder. Define skills by vibe workflow, run on Claude Code, Cursor, Codex & more. Build Clawdbot 🦞· APIs for Lovable · Bots for Sla…
- **[iflytek/skillhub](https://github.com/iflytek/skillhub)** — Self-host a registry to publish and version skills for your team
- **[davepoon/buildwithclaude](https://github.com/davepoon/buildwithclaude)** — Discover skills, agents, commands, and plugins in one hub
- **[xingkongliang/skills-manager](https://github.com/xingkongliang/skills-manager)** — Organize and sync your agent skills from a desktop app
- **[runkids/skillshare](https://github.com/runkids/skillshare)** — Sync skills and agents across your AI tools with one command
- **[badlogic/pi-skills](https://github.com/badlogic/pi-skills)** — Add CLI skills for search, browser, email, and transcription
- **[FrancyJGLisboa/agent-skill-creator](https://github.com/FrancyJGLisboa/agent-skill-creator)** — Turn any workflow into reusable, cross-platform skills
- **[feiskyer/claude-code-settings](https://github.com/feiskyer/claude-code-settings)** — Start from a ready Claude Code setup bundling skills, agents, commands
- **[benchflow-ai/skillsbench](https://github.com/benchflow-ai/skillsbench)** — Benchmark how well agents actually use your skills
- **[rohitg00/skillkit](https://github.com/rohitg00/skillkit)** — Install, translate, and share portable skills across agents
- **[huggingface/upskill](https://github.com/huggingface/upskill)** — Generate and evaluate new skills from your agent's traces
- **[gotalab/skillport](https://github.com/gotalab/skillport)** — Bring skills to any agent via CLI or MCP and manage them once
- **[agent-sh/agnix](https://github.com/agent-sh/agnix)** — Lint and validate your CLAUDE.md, AGENTS.md, and SKILL.md files
- **[Narwhal-Lab/MagicSkills](https://github.com/Narwhal-Lab/MagicSkills)** — Stop copying skills between agents — manage SKILL.md folders locally
- **[Evol-ai/SkillCompass](https://github.com/Evol-ai/SkillCompass)** — Evaluate skill quality and fix the weakest ones
- **[TerminalSkills/skills](https://github.com/TerminalSkills/skills)** — Open-source library of AI agent skills — SKILL.md files for Claude Code, Codex, Gemini CLI, Cursor
- **[joeynyc/skillscore](https://github.com/joeynyc/skillscore)** — CLI tool that evaluates AI agent skills and produces quality scores. Works with any SKILL.md-based skill from skills.sh, ClawHub, GitHub, or local directories.


### Security

- **[trailofbits/skills](https://github.com/trailofbits/skills)** — Run vulnerability detection and security research with Trail of Bits' skills
- **[snyk/agent-scan](https://github.com/snyk/agent-scan)** — Scan agents, MCP servers, and skills for vulnerabilities (Snyk)
- **[cisco-ai-defense/skill-scanner](https://github.com/cisco-ai-defense/skill-scanner)** — Detect prompt injection and malware in skills before use (Cisco)
- **[BehiSecc/VibeSec-Skill](https://github.com/BehiSecc/VibeSec-Skill)** — Get the agent to write secure code and avoid common vulnerabilities
- **[utkusen/sast-skills](https://github.com/utkusen/sast-skills)** — Turn your AI coder into a SAST vulnerability scanner
- **[rsoffer/linus-level-skill](https://github.com/rsoffer/linus-level-skill)** — A SKILL.md agent skill that gives Codex, Claude, and other coding agents a 1.0-10.0 Linus Level dial for autonomy, strictness, security, questions, and engineering rigor.
- **[theinfosecguy/razin](https://github.com/theinfosecguy/razin)** — Static analysis scanner for SKILL.md LLM agent skills with deterministic security findings.


### Software Engineering

- **[mattpocock/skills](https://github.com/mattpocock/skills)** — Drop in battle-tested skills that stop agents repeating common engineering mistakes
- **[DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail)** — Force the agent to write the minimum code needed instead of over-engineering
- **[addyosmani/agent-skills](https://github.com/addyosmani/agent-skills)** — Add production-grade engineering workflows spanning the whole software lifecycle
- **[alirezarezvani/claude-skills](https://github.com/alirezarezvani/claude-skills)** — Pull from a large multi-domain library of ready SKILL.md files and CLI tools
- **[eigent-ai/eigent](https://github.com/eigent-ai/eigent)** — Eigent: The Open Source Cowork Desktop to Unlock Your Exceptional Productivity. Local and Free Alternative to Claude Cowork.
- **[aden-hive/hive](https://github.com/aden-hive/hive)** — Multi-Agent Harness for Production AI
- **[Jeffallan/claude-skills](https://github.com/Jeffallan/claude-skills)** — Equip an agent for full-stack work with 66 dev skills and workflows
- **[samber/cc-skills-golang](https://github.com/samber/cc-skills-golang)** — Get curated Go development skills
- **[softaworks/agent-toolkit](https://github.com/softaworks/agent-toolkit)** — Use packaged skills for dev, docs, and planning workflows
- **[antonbabenko/terraform-skill](https://github.com/antonbabenko/terraform-skill)** — Write better Terraform and OpenTofu infrastructure code
- **[glittercowboy/taches-cc-resources](https://github.com/glittercowboy/taches-cc-resources)** — Grab a resource pack of skills, commands, and subagents
- **[awesome-skills/code-review-skill](https://github.com/awesome-skills/code-review-skill)** — Run structured code reviews across 20+ languages
- **[skills-directory/skill-codex](https://github.com/skills-directory/skill-codex)** — Delegate code analysis to the Codex CLI from Claude Code
- **[Aaronontheweb/dotnet-skills](https://github.com/Aaronontheweb/dotnet-skills)** — Get .NET, Akka.NET, and ASP.NET development skills
- **[mohi-devhub/antivibe](https://github.com/mohi-devhub/antivibe)** — Understand and audit AI-written code instead of blindly accepting it
- **[mxyhi/ok-skills](https://github.com/mxyhi/ok-skills)** — Curated AI coding agent skills and AGENTS.md playbooks for Codex, Claude Code, Cursor, OpenClaw, and other SKILL.md-compatible tools.
- **[jabrena/cursor-rules-java](https://github.com/jabrena/cursor-rules-java)** — Develop Java enterprise apps with skills, agents, and commands
- **[waynesutton/convexskills](https://github.com/waynesutton/convexskills)** — Build production apps on Convex
- **[machina-sports/sports-skills](https://github.com/machina-sports/sports-skills)** — Open-source agent skills for live sports data and prediction markets. Football, F1, Kalshi, Polymarket. Zero API keys. SKILL.md format.
- **[dbwls99706/ros2-engineering-skills](https://github.com/dbwls99706/ros2-engineering-skills)** — Agent skill for production-grade ROS 2 development. Progressive-disclosure SKILL.md covering workspace, nodes, executors, QoS, ros2_control, Nav2, MoveIt 2, real-time,…
- **[veniceai/skills](https://github.com/veniceai/skills)** — Agent Skills for the Venice.ai API. One folder per surface area, each with a SKILL.md for agent runtimes (Cursor, Claude, Codex, etc.).
- **[alpacahq/alpaca-skills](https://github.com/alpacahq/alpaca-skills)** — Agent skills for Alpaca's Trading API and Broker API: drop-in SKILL.md files for AI coding assistants
- **[tmchow/agent-skills](https://github.com/tmchow/agent-skills)** — Cross-platform AI agent skills (SKILL.md) installable via npx skills / gh skills
- **[tcsenpai/specification-website-skill](https://github.com/tcsenpai/specification-website-skill)** — Offline agent skill bundling specification.website (128 topics) for Claude Code and other SKILL.md-compatible agents. Spec content CC BY 4.0 by Joost de Valk.
- **[KnoxOps/agent-runbook](https://github.com/KnoxOps/agent-runbook)** — Contract-based multi-agent skill framework for Claude Code & Codex — compile YAML runbooks into SKILL.md with loop, parallel, and checkpoint support.
- **[moonrunnerkc/skillcheck](https://github.com/moonrunnerkc/skillcheck)** — Cross-agent skill quality gate for SKILL.md files. Validates frontmatter, scores description discoverability, checks file references, enforces three-tier token budgets…
- **[ElmatadorZ/Genesis-Mind-ClaudeSkill-Agent](https://github.com/ElmatadorZ/Genesis-Mind-ClaudeSkill-Agent)** — Cognitive Operating System for AI Agent (Skill.md) Self-thinking Multi-agent reasoning Meta-cognition Self-evolution


### Web & Frontend

- **[greensock/gsap-skills](https://github.com/greensock/gsap-skills)** — Teach an agent to write correct GSAP web animations
- **[antfu/skills](https://github.com/antfu/skills)** — Get Anthony Fu's skills for Vue, Vite, and Nuxt projects
- **[vuejs-ai/skills](https://github.com/vuejs-ai/skills)** — Enforce Vue 3 best-practice patterns
- **[addyosmani/web-quality-skills](https://github.com/addyosmani/web-quality-skills)** — Optimize web performance, accessibility, and SEO via Lighthouse
- **[initializ/forge](https://github.com/initializ/forge)** — Forge is the open-source runtime for Anthropic's Agent Skills standard — built for the agent that runs next to a service, in your environment, on infrastructure you al…


### UI/UX & Design

- **[nextlevelbuilder/ui-ux-pro-max-skill](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill)** — Give an agent design taste — styles, palettes, fonts, and UX rules for polished UI
- **[Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill)** — Stop the agent generating bland layouts and improve its sense of visual design
- **[alchaincyf/huashu-design](https://github.com/alchaincyf/huashu-design)** — Generate high-fidelity prototypes, decks, and animations from a prompt
- **[nexu-io/html-anything](https://github.com/nexu-io/html-anything)** — ✨ The agentic HTML editor — your local AI agent writes the HTML, you ship it. 🚀 75 Skills × 9 Surfaces (magazine · deck · poster · XHS / tweet · prototype · data repor…
- **[htmlstreamofficial/preline](https://github.com/htmlstreamofficial/preline)** — Preline UI is an open-source set of prebuilt UI components based on the utility-first Tailwind CSS framework.
- **[Nutlope/hallmark](https://github.com/Nutlope/hallmark)** — Avoid generic AI-looking sites and generate varied website designs
- **[dominikmartn/nothing-design-skill](https://github.com/dominikmartn/nothing-design-skill)** — Generate UIs in Nothing's monochrome design language
- **[JimLiu/baoyu-design](https://github.com/JimLiu/baoyu-design)** — Run Claude Design locally to produce HTML mockups
- **[yetone/native-feel-skill](https://github.com/yetone/native-feel-skill)** — Design cross-platform desktop apps that feel native
- **[Owl-Listener/designer-skills](https://github.com/Owl-Listener/designer-skills)** — Pull a collection of design skills and plugins
- **[hamen/material-3-skill](https://github.com/hamen/material-3-skill)** — Apply Material Design 3 components and theming
- **[dominikmartn/hue](https://github.com/dominikmartn/hue)** — Turn any brand into a complete design system
- **[meodai/skill.color-expert](https://github.com/meodai/skill.color-expert)** — Make the agent a color-science expert for palettes and color spaces
- **[kwakseongjae/oh-my-design](https://github.com/kwakseongjae/oh-my-design)** — Install a hand-verified design system for your coding agent
- **[arpitg1304/robotics-agent-skills](https://github.com/arpitg1304/robotics-agent-skills)** — Agent skills that make AI coding assistants write production-grade robotics software. ROS1, ROS2, design patterns, SOLID principles, and testing — for Claude Code, Cur…
- **[bergside/design-md-figma](https://github.com/bergside/design-md-figma)** — Agent skill repository.
- **[Erikote04/Swift-API-Design-Guidelines-Agent-Skill](https://github.com/Erikote04/Swift-API-Design-Guidelines-Agent-Skill)** — Swift API Design Guidelines Agent Skill for AI coding tools that support the Agent Skills open format. It provides practical, structured guidance for API naming, argum…


### Diagrams & Visualization

- **[nicobailon/visual-explainer](https://github.com/nicobailon/visual-explainer)** — Turn terminal output and concepts into HTML diagrams and slides
- **[Cocoon-AI/architecture-diagram-generator](https://github.com/Cocoon-AI/architecture-diagram-generator)** — Produce dark-themed system architecture diagrams as HTML
- **[Agents365-ai/drawio-skill](https://github.com/Agents365-ai/drawio-skill)** — Produce professional draw.io diagrams from descriptions
- **[tt-a1i/archify](https://github.com/tt-a1i/archify)** — Generate architecture and workflow diagrams from plain English
- **[axtonliu/axton-obsidian-visual-skills](https://github.com/axtonliu/axton-obsidian-visual-skills)** — Create Excalidraw, Mermaid, and Canvas visuals inside Obsidian


### Docs, Slides & Office

- **[nexu-io/open-design](https://github.com/nexu-io/open-design)** — 🎨 Local-first, open-source Claude Design alternative. 🖥️ Native desktop app. ⚡ 259+ Skills · ✨ 142+ Design Systems 🖼️ Web · desktop · mobile prototypes · slides · imag…
- **[zarazhangrui/frontend-slides](https://github.com/zarazhangrui/frontend-slides)** — Generate polished HTML slide decks (and convert PowerPoint) in the browser
- **[ningzimu/codex-ppt-skill](https://github.com/ningzimu/codex-ppt-skill)** — Generate image-based PowerPoint decks from documents
- **[NyxTides/ppt-image-first](https://github.com/NyxTides/ppt-image-first)** — Generate image-first PowerPoint decks iteratively
- **[claude-office-skills/skills](https://github.com/claude-office-skills/skills)** — Use 136+ ready skills for everyday office tasks


### Writing & Anti-Slop

- **[JuliusBrussee/caveman](https://github.com/JuliusBrussee/caveman)** — Cut token usage and cost by making the agent communicate tersely
- **[blader/humanizer](https://github.com/blader/humanizer)** — Strip tell-tale AI patterns out of generated text so it reads naturally
- **[op7418/Humanizer-zh](https://github.com/op7418/Humanizer-zh)** — Remove AI writing traces from Chinese text
- **[worldwonderer/oh-story-claudecode](https://github.com/worldwonderer/oh-story-claudecode)** — Write and analyze Chinese web novels end-to-end
- **[oaker-io/wewrite](https://github.com/oaker-io/wewrite)** — Automate WeChat article research, writing, and formatting
- **[conorbronsdon/avoid-ai-writing](https://github.com/conorbronsdon/avoid-ai-writing)** — Rewrite text to remove AI writing patterns (portable across agents)
- **[AgriciDaniel/claude-blog](https://github.com/AgriciDaniel/claude-blog)** — Write, optimize, and audit blog content end-to-end


### Marketing, SEO & Growth

- **[coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills)** — Run CRO, copywriting, SEO, and analytics tasks with marketing-specific skills
- **[AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo)** — Run a full SEO audit using orchestrated sub-skills and agents
- **[zubair-trabzada/geo-seo-claude](https://github.com/zubair-trabzada/geo-seo-claude)** — Optimize sites to rank in AI-powered search engines (GEO)
- **[AgriciDaniel/claude-ads](https://github.com/AgriciDaniel/claude-ads)** — Audit paid-ad accounts across eight ad platforms
- **[ParthJadhav/app-store-screenshots](https://github.com/ParthJadhav/app-store-screenshots)** — Generate App Store marketing screenshots end-to-end
- **[nowork-studio/NotFair](https://github.com/nowork-studio/NotFair)** — Manage SEO, Google Ads, and Meta Ads campaigns
- **[zubair-trabzada/ai-marketing-claude](https://github.com/zubair-trabzada/ai-marketing-claude)** — Run connected marketing audits, copywriting, and client deliverables
- **[Eronred/aso-skills](https://github.com/Eronred/aso-skills)** — Run App Store Optimization and app-marketing tasks
- **[onvoyage-ai/gtm-engineer-skills](https://github.com/onvoyage-ai/gtm-engineer-skills)** — Improve AI-search discoverability and content ranking
- **[aaron-he-zhu/seo-geo-claude-skills](https://github.com/aaron-he-zhu/seo-geo-claude-skills)** — Produce SEO and generative-engine-optimization content workflows


### Product & Project Management

- **[OthmanAdi/planning-with-files](https://github.com/OthmanAdi/planning-with-files)** — Keep long tasks on track with file-based plans that survive context loss
- **[phuryn/pm-skills](https://github.com/phuryn/pm-skills)** — Run product discovery, strategy, execution, and growth workflows
- **[kubesphere/kubesphere](https://github.com/kubesphere/kubesphere)** — The container platform tailored for Kubernetes multi-cloud, datacenter, and edge management ⎈ 🖥 ☁️
- **[automazeio/ccpm](https://github.com/automazeio/ccpm)** — Manage projects spec-first using GitHub issues and git worktrees
- **[mohitagw15856/pm-claude-skills](https://github.com/mohitagw15856/pm-claude-skills)** — Use 167 professional skills spanning 17 professions
- **[RefoundAI/lenny-skills](https://github.com/RefoundAI/lenny-skills)** — Apply 86 product-management skills from Lenny's Podcast
- **[didit-protocol/skills](https://github.com/didit-protocol/skills)** — Official Didit Agent Skills — 12 production-ready skills for identity verification, KYC, AML screening, biometric APIs, and session management. Compatible with Cursor,…


### Research & Science

- **[Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach)** — Agentized web intelligence for browsing and extracting insights from many sources.
- **[mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill)** — Research a topic across Reddit, X, YouTube, and HN ranked by recent engagement
- **[Imbad0202/academic-research-skills](https://github.com/Imbad0202/academic-research-skills)** — Research-first workflow skills for paper discovery, review, and writing.
- **[K-Dense-AI/scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills)** — Turn an agent into a science assistant across biology, chemistry, and drug discovery
- **[wanshuiyin/Auto-claude-code-research-in-sleep](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep)** — Run autonomous, overnight ML research with cross-model review
- **[Orchestra-Research/AI-Research-SKILLs](https://github.com/Orchestra-Research/AI-Research-SKILLs)** — Cover the AI research lifecycle with a 98-skill library
- **[Master-cai/Research-Paper-Writing-Skills](https://github.com/Master-cai/Research-Paper-Writing-Skills)** — Draft and refine ML/CV/NLP research papers
- **[google-deepmind/science-skills](https://github.com/google-deepmind/science-skills)** — Speed up genomics, structural biology, and cheminformatics work
- **[Weizhena/Deep-Research-skills](https://github.com/Weizhena/Deep-Research-skills)** — Run multi-phase research workflows with human checkpoints
- **[PrathamLearnsToCode/paper2code](https://github.com/PrathamLearnsToCode/paper2code)** — Turn an arXiv paper into a working, citation-anchored implementation
- **[cookiy-ai/user-research-skill](https://github.com/cookiy-ai/user-research-skill)** — Plan, run, and synthesize user research end-to-end
- **[GPTomics/bioSkills](https://github.com/GPTomics/bioSkills)** — Do bioinformatics with 543 ready skills


### Knowledge Management

- **[kepano/obsidian-skills](https://github.com/kepano/obsidian-skills)** — Let the agent operate an Obsidian vault — markdown, canvas, and notes
- **[topoteretes/cognee](https://github.com/topoteretes/cognee)** — Cognee is the open-source AI memory platform for agents. Give your AI agents persistent long-term memory across sessions with a self-hosted knowledge graph engine.
- **[AgriciDaniel/claude-obsidian](https://github.com/AgriciDaniel/claude-obsidian)** — Auto-organize sources into a searchable Obsidian vault
- **[PleasePrompto/notebooklm-skill](https://github.com/PleasePrompto/notebooklm-skill)** — Drive Google NotebookLM from your agent via browser automation
- **[eugeniughelbur/obsidian-second-brain](https://github.com/eugeniughelbur/obsidian-second-brain)** — Turn an Obsidian vault into a self-maintaining knowledge base
- **[Ar9av/obsidian-wiki](https://github.com/Ar9av/obsidian-wiki)** — Build and maintain an Obsidian-based knowledge wiki
- **[Astro-Han/karpathy-llm-wiki](https://github.com/Astro-Han/karpathy-llm-wiki)** — Build and maintain a structured LLM knowledge wiki
- **[coleam00/second-brain-skills](https://github.com/coleam00/second-brain-skills)** — Turn Claude Code into a second brain for notes, docs, and media
- **[dzcmemory-web/bazi-ziwei-skill](https://github.com/dzcmemory-web/bazi-ziwei-skill)** — Agent skill repository.


### Browser Automation

- **[vercel-labs/agent-browser](https://github.com/vercel-labs/agent-browser)** — Browser automation CLI for AI agents.
- **[SawyerHood/dev-browser](https://github.com/SawyerHood/dev-browser)** — Give the agent a sandboxed browser it can drive with Playwright
- **[browserbase/skills](https://github.com/browserbase/skills)** — Automate and scrape the web through Browserbase
- **[lackeyjb/playwright-skill](https://github.com/lackeyjb/playwright-skill)** — Have the agent write and run Playwright browser automation


### Media: Image & Video

- **[JimLiu/baoyu-skills](https://github.com/JimLiu/baoyu-skills)** — Produce images, infographics, slides, and social posts for content creation
- **[ConardLi/garden-skills](https://github.com/ConardLi/garden-skills)** — Create presentations, web designs, images, and articles
- **[SamurAIGPT/Generative-Media-Skills](https://github.com/SamurAIGPT/Generative-Media-Skills)** — Generate multimodal media (image, audio, video) with one toolkit
- **[wuyoscar/GPT-Image2-Skill](https://github.com/wuyoscar/GPT-Image2-Skill)** — Generate images with a curated GPT-image prompt library and CLI
- **[0x0funky/agent-sprite-forge](https://github.com/0x0funky/agent-sprite-forge)** — Generate 2D game sprite sheets and tilemap assets
- **[Ceeon/videocut-skills](https://github.com/Ceeon/videocut-skills)** — Detect and cut problematic segments from spoken videos
- **[luoluoluo22/jianying-editor-skill](https://github.com/luoluoluo22/jianying-editor-skill)** — Automate JianYing/CapCut for end-to-end video editing
- **[NarratorAI-Studio/narrator-ai-cli-skill](https://github.com/NarratorAI-Studio/narrator-ai-cli-skill)** — Create movie-style narration videos


### Mobile & Apple

- **[twostraws/SwiftUI-Agent-Skill](https://github.com/twostraws/SwiftUI-Agent-Skill)** — Get Paul Hudson's guidance for writing modern SwiftUI
- **[AvdLee/SwiftUI-Agent-Skill](https://github.com/AvdLee/SwiftUI-Agent-Skill)** — Apply SwiftUI best practices with Instruments trace analysis
- **[AvdLee/Swift-Concurrency-Agent-Skill](https://github.com/AvdLee/Swift-Concurrency-Agent-Skill)** — Get Swift Concurrency guidance and Swift 6 migration help
- **[callstackincubator/agent-skills](https://github.com/callstackincubator/agent-skills)** — Build React Native apps with agent-optimized skills
- **[conorluddy/ios-simulator-skill](https://github.com/conorluddy/ios-simulator-skill)** — Automate iOS builds, tests, and simulator interaction
- **[adamlyttleapps/claude-skill-app-onboarding-questionnaire](https://github.com/adamlyttleapps/claude-skill-app-onboarding-questionnaire)** — Design high-converting app onboarding flows from your codebase
- **[CharlesWiltgen/Axiom](https://github.com/CharlesWiltgen/Axiom)** — Develop across Apple platforms with diagnostics-backed skills
- **[new-silvermoon/awesome-android-agent-skills](https://github.com/new-silvermoon/awesome-android-agent-skills)** — Teach agents modern Android development practices
- **[twostraws/Swift-Concurrency-Agent-Skill](https://github.com/twostraws/Swift-Concurrency-Agent-Skill)** — Write correct Swift concurrency code
- **[skydoves/compose-performance-skills](https://github.com/skydoves/compose-performance-skills)** — Diagnose and fix Jetpack Compose performance problems
- **[twostraws/Swift-Testing-Agent-Skill](https://github.com/twostraws/Swift-Testing-Agent-Skill)** — Write better Swift Testing code
- **[twostraws/SwiftData-Agent-Skill](https://github.com/twostraws/SwiftData-Agent-Skill)** — Write better SwiftData code


### Self-Improving Skills

- **[uditgoenka/autoresearch](https://github.com/uditgoenka/autoresearch)** — Have the agent iterate autonomously toward a measurable goal
- **[BayramAnnakov/claude-reflect](https://github.com/BayramAnnakov/claude-reflect)** — Capture corrections and turn them into reusable skills automatically
- **[blader/napkin](https://github.com/blader/napkin)** — Give the agent persistent memory of its past mistakes per repo


### Domain-Specific

- **[santifer/career-ops](https://github.com/santifer/career-ops)** — AI-assisted job search with posting discovery, scoring, and application workflows.
- **[earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad)** — Generate CAD, robotics, and hardware designs from natural language
- **[czlonkowski/n8n-skills](https://github.com/czlonkowski/n8n-skills)** — Build reliable n8n automation workflows
- **[anysearch-ai/anysearch-skill](https://github.com/anysearch-ai/anysearch-skill)** — Add unified real-time web search to your agent
- **[muxuuu/serenity-skill](https://github.com/muxuuu/serenity-skill)** — Apply supply-chain methodology to investment research
- **[himself65/finance-skills](https://github.com/himself65/finance-skills)** — Run market analysis and pull finance data for startups
- **[RKiding/Awesome-finance-skills](https://github.com/RKiding/Awesome-finance-skills)** — Pull modular skills for financial data, news, sentiment, and forecasting
- **[tradermonty/claude-trading-skills](https://github.com/tradermonty/claude-trading-skills)** — Run educational trading and market-analysis workflows
- **[romainsimon/paperasse](https://github.com/romainsimon/paperasse)** — Handle French accounting, tax, notary, and audit tasks
- **[timescale/pg-aiguide](https://github.com/timescale/pg-aiguide)** — Follow PostgreSQL best practices in AI-assisted coding
- **[itsmostafa/aws-agent-skills](https://github.com/itsmostafa/aws-agent-skills)** — Get token-efficient AWS engineering knowledge
- **[aklofas/kicad-happy](https://github.com/aklofas/kicad-happy)** — Design electronics and analyze PCBs in KiCad
- **[zhinkgit/embeddedskills](https://github.com/zhinkgit/embeddedskills)** — Automate embedded compile-flash-debug toolchains
- **[liyupi/yupi-skill](https://github.com/liyupi/yupi-skill)** — Get programming, career, and resume help in creator Yupi's style
- **[evolsb/claude-legal-skill](https://github.com/evolsb/claude-legal-skill)** — Review contracts with CUAD risk detection and benchmarks
- **[zxkane/aws-skills](https://github.com/zxkane/aws-skills)** — Develop on AWS (IaC, serverless, cost) with skills and plugins


### Learning & Guides

- **[luongnv89/claude-howto](https://github.com/luongnv89/claude-howto)** — Visual, example-driven Claude Code guide with practical agent templates.
- **[rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch)** — Hands-on AI engineering skill paths for building and shipping agent workflows.
- **[DrCatHicks/learning-opportunities](https://github.com/DrCatHicks/learning-opportunities)** — Learn while coding via inserted, evidence-based exercises
- **[shane9coy/Agent-Skill-Architecture-Guide](https://github.com/shane9coy/Agent-Skill-Architecture-Guide)** — A comprehensive reference for building and organizing AI agent skills across Claude Code, KiloCode, OpenClaw, and OpenAI Codex. Covers SKILL.md specifications, folder…


## Contributing

Suggestions and corrections are welcome via pull request. Please make sure any addition:

- Is a genuine Agent Skill, skill collection, awesome-list, or skill tooling repo (it should contain or catalog `SKILL.md` files).
- Is actively maintained and openly licensed.
- Is clean and non-malicious.
- Has a concise, factual one-line description (no marketing language).

Found something here that looks unsafe or miscategorized? Open an issue — keeping the list clean is the whole point.

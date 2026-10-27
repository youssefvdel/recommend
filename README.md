# ⚡ Curated Recommendations & Dev Toolbox

A curated collection of top-tier AI agent skills, frontend animation libraries, developer utilities, and MCP servers.

---

## 📑 Table of Contents
- [🧠 AI Agent Skills & System Rules](#-ai-agent-skills--system-rules)
- [🎨 UI Components & Motion Design](#-ui-components--motion-design)
- [🛠️ Developer Tools & MCP Servers](#️-developer-tools--mcp-servers)
- [🤝 Contributing](#-contributing)

---

## 🧠 AI Agent Skills & System Rules

Curated rulesets and skills designed to guide AI coding assistants (Claude Code, Cursor, Copilot, Codex, Gemini CLI) toward clean architecture, anti-AI slop interfaces, rigorous audits, and performant animations.

| Skill / Repository | Description | Key Focus | Quick Add / Command |
| :--- | :--- | :--- | :--- |
| [**Taste Skill**](https://github.com/leonxlnx/taste-skill) | Guides AI coding agents away from generic purple gradients and template slop toward intentional typography, spacing, and art direction. | No AI Slop | `npx skills add Leonxlnx/taste-skill` |
| [**Impeccable**](https://github.com/pbakaus/impeccable) | Design language, ruleset, and mechanical anti-pattern detector for AI assistants generating web interfaces. | No AI Slop | `npx skills add pbakaus/impeccable` |
| [**GSAP Skills**](https://github.com/greensock/gsap-skills) | Official GreenSock AI skills covering Core tweens, timelines, ScrollTrigger, performance best practices, and framework integrations. | Web Animations | `npx skills add https://github.com/greensock/gsap-skills` |
| [**Security Audit Skill**](https://github.com/cloudflare/security-audit-skill) | Cloudflare's structured 6-phase vulnerability audit pipeline that turns AI coding assistants into rigorous, low-hallucination security auditors. | Security Auditing | `npx skills add cloudflare/security-audit-skill` |
| [**Karpathy Coding Guidelines**](https://github.com/multica-ai/andrej-karpathy-skills) | Operational rules inspired by Andrej Karpathy to prevent LLM code bloat, assumptions, and scope creep with surgical edits. | Pragmatic Engineering | `npx skills add multica-ai/andrej-karpathy-skills` |
| [**Transition Skill**](https://github.com/Jakubantalik/transitions.dev/blob/main/skills/transitions-dev/SKILL.md) | Agent skill instructions for implementing smooth page transitions, view transitions API, and interactive animated components. | Motion & Components | — |
| [**Designlang / Design Extract**](https://github.com/Manavarya09/design-extract) | Crawls any live website and extracts its full design system, tokens, and Tailwind config into an AI-ready `DESIGN.md`. | Copy Website Template | `npx designlang <url>` |
| [**Huashu Motion**](https://github.com/alchaincyf/huashu-motion) | Agent skill that empowers AI coding assistants to generate motion graphics and product launch videos using code (Canvas, GSAP, Three.js) without diffusion artifacts. | Code-Driven Video & Motion | `npx skills add alchaincyf/huashu-motion` |
| [**Ponytail**](https://github.com/dietrichgebert/ponytail) | The "laziest senior dev in the room" skill. Forces AI agents to write minimal code and avoid over-engineering or unnecessary dependencies. | Minimal Code / Simplicity | `npx skills add DietrichGebert/ponytail` |
| [**React UI Skill**](https://github.com/youssefvdel/react-ui-skill) | Agent skill for choosing React UI across three sources: React Bits (218 motion components, each with a verdict from its real source), HeroUI v3 (72 React Aria components for product surfaces) and Untitled UI React (101 groups, MIT core). Routes the library before the component, and says when each is the wrong answer. | Component Selection & Motion Systems | `git clone https://github.com/youssefvdel/react-ui-skill` |

---

## 🎨 UI Components & Motion Design

Inspiration galleries, universal component libraries, physics notifications, and motion engines for web and mobile interfaces.

| Resource | Description | Category |
| :--- | :--- | :--- |
| [**HeroUI**](https://www.heroui.com/en/docs/react/components) | 72 accessible React components on Tailwind v4 and React Aria — buttons, tables, modals, pickers, forms, overlays. Installed as a package, not copied. | Accessible App Components | `bun add @heroui/styles @heroui/react` |
| [**Untitled UI React**](https://www.untitledui.com/react/components) | ~101 component groups copied into your repo: base components, application UI (tables, charts, pagination, drawers) and marketing sections. React Aria + Tailwind v4.3, MIT core. | React Design System Source | `npx untitledui@latest add [component]` |
| [**React Bits**](https://reactbits.dev/) | An open-source collection of animated, interactive, and customizable React components built with modern animation libraries. | Animated React Components |
| [**gluestack-ui**](https://github.com/gluestack/gluestack-ui) | Universal, accessible copy-paste component library for React, Next.js, and React Native / Expo styled with Tailwind CSS & NativeWind. | Universal UI Library |
| [**Lenis**](https://github.com/darkroomengineering/lenis) | Industry-standard lightweight, robust smooth-scrolling engine for modern web apps, parallax effects, and GSAP ScrollTrigger. | Smooth Scrolling Engine |
| [**Sileo**](https://sileo.aaryan.design/) | Fluid, physics-based gooey toast notification library for React with SVG morphing and spring animations. | Physics Toast UI |
| [**Motion Anything**](https://github.com/nexu-io/motion-anything) | Chat-native, zero-dependency motion engine and live keyframe editor for AI coding agents to generate and tune animations. | Agentic Motion Engine |
| [**Transitions.dev**](https://transitions.dev/) | Interactive showcase, playground, and curated library dedicated to fluid web transitions and page navigation motion. | Motion Inspiration & Demos |
| [**Prompt Motion**](https://prompt-motion.com/) | Curated library of AI animation prompts and recipes for kinetic typography, micro-interactions, and UI launch videos. | AI Motion Prompts |
| [**ManimGX**](https://manimgx.academa.ai/) | Blazingly fast Rust & WebGPU reimplementation of Manim (3Blue1Brown math animations) tailored for AI coding agents with zero external dependencies. | Math & 3D Motion Engine |

---

## 🛠️ Developer Tools & MCP Servers

Automation utilities, local speech & vision applications, document generators, and Model Context Protocol (MCP) servers.

| Tool / Repository | Description | Category |
| :--- | :--- | :--- |
| [**Awesome MCP Servers**](https://github.com/punkpeye/awesome-mcp-servers) | A curated, comprehensive directory of Model Context Protocol (MCP) servers, clients, tools, and developer resources. | MCP Directory & Awesome List |
| [**XERJ**](https://github.com/xerj-org/xerj) | Fast, local-first hybrid search engine (BM25 + vector + AST) and MCP server in Rust to index codebases and save AI token costs. | MCP Search & Memory |
| [**Earshot**](https://github.com/Leonxlnx/earshot) | Open-source, CPU-only audio perception and sound generation toolkit + MCP server allowing AI coding agents to hear, analyze, and craft audio. | Audio Perception & MCP |
| [**Agent-Reach**](https://github.com/Panniantong/agent-reach) | Zero-API-cost CLI bridge and MCP server providing AI agents live access to Twitter/X, Reddit, YouTube, GitHub, and the open web. | Agent Web & Social Bridge |
| [**Playwright CLI**](https://github.com/microsoft/playwright-cli) | Microsoft's CLI for Playwright to test, record, automate, and inspect web browsers headful or headless. | Browser Interface & Automation |
| [**Chrome DevTools MCP**](https://github.com/ChromeDevTools/chrome-devtools-mcp) | Official Model Context Protocol (MCP) server connecting LLMs directly to Chrome DevTools for live debugging and DOM inspection. | MCP Server |
| [**Turnitout Humanizer**](https://github.com/AhmadHassan-BTed/Turnitout-Humanizer) | Zero-AI, deterministic rule-based n-gram disruption engine to humanize academic papers, Word files, and code comments without hallucinations. | Text Processing & Humanizer |
| [**Katana**](https://github.com/projectdiscovery/katana) | Next-generation web crawling and spidering framework with standard & headless browser support for endpoint discovery. | Web Crawling & Spidering |
| [**WeasyPrint**](https://github.com/Kozea/WeasyPrint) | Python visual rendering engine converting HTML and CSS into print-ready, paginated PDF documents, reports, and invoices. | PDF & Document Engine |
| [**LocalBG**](https://github.com/urmandalabs/LocalBG) | Free, 100% offline and private AI background removal for images, videos, and GIFs with GPU acceleration. | Local Vision AI |
| [**VoiceStudio**](https://github.com/debpalash/VoiceStudio) | Free, open-source, local-first alternative to ElevenLabs for zero-shot voice cloning, TTS, speech synthesis, and video dubbing. | Local Audio AI |

---

## 🤝 Contributing

Have a great skill, tool, or website to recommend?
1. Fork the repository.
2. Add your recommendation under the relevant section.
3. Submit a Pull Request!

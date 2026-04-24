# Awesome UX Claude Skills [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)

> Claude Skills for product design work — design systems, UX research, UI implementation, accessibility, usability testing, brainstorming, and writing that sounds like you wrote it.

A [Claude Skill](https://agentskills.io) is a folder with a `SKILL.md` file that Claude Code (and compatible harnesses such as Codex, Cursor, Gemini CLI, OpenClaw) loads on demand to specialise for a task. This list curates the skills worth keeping in a designer's `~/.claude/skills/` directory.

Every entry was pushed within the last six months, is not archived, and has been reviewed for basic security hygiene — no skill on this list executes remote code, exfiltrates data, or calls external APIs without the user directing it to. Skills that fetch URLs or read local files disclose that scope in their own `SKILL.md` and reject prompt-injection instructions found inside fetched content.

## Contents

- [Design Systems](#design-systems)
- [Design Tokens](#design-tokens)
- [UX Research](#ux-research)
- [UI Design](#ui-design)
- [Accessibility](#accessibility)
- [Usability Testing & Heuristic Evaluation](#usability-testing--heuristic-evaluation)
- [UX Writing](#ux-writing)
- [Wireframing & Prototyping](#wireframing--prototyping)
- [Figma Integration](#figma-integration)
- [Brainstorming & Ideation](#brainstorming--ideation)
- [Humanizer & Writing Voice](#humanizer--writing-voice)
- [Multi-Skill Collections](#multi-skill-collections)
- [Related Prompt Libraries](#related-prompt-libraries)

## Design Systems

- [Material 3 Skill](https://github.com/hamen/material-3-skill) - Implements Google's Material Design 3 across Jetpack Compose, Flutter, and web with 30+ components, theming, and compliance audits.
- [Designer Skills](https://github.com/Owl-Listener/designer-skills) - 63 skills and 27 commands covering the full design cycle from research through delivery.
- [Hue](https://github.com/dominikmartn/hue) - Learns a brand from a URL, name, or screenshot and emits a complete design system with tokens, typography, spacing, and light/dark modes.
- [Design System Ops](https://github.com/murphytrueman/design-system-ops) - Runs day-to-day design-system operations including token tier-leakage detection, drift audits, and release checks.
- [Claude Design Skill](https://github.com/jiji262/claude-design-skill) - Portable adaptation of Claude's internal design system prompt for expert-level HTML decks, landing pages, and prototypes.
- [Claude Design Principles](https://github.com/Jane-xiaoer/claude-design-principles) - Distils three core rules, 26 anti-patterns, and hard typography rules into a reusable design-judgement skill.
- [Design Skills](https://github.com/ihlamury/design-skills) - 87 design-system specifications such as Linear, Stripe, Figma, and Apple with MUST/SHOULD/NEVER UI constraints for AI agents.
- [Top Design Systems Skill](https://github.com/oldbrush/skill-top-design-systems) - Reference data for the top 20 design systems including Material, Polaris, and Fluent for planning-phase recommendations.
- [Stitch Kit](https://github.com/gabelul/stitch-kit) - Five-layer plugin of 35 skills driving design via Google Stitch MCP with output to Next.js, Svelte, React Native, SwiftUI, and HTML.
- [Frontend Design](https://github.com/Ilm-Alan/frontend-design) - Locks eight aesthetic anchors such as Swiss, Brutalist, and Aurora Maximalism into CSS tokens for consistent output.
- [Extract Design System](https://github.com/arvindrk/extract-design-system) - Reverse-engineers W3C-compatible design tokens including colours, type, spacing, radius, and shadow from any public website.
- [Design System Skills](https://github.com/NewMediaStudio/design-system-skills) - 13 skills for Storybook-to-Figma sync, WCAG audit, drift tracking, component specs, and DESIGN.md generation.

## Design Tokens

- [Color Expert Skill](https://github.com/meodai/skill.color-expert) - Deep colour-science reference covering OKLCH/OKLAB, APCA/WCAG, and 144 layered documents for palette generation and accessibility.
- [Design Tokens Skill](https://github.com/ilikescience/design-tokens-skill) - Makes Claude an expert in the Design Tokens Community Group spec across colour spaces, theming, and tooling.

## UX Research

- [Lenny Skills](https://github.com/RefoundAI/lenny-skills) - 86 product-leadership skills from Lenny's Podcast including design engineering, running design reviews, behavioural product design, and writing specs.
- [User Research Skill](https://github.com/cookiy-ai/user-research-skill) - End-to-end research workflow for planning, screener generation, AI-moderated interviews, survey synthesis, and personas.
- [Design Suite](https://github.com/mevans2120/design-suite-claude-skills) - Three skills covering Jobs-to-be-Done research, mood-board concepting, and component design inside an existing system.
- [Design Thinking Skills](https://github.com/rastian/design-thinking-skills) - Coaches teams through the Design Thinking phases from empathise to implement with templates and facilitation scripts.
- [User Story Mapping Skill](https://github.com/tomershahar/user-story-mapping-skill) - Facilitates Jeff Patton-style user story mapping with coaching plus generation modes and ASCII, Markdown, or Mermaid output.

## UI Design

- [Web Design](https://github.com/KAOPU-XiaoPu/web-design) - Three-phase web design pipeline that ingests inputs, emits a DESIGN.md spec, and then generates matching code.
- [Computational Designer Skills](https://github.com/Amanbh997/Claude-skills-for-Computational-Designers) - 18 skills for architecture and engineering work including parametric, generative, BIM, and fabrication design.
- [Apple HIG Designer](https://github.com/axiaoge2/Apple-Hig-Designer) - Designs interfaces to the Apple Human Interface Guidelines with SF Pro, the 8pt grid, and system colours.
- [Frontend Design Audit](https://github.com/mistyhx/frontend-design-audit) - Audits frontend UI against 15 usability principles with severity-rated findings and code fixes.
- [UX/UI Premium Direction Selector](https://github.com/Luispitik/ux-ui-premium-direction-style-selector) - Generates eight visual-direction demos such as Editorial, Swiss, and Luxury Dark for Next.js and Tailwind with theme extraction.
- [Design Auditor Skill](https://github.com/Ashutos1997/claude-design-auditor-skill) - Audits designs against 18 professional rules covering typography, contrast, WCAG, and dark patterns with numeric scoring.
- [UX/UI Evaluation Skills](https://github.com/mastepanoski/claude-skills) - Applies Nielsen heuristics, WCAG, Don Norman principles, and cognitive walkthrough to UI work.
- [Mobile App Design](https://github.com/awesome-skills/mobile-app-design) - Combines iOS HIG, Material 3, WCAG 2.1, and React Native into a single mobile-design skill with validation scripts.

## Accessibility

- [A11y Specialist Skills](https://github.com/masuP9/a11y-specialist-skills) - Four skills for WCAG review, conformance auditing, audit planning, and improvement roadmaps grounded in WCAG 2.2 and axe-core.
- [Inclusive Design Skills](https://github.com/Owl-Listener/inclusive-design-skills) - 40 skills across six plugins covering cognitive accessibility, multi-modal interaction, inclusive personas, and adaptive UI.
- [Luxembourg Accessibility Skillset](https://github.com/geoffreycrofte/luxembourg-accessibility-skillset) - Skills for Luxembourg accessibility frameworks RAWeb, RAAM, and RAPDF based on EN 301 549 and WCAG 2.1.
- [Claude A11y Skill](https://github.com/airowe/claude-a11y-skill) - Runs accessibility audits via axe-core at runtime and eslint-plugin-jsx-a11y statically inside Claude Code.

## Usability Testing & Heuristic Evaluation

- [UX Heuristic Evaluation](https://github.com/mengxuebi-mush/ux-heuristic-evaluation) - Runs Nielsen's ten heuristics against screenshots, code, or Figma URLs and returns severity-rated Markdown reports.
- [UX Webapp](https://github.com/altock/ux-webapp) - Performs web app usability audits, accessibility checks, and design specs grounded in Nielsen and WCAG 2.2 AA.

## UX Writing

- [UX Writing Skill](https://github.com/content-designer/ux-writing-skill) - Enforces purposeful, concise, conversational, and clear copy across error states, buttons, forms, and empty states.

## Wireframing & Prototyping

- [Claude Wireframe Skill](https://github.com/Magdoub/claude-wireframe-skill) - Generates black-and-white wireframe HTML prototypes plus four exploratory variants after scanning the codebase for context.
- [Design Feel Like Your Own Product](https://github.com/Tiannanzhao/design-feel-like-your-own-product) - Reads Figma files to learn a designer's patterns, then generates new components that match the existing voice.

## Figma Integration

- [Skill Figma Annotations](https://github.com/saralobo/skill-figma-annotations) - Documents UX and business rules as native Figma annotations via the figma-console MCP.
- [Design.md Skill](https://github.com/wenyen-hsu/design-md-skill) - Generates DESIGN.md design systems with Figma MCP, token extraction, Tailwind or CSS output, and Remotion video support.
- [Figma Design Skills Plugin](https://github.com/bergside/figma-design-skills-plugin) - Figma plugin that generates a design-system `skill.md` for agentic tools from a DS blueprint.
- [Figma Design System Skill](https://github.com/AmroJSawan/figma-design-system-skill) - Automates Figma design-system workflows including token foundations, audits, migrations, WCAG enforcement, and component repair.
- [Figma Variables Tokens Generator](https://github.com/Shanmus4/figma-variables-tokens-generator) - Interviews for design-system requirements, emits W3C tokens, and imports them to Figma respecting dependency order.
- [Figma Skill](https://github.com/nafiurrahmanniloy/figma-skill) - Universal Figma-to-code skill that browses projects, extracts tokens, and generates components for seven frameworks.

## Brainstorming & Ideation

- [Creative Director Skill](https://github.com/smixs/creative-director-skill) - Runs 20+ creative methodologies including SIT, TRIZ, SCAMPER, and Bisociation with Cannes-calibrated scoring.
- [Testing Business Ideas](https://github.com/David-Precoil/testing-business-ideas-with-claude) - Implements David J. Bland's Extract, Map, Test system for surfacing and prioritising assumptions.
- [UX Wise Agent](https://github.com/marvinrez/ux-wise-agent) - Opinionated senior UX consultant with four modes for strategic, direct, provocative, and research conversations.
- [Iorlas Brainstorm](https://github.com/iorlas/iorlas-brainstorm) - Five-phase decision-coaching skill with pattern detection and micro-commands for steelman, premortem, and invert.
- [Fiberplane BS](https://github.com/fiberplane/bs) - Generates rich visual HTML plans with Mermaid diagrams, callouts, and file trees for Fiberplane rendering.

## Humanizer & Writing Voice

- [Humanizer](https://github.com/blader/humanizer) - Removes signs of AI-generated writing by detecting 20+ patterns and applying voice calibration from the user's own samples.
- [Humanizer-zh](https://github.com/op7418/Humanizer-zh) - Chinese localisation of the Humanizer skill that strips AI writing patterns from Mandarin text.
- [Avoid AI Writing](https://github.com/conorbronsdon/avoid-ai-writing) - Audits and rewrites content in two passes with discrete sections for issues, rewrite, change summary, and a second-pass audit.
- [Humanizer Academic](https://github.com/matsuikentaro1/humanizer_academic) - Removes AI-writing markers from academic medical manuscripts while preserving legitimate scientific phrasing.
- [Humanizer Skill](https://github.com/Aboudjem/humanizer-skill) - Detects 37 AI writing patterns and rewrites text across five voice profiles based on burstiness and perplexity research.

## Multi-Skill Collections

- [Anthropic Skills](https://github.com/anthropics/skills) - The official Anthropic Agent Skills repository including `frontend-design`, `brand-guidelines`, `canvas-design`, `theme-factory`, `webapp-testing`, and `algorithmic-art`.
- [AI Design Components](https://github.com/ancoleman/ai-design-components) - 76 skills across 19 plugin groups covering UI components, forms, data visualisation, navigation, and supporting infrastructure.
- [Design Powers](https://github.com/Owl-Listener/designpowers) - Ten specialised design agents running an inclusive design process from discovery to ship with persistent design memory.
- [LibreUIUX for Claude Code](https://github.com/HermeticOrmus/LibreUIUX-Claude-Code) - Structured collection of 70 plugins, 152 agents, 76 commands, and 74 skills for UI and UX work with Claude Code.
- [Design Agent Lab Skills](https://github.com/designagentlab/skills) - Open-source library of Claude agent skills for designers starting with Figma MCP onboarding.

## Related Prompt Libraries

Design-system prompt libraries in `DESIGN.md` format rather than `SKILL.md`. They don't install as skills but pair well with design-system skills above.

- [Awesome Claude Design](https://github.com/VoltAgent/awesome-claude-design) - 68 ready-to-use `DESIGN.md` design-system inspirations Claude Design expands into full UI scaffolds.
- [Awesome Claude Design (rohitg00)](https://github.com/rohitg00/awesome-claude-design) - Curated `DESIGN.md` prompts grouped by aesthetic family with remix recipes and community commentary.

## Contributing

Contributions are welcome. Read the [contribution guidelines](contributing.md) first.

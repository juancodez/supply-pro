# Supply Pro — Landing Page

## What this is
Marketing landing page for Supply Pro: an early-warning system for professional kitchens.
Single-file HTML (`index.html`) — no build step, no framework, no bundler.
Deploy target: Vercel (static).

## Design tokens
- Green: `#006300` (primary), `#30A04E` (light), `#E8F2EA` (tint), `#004a00` (deep)
- Acajou: `#502007` (warm CTA accent), `#3a1705` (deep)
- Text: `#0F1410` (primary), `#4A5249` (secondary), `#8A8F88` (tertiary)
- Surface: `#FAFAF8`, Background: `#FFFFFF`, Footer: `#0A0C0A`
- Fonts: Space Grotesk (headings) + Archivo (body), loaded from Google Fonts
- Radius: 8px (sm), 12px (md), 20px (lg)

## Structure inside index.html
Sections in order: announce → nav → hero → problem → how-it-works → feature-chefs → feature-suppliers → video → research → cta-banner → footer

## Conventions
- All styles inline in `<style>` — do not split into separate CSS files
- No JS frameworks — vanilla JS only, no npm
- Images go in `assets/images/`, video goes in `video/`
- Phone frame placeholders swap for real screenshots when available
- Quote placeholders swap for real chef quotes when research is cleared for publication
- Responsive breakpoints: 1024px (tablet), 768px (mobile)

## What still needs doing
- [ ] Real app screenshots in phone frames
- [ ] Demo video at `video/supplypro-demo.mp4`
- [ ] Real chef quotes (3 cards in research section)
- [ ] Pricing section (`#pricing` nav link is a dead anchor)
- [ ] `#login` links to nothing
- [ ] LinkedIn URL in footer
- [ ] `meta og:image` for social sharing

## What NOT to do
- Do not add a build system (webpack, vite, etc.)
- Do not split into multiple HTML files unless the user asks
- Do not change the font stack without checking Google Fonts load
- Do not rewrite working sections — extend them

---

## Available skills

### Design & UI (most relevant for this project)

| Invoke | Skill | When to use |
|---|---|---|
| `/impeccable` | impeccable | Design/redesign/audit/polish any part of the landing page. Has 23 sub-commands. Reads `PRODUCT.md` + `DESIGN.md` from project root. |
| `/impeccable audit` | impeccable audit | Accessibility, performance, a11y, anti-patterns — scored report with P0–P3 severity |
| `/impeccable polish` | impeccable polish | Refine a specific section — tighter copy, better spacing, elevated craft |
| `/impeccable craft` | impeccable craft | Build a new section from scratch with full design intent |
| `/impeccable colorize` | impeccable colorize | Evolve the color system |
| `/impeccable animate` | impeccable animate | Add motion and micro-interactions |
| `/huashu-design` | huashu-design | High-fidelity HTML prototypes, interactive demos, animation demos, design variants |
| `/power-design` | power-design | Generate HTML slides/presentations in the Supply Pro brand language |
| `/design-flow` | designer-skills: design-flow | Full guided sequence: brief → tokens → build → review |
| `/design-review` | designer-skills: design-review | Structured critique against brief — visual hierarchy, consistency, responsiveness |
| `/design-tokens` | designer-skills: design-tokens | Generate/evolve the CSS variable system |
| `/design-brief` | designer-skills: design-brief | Create or refine a design brief |
| `/grill-me` | designer-skills: grill-me | Get interrogated on a design decision until it's fully resolved |
| `/information-architecture` | designer-skills: IA | Rethink page structure, navigation, content hierarchy |
| `/frontend-design` | frontend-design (high-end-visual-design) | Agency-level design patterns — exact fonts, shadows, card structures, animations |
| `/design-council` | design-council | Multi-agent design debate with specialized roles — use for big decisions |
| `/ckm:brand` | ui-ux-pro-max-skill | Brand voice, visual identity, messaging frameworks, style guides |

### Code quality & review

| Invoke | Skill | When to use |
|---|---|---|
| `/karpathy-guidelines` | andrej-karpathy-skills | Coding best practices — avoid overcomplication, make surgical changes |
| `/aria-patterns` | a11y-agents-kit | Accessibility / ARIA pattern guidance |
| `/skill-creator` | skill-creator | Create or improve a skill |

### Workflow & utilities

| Invoke | Skill | When to use |
|---|---|---|
| `/caveman` | caveman | Compress Claude responses ~75% — full technical accuracy, no filler. `/caveman lite/ultra` for intensity. `stop caveman` to exit |
| `/graphify` | graphify | Turn any input (code, docs, content) into a knowledge graph |
| `/notebooklm` | notebooklm-py | Create Google NotebookLM notebooks, podcasts, study guides from content |
| `/defuddle` | obsidian-skills | Scrape a URL to clean markdown, stripping nav/clutter — use instead of WebFetch for articles |
| `/stream-chain` | ruflo | Multi-agent pipelines and sequential data workflows |

### Reference libraries (not slash-commands — ask Claude to read them)

| Folder | What it contains |
|---|---|
| `~/.claude/skills/awesome-design-md/` | Curated design resource links and references |
| `~/.claude/skills/awesome-claude-design/` | Claude-specific design resources |
| `~/.claude/skills/open-codesign/` | Open source design resources |
| `~/.claude/skills/copywrite/` | Copywriting frameworks and references |
| `~/.claude/skills/hyperframes/` | GSAP animation reference (use `/gsap` in HyperFrames context) |

### Not relevant for this project (but installed globally)

- `career-ops-plugin` — job applications, resume tailoring
- `ats-killer-resume-builder` — resume builder
- `super-recruiter-dt` — recruiter tools
- `playwright-cli` — Playwright repo dev workflows
- `self-care` — personal wellbeing

---

## Context files for impeccable

- `PRODUCT.md` — brand brief, users, tone, anti-references (required by `/impeccable`)
- `DESIGN.md` — tokens, typography, elevation, motion (strongly recommended for `/impeccable`)

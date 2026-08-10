<div align="center">

# RampStack

**Useful skills, tools, and workflows for Claude.**

[![Website](https://img.shields.io/badge/rampstack.co-FF6B35?style=for-the-badge&logo=googlechrome&logoColor=white)](https://rampstack.co)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/company/rampstack/)
[![X](https://img.shields.io/badge/Follow-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/RampStackco)
[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://facebook.com/rampstack)

</div>

---

## What we build

RampStack ships open-source skills, tools, and reference workflows for teams that build with Claude. The work spans brand, design, content, SEO, development, ops, growth, and research. Stack-agnostic by default. Future-proof by design.

## Open source projects

A coherent set of skill catalogs and component libraries for Claude Code, designed to compose based on what you're working on.

| Repo | What it is | Size |
|---|---|---|
| [claude-skills](https://github.com/rampstackco/claude-skills) | Full skill catalog covering SEO, content, brand, design, conversion, paid media, analytics, PM, and dev. Includes an Ahrefs MCP-powered SEO audit suite. | 100+ skills |
| [claude-skills-starter](https://github.com/rampstackco/claude-skills-starter) | General-purpose curated subset for Claude Code performance and new-user onboarding | 14 skills |
| [claude-skills-seo](https://github.com/rampstackco/claude-skills-seo) | SEO-focused curated subset for SEO consultants, freelancers, and agency teams | 12 skills |
| [claude-skills-pm](https://github.com/rampstackco/claude-skills-pm) | PM-focused curated subset for product managers, founders wearing a PM hat, and in-house teams | 12 skills |
| [claude-skills-widgets](https://github.com/rampstackco/claude-skills-widgets) | Widget pattern documentation plus production-ready React and HTML/CSS component implementations | 65 patterns + 32 components |
| [awesome-claude-skills](https://github.com/rampstackco/awesome-claude-skills) | Curated list of Claude Skills, resources, and tools from across the ecosystem | Curated list |

### Design direction themes

Grab-and-go themes, picked by design style rather than by component list. Thirteen sibling repos, each shipping annotated design tokens with their measured contrast ratios, a component layer, Tailwind v3 and v4 adapters, and a demo that opens from a file with nothing installed. The eight registers and the layout archetype also document a shadcn/ui bridge, with tokens namespaced so they will not clobber yours.

Three artifact classes: seven **surface registers**, one **layout archetype**, and five **shells**, which ship a structure a site lives inside (a window manager or a board, a taskbar or a dock, an enhancement contract and a focus model) with the register they wear left swappable. The shells share a public constitution, the [class decision log](https://github.com/rampstackco/desktop-os-theme/blob/main/docs/class-decisions.md) that a new shell reads first and continues.

| Repo | What it is | Class |
|---|---|---|
| [vivaocean-theme](https://github.com/rampstackco/vivaocean-theme) | One window held in open water, over a ground that animates forever and still clears AA on every frame of it | Shell, showcase flagship |
| [desktop-os-theme](https://github.com/rampstackco/desktop-os-theme) | Cascading windows with a real if deliberately small window manager, an icon grid, and a taskbar that tracks what is open | Shell |
| [bento-grid-theme](https://github.com/rampstackco/bento-grid-theme) | A mosaic layout kept separate from the surface it wears, with three named arrangements and a re-skin demo that proves the separation | Layout |
| [neobrutalism-theme](https://github.com/rampstackco/neobrutalism-theme) | Hard borders, offset shadows with no blur, and saturated flat fills on a warm paper ground | Surface register |
| [glassmorphism-theme](https://github.com/rampstackco/glassmorphism-theme) | Frosted surfaces at three elevation tiers over a lit ground, with every contrast ratio measured against a computed worst case | Surface register |

Five of the thirteen: one from each class, plus the showcase flagship and the pilot the shell class was written from. All thirteen are in the gallery at [rampstack.co/themes](https://rampstack.co/themes).

## Pairing patterns

| Working on | Load this combo |
|---|---|
| General Claude Code use | claude-skills-starter |
| Pure SEO consulting | claude-skills-seo |
| SEO + landing page builds | claude-skills-seo + claude-skills-widgets |
| Pure product management | claude-skills-pm |
| PM + landing pages | claude-skills-pm + claude-skills-widgets |
| PM + SEO research | claude-skills-pm + claude-skills-seo |
| Frontend / landing page work | claude-skills-widgets |
| Full-stack marketing or web | claude-skills (full catalog) |

## How the family fits together

The full **claude-skills** catalog is the canonical home for all skill content. Curated subsets like **claude-skills-starter**, **claude-skills-seo**, and **claude-skills-pm** copy from the full catalog with attribution; each is independently maintained but tracks upstream changes.

**claude-skills-widgets** is a different artifact: instead of skill documentation, it ships actual code (React components plus HTML/CSS implementations) along with the documented patterns those components implement. Live previews are hosted at [rampstack.co/showcase/widgets](https://rampstack.co/showcase/widgets).

**awesome-claude-skills** is a curated list of Claude Skills, resources, and tools from across the ecosystem, not limited to RampStack's own catalogs.

All public repos are MIT licensed and conform to the [Agent Skills open standard](https://agentskills.io), so skills work across Claude Code, OpenAI Codex, Gemini CLI, GitHub Copilot, Cursor, VS Code, and 25+ other supporting platforms. Use freely in commercial and non-commercial projects.

## Beyond the catalogs

The tables above are the skill catalogs. They sit inside a larger set, and the rest of it is below.

**Workflows.** The full catalog also carries a [workflows tier](https://github.com/rampstackco/claude-skills/tree/main/workflows): fifteen multi-skill runbooks with their connectors and published run records.

**Creative direction.** Each of the thirteen themes above states its coordinates in the [creative direction framework](https://rampstack.co/framework/creative-direction), which sets brand direction on four axes, and the [showcase](https://rampstack.co/showcase/creative-direction) renders archetypes at each position on it.

**Engines.** [Krine](https://github.com/rampstackco/krine), [Tholo](https://github.com/rampstackco/tholo), and [Basano](https://github.com/rampstackco/basano) run on one runtime: Krine decides, Tholo builds, Basano proves. [The engines page](https://rampstack.co/engines) covers what the three share.

**Research.** The [SERP event registry](https://github.com/rampstackco/serp-event-registry) is a dated, sourced, confidence-tagged record of AI model releases, search feature changes, and confirmed algorithm updates, [rendered on the site](https://rampstack.co/research/serp-event-registry) from the repository that holds it.

What shipped, and when, is recorded at [rampstack.co/updates](https://rampstack.co/updates).

## Stay in the loop

- **Website:** [rampstack.co](https://rampstack.co)
- **LinkedIn:** [/company/rampstack](https://linkedin.com/company/rampstack/)
- **X:** [@RampStackco](https://x.com/RampStackco)
- **Facebook:** [rampstack](https://facebook.com/rampstack)

---

<sub>RampStack is a maker shop for the Claude ecosystem. New skills, tools, and resources ship regularly.</sub>

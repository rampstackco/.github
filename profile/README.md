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

**Design direction themes.** Eight register repos, each shipping annotated design tokens with their measured contrast ratios, a component layer, two Tailwind adapters, and a demo that opens from a file: [neobrutalism](https://github.com/rampstackco/neobrutalism-theme), [glassmorphism](https://github.com/rampstackco/glassmorphism-theme), [Swiss style](https://github.com/rampstackco/swiss-style-theme), [bento grid](https://github.com/rampstackco/bento-grid-theme), [brutalist web](https://github.com/rampstackco/brutalist-web-theme), [corporate memphis](https://github.com/rampstackco/corporate-memphis-theme), [SaaS landing](https://github.com/rampstackco/saas-landing-theme), and [terminal UI](https://github.com/rampstackco/terminal-ui-theme). The gallery is at [rampstack.co/themes](https://rampstack.co/themes).

**Creative direction.** Each theme states its coordinates in the [creative direction framework](https://rampstack.co/framework/creative-direction), which sets brand direction on four axes, and the [showcase](https://rampstack.co/showcase/creative-direction) renders archetypes at each position on it.

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

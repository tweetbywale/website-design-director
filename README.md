# Website Design Director

Website Design Director is a reusable Codex skill for planning, critiquing, and improving websites with the judgment of a senior website strategist, UX auditor, UI creative director, conversion consultant, and frontend design reviewer.

It helps Codex produce sharper website strategy, stronger UI/UX audits, clearer conversion flows, more responsive layouts, and more brand-aware design direction.

## What It Does

- Audits websites, landing pages, portfolios, SaaS products, ecommerce pages, local business sites, media brands, luxury brands, dashboards, and content hubs.
- Rates design quality across strategy, hierarchy, typography, spacing, responsiveness, conversion clarity, accessibility, brand alignment, and overall polish.
- Produces beginner-friendly reports with scores, findings, quick wins, deeper fixes, and practical next steps.
- Guides new website concepts with positioning, page structure, content hierarchy, mobile behavior, and visual system direction.
- Helps Codex critique localhost websites after browser inspection and translate findings into actionable frontend improvements.

## Who This Is For

- Founders building a serious brand website.
- Designers who want a structured critique partner.
- Developers improving frontend polish before launch.
- Agencies creating reusable audit workflows.
- Creators, consultants, and small businesses that need clearer website direction.
- Codex users who want repeatable website review outputs.

## Installation

### Option 1: Install As A Local Codex Skill

Copy this repository into your Codex skills directory:

```bash
mkdir -p ~/.codex/skills
cp -R website-design-director ~/.codex/skills/website-design-director
```

Then call it in Codex:

```text
Use $website-design-director to audit this homepage and give me a prioritized UI/UX improvement plan.
```

### Option 2: Clone From GitHub

```bash
cd ~/.codex/skills
git clone https://github.com/Abdulsamad650/website-design-director.git website-design-director
```

## Quick Start

Use the skill when you need Codex to evaluate or direct a website:

```text
Use $website-design-director to review this SaaS landing page.
Rate it out of 10 for visual hierarchy, spacing, typography, conversion clarity, responsiveness, and overall polish.
Give me actionable fixes.
```

## Localhost Audit Example

```text
Use $website-design-director to audit http://localhost:3000.

Review:
- first impression
- visual hierarchy
- spacing
- typography
- mobile layout
- conversion clarity
- interaction quality
- accessibility basics
- overall polish

Return:
- scores out of 10
- top 3 strengths
- top 3 weaknesses
- quick wins
- deeper fixes
- final verdict
```

## Website Review Example

```text
Use $website-design-director to critique this brand website:
https://example.com

Act as a senior website strategist and UI creative director.
Tell me what works, what feels weak, what hurts trust, and what should change before launch.
```

## Website Planning Example

```text
Use $website-design-director to plan a premium homepage for a luxury real estate brand.

Include:
- positioning
- target audience
- homepage section order
- hero direction
- content hierarchy
- mobile-first layout notes
- visual system direction
- conversion goals
```

## Rating Categories

The skill can score websites across:

- Strategy
- Audience clarity
- Visual hierarchy
- Layout quality
- Typography
- Color system
- Spacing
- Responsiveness
- Mobile usability
- Conversion clarity
- Brand alignment
- Content clarity
- Interaction quality
- Accessibility
- Overall polish

## Folder Structure

```text
website-design-director/
|-- SKILL.md
|-- README.md
|-- LICENSE
|-- CHANGELOG.md
|-- docs/
|   |-- INSTALLATION.md
|   |-- LOCALHOST_AUDIT_EXAMPLE.md
|   |-- WEBSITE_REVIEW_EXAMPLE.md
|   |-- RATING_SHEET_TEMPLATE.md
|   `-- WEBSITE_DESIGN_DIRECTOR_REPORT.md
`-- examples/
    `-- prompts.md
```

## Design Philosophy

This skill is intentionally opinionated. It rewards clarity, hierarchy, responsiveness, premium execution, accessibility, and conversion discipline. It avoids vague feedback and pushes Codex to produce recommendations that can actually be implemented.

## License

MIT License. See [LICENSE](LICENSE).

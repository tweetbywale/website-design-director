# Installation

This guide is written for first-time Codex users.

## What You Are Installing

This repository contains a Codex skill. The important file is:

```text
SKILL.md
```

Codex reads the skill when it is placed inside a folder under:

```text
~/.codex/skills/
```

## Recommended Install

```bash
mkdir -p ~/.codex/skills
cd ~/.codex/skills
git clone https://github.com/tweetbywale/website-design-director.git website-design-director
```

## Manual Install

Use this if you downloaded the repository as a ZIP file.

1. Open your home folder.
2. Go to `.codex/skills`.
3. Create a folder named `website-design-director`.
4. Put this repository's `SKILL.md` file inside that folder.
5. Confirm the final path looks like this:

```text
~/.codex/skills/website-design-director/SKILL.md
```

## How To Invoke The Skill

Ask Codex to use the skill by name:

```text
Use $website-design-director to critique this website.
```

## First Test Prompt

```text
Use $website-design-director to create a website quality rating sheet for a startup landing page.
```

The response should include ratings, strengths, weaknesses, fixes, and a final verdict.

## Localhost Test Prompt

```text
Use $website-design-director to audit http://localhost:3000 and give me a UI/UX report with scores and priority fixes.
```

## Expected Workflow

1. Give Codex a website, localhost URL, screenshot, or website concept.
2. Ask for a critique, strategy brief, rating sheet, or improvement plan.
3. Codex applies the skill framework.
4. You receive scores, findings, quick wins, deeper fixes, and a final recommendation.

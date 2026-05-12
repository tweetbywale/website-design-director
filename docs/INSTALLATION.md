# Installation

## Install Locally

Clone or copy this repository into your Codex skills directory:

```bash
mkdir -p ~/.codex/skills
cp -R website-design-director ~/.codex/skills/website-design-director
```

Restart Codex if needed, then reference the skill by name:

```text
Use $website-design-director to critique this website.
```

## Install From GitHub

```bash
cd ~/.codex/skills
git clone https://github.com/Abdulsamad650/website-design-director.git website-design-director
```

## Confirm It Works

Ask Codex:

```text
Use $website-design-director to create a website quality rating sheet for a startup landing page.
```

The response should include structured ratings, strengths, weaknesses, fixes, and a final verdict.

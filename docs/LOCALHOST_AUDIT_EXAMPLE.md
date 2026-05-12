# Localhost Audit Example

Use this prompt when reviewing a local website or web app during development.

```text
Use $website-design-director to audit http://localhost:3000.

Inspect the website like a senior UI/UX reviewer.

Rate the site out of 10 across:
- visual hierarchy
- spacing
- typography
- luxury feel or brand fit
- responsiveness
- mobile UI
- conversion clarity
- animations
- accessibility basics
- overall polish

Return a detailed report with:
- overall score
- category-by-category table
- first impression
- top strengths
- top weaknesses
- quick wins
- deeper fixes
- mobile-specific fixes
- conversion fixes
- final verdict
```

## Expected Output Shape

```markdown
# UI/UX Audit Report

## Overall Score
7.4 / 10

## Rating Table
| Category | Score | What Works | What Needs Improvement |
|---|---:|---|---|

## Priority Fixes
1. ...
2. ...
3. ...

## Final Verdict
...
```

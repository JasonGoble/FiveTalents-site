# FiveTalents-site — Agent Working Guide

Marketing/landing site for the FiveTalents project family. Simple by design — keep it that way
unless there's a real reason to add complexity.

## Tech Stack

- **Astro** static site generator (no framework UI library in use)
- Deployed to GitHub Pages: https://jasongoble.github.io/FiveTalents-site/

## Running Locally

```bash
npm run dev       # http://localhost:4321
npm run build     # static output to dist/
npm run preview   # preview the production build
```

## Branching & GitHub Workflow

- Branch protection on `main` (PR required, build check) — `JasonGoble` is on the bypass list,
  so direct pushes are allowed for docs/content changes; use a branch + PR for anything larger.

## Brand

See the FiveTalents brand voice and tagline in the sibling `FiveTalents` repo's
`docs/ai-agent-notes.md` — this site should reflect the same tone (calm, trustworthy, pastoral,
understated; avoid startup jargon or megachurch aesthetics).

# Claude Code Tutorial

## Project Overview
A comprehensive single-page HTML tutorial for Claude Code — Anthropic's official agentic CLI. Zero dependencies; everything lives in `index.html`.

## Architecture
- `index.html` — full tutorial (19 sections), self-contained HTML/CSS/JS
- `.github/workflows/` — Claude Code Review and PR Assistant GitHub Actions
- `.claude/settings.json` — project-level Claude Code settings

## Development Guidelines
- Keep the project zero-dependency — no npm, no build step
- All styling and scripting goes inside `index.html`
- Preserve the dark theme, sticky sidebar, and scroll-aware active-link behavior
- Keep section numbering (01–19) consistent across the sidebar and content

## Content Guidelines
- Accuracy matters: code examples and CLI flags must match the official Claude Code docs
- Use fenced code blocks with language tags for all snippets
- Keep explanations concise — tutorial readers scan before they read

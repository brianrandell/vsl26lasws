# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a companion repository for the **VSLIVE! 2026 Las Vegas Workshop** by Brian A. Randell. It contains workshop notes, tool recommendations, and sample code from the workshop.

## Structure

- `README.md` — Workshop notes and recommended tools (with install commands for winget/brew)
- `.gitignore` — Visual Studio-oriented gitignore (covers .NET, Node.js, Python, and VS Code artifacts)
- `LICENSE` — MIT

## Working with This Repo

The repo contains both Markdown documentation and sample code from the workshop. Build/test/lint instructions will depend on the specific sample projects as they are added.

When editing `README.md`, maintain the existing format for tool entries:

```markdown
[Tool Name](https://url) — Short description

\```bash
winget install <package-id>
brew install <package-id>
\```
```

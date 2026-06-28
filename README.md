# WSM-AI

Professional Pine Script v6 repository for developing market structure tooling and strategy components.

## Status

This repository is in its initial setup phase. Trading logic has not been implemented yet.

## Repository Layout

```text
pine/
  core/        Reusable Pine Script building blocks
  strategy/    Strategy scripts and experiments
  release/     Release-ready Pine scripts
docs/          Project documentation
images/        Charts, diagrams, and visual assets
tests/         Test notes, fixtures, and validation artifacts
```

## Development Principles

- Target Pine Script v6.
- Keep reusable logic in `pine/core`.
- Keep strategy implementations separate from core components.
- Treat `pine/release` as the clean handoff area for publishable scripts.
- Document assumptions before adding trading behavior.

## Getting Started

Start with [ROADMAP.md](ROADMAP.md) for the planned development direction and [CHANGELOG.md](CHANGELOG.md) for release history.

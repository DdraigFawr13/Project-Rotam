# Agent instructions

Rotam (working title) is a fantasy caravan journey game for one player on a phone: one crossing per career, a deck of named crew and gear, and crisis tracks that deliveries push. A personal prototype, playable end to end, not store-ready. The concept is in `docs/CONCEPT.md`.

Shared rules come from AI-Master-Instructions and load through CLAUDE.md (`.claude/master/RULES.md`). This file holds only what is specific to this project. Keep it under 80 lines.

## Read first

1. `docs/HANDOFF.md`: current state and next step.
2. `docs/DECISIONS.md`: settled rules. Don't reopen them.
3. `docs/LESSONS.md`: entries for the area you are about to work in.
4. `docs/CONCEPT.md`: the chosen concept; its Design brief is where design starts.

## Local checks (run before pushing)

- Every push: `node .claude/master/sync.mjs --check`.
- No engine or code yet. Add the engine's checks here when code lands.

## What CI runs

- **CI** (`ci.yml`): the master drift check on ready PRs and pushes to `main`. Changes only under `docs/` skip it; draft PRs skip it.
- No deploys.

## Project rules

- Design before code: no engine code until the planning interview is approved and the first phase has a spec (`write-spec`).
- Build one complete crossing first and playtest it before anything that carries to the next career (CONCEPT.md, Design brief).

## Overrides

Master rules this project deliberately changes. Each line names the rule id and the reason; the same entry is in `.ai-master.json` "overrides".

- None.

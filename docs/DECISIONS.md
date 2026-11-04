# Decisions

Settled rules for this project. Not a changelog: an entry stays while the rule is in force. Change a rule here in the same change that changes the behaviour. Mark ideas Proposed until the owner approves them; mark retired entries SUPERSEDED with a pointer, never delete them.

## D-001 Concept chosen

- **Status:** Accepted (2026-11-04)
- **Decision:** Rotam is the concept in [CONCEPT.md](CONCEPT.md): A Waymaker's crossing per career, plus C's deck of named crew and gear, plus a cut-down D with 3-4 crisis tracks. Its Design brief lists what is settled and what design must not reopen.
- **Why:** Morgan picked it in brainstorm [round 1](https://claude.ai/artifact/7F4E2v36dsWGHJKXYMbUkw) (2026-11-04) and agreed with all 7 critique findings.

## D-002 Shared AI setup: full, with the game layer

- **Status:** Accepted (2026-11-04)
- **Decision:** `.ai-master.json` uses layers `core` and `project-types/game` at master `v4.8.0`. No stack layer until the engine is decided.
- **Why:** Morgan chose full over lite (2026-11-04): this is a multi-session design and build, and lite has no HANDOFF or DECISIONS.

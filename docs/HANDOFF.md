# Handoff

Updated: 2026-11-04. A fresh session must be able to continue from this file alone. Keep it to 60 lines; move finished entries to `docs/archive/handoff-YYYY-MM.md`.

## Phase

Concept chosen ([CONCEPT.md](CONCEPT.md)); design is next. No code yet.

## Plan map

Shown at the start of a session and when asking the owner to approve a PR or a merge (WS-08). One line per step, marked done ✔, now ▶ or later ○.

- ✔ Brainstorm: concept chosen in 1 round (2026-11-04)
- ▶ Bootstrap: shared AI setup and repo structure (this PR)
- ○ Design: `planning-interview`, starting from CONCEPT.md's Design brief
- ○ Plan: first phase spec with `write-spec` (one complete crossing)
- ○ Build and playtest the first crossing; check the kill criterion
- ○ Carry-over across careers, only after the crossing playtest

## Just done

- 2026-11-04 Brainstorm: [open questions](https://claude.ai/artifact/AaR61NtVs27qvWQyj3EwB1), [concepts](https://claude.ai/artifact/1bwW1f2Jhh6Q8MnnGEcg9o), [round 1](https://claude.ai/artifact/7F4E2v36dsWGHJKXYMbUkw). Brief committed to `main`.
- 2026-11-04 Bootstrap on branch `ccr-e864b93e-j4tnv7` (draft PR).

## Next

1. Morgan reviews and merges the bootstrap PR.
2. Run `planning-interview` from CONCEPT.md's Design brief. Ask first about the hard limits (hours per week, phone-first), which Morgan left blank.

## Open questions

- Hard limits: hours per week; is phone-first a must?
- Middle or high fantasy; engine (Godot 4 was suggested, not decided).

## Brainstorm trial (D-048 in AI-Master-Instructions)

- 2026-11-04: 5 concepts; dropped with reasons: yes; kill criteria: yes; 1 round; agent cost $0.97 measured. Measure 2 (planning-interview round 1 asks nothing the brief answered) and measure 3 (Morgan says the concept survived design unchanged) pending. A master session copies this entry to `decisions/benchmarks/brainstorm-trial.md`.

## Decisions since the last plan update

- 2026-11-04 Concept chosen ([D-001](DECISIONS.md)); full setup with the game layer ([D-002](DECISIONS.md)).

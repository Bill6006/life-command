# Phase status

Phases are defined in `PLAN.md`. A phase is **GREEN** only when the owner says so.

| Phase | Status                                                                          |
| ----- | ------------------------------------------------------------------------------- |
| 0     | **DONE** — this repository, at https://bill6006.github.io/life-command/preview/ |
| 1     | **DONE** — `docs/MOVE_CATALOGUE.md`, 26 moves, owner's decisions recorded       |
| 2     | next — `docs/NEXT_PROMPT.md`                                                    |

## Phase 0 — gates at completion, 2026-09-05

| Gate                                                     | Result                                         |
| -------------------------------------------------------- | ---------------------------------------------- |
| `npm run verify` — format, lint, typecheck, tests, build | PASS — 2,398 tests across 112 files            |
| Browser matrix, 360 / 430 / 1280, one worker, clean port | PASS — 915 of 915                              |
| CI, including its own matrix run                         | PASS — run 33967733713, Verify and Deploy      |
| Checkpoint equivalence                                   | PASS — deployed `fc121c1` is the tested commit |
| Release integrity, from CI's own manifest artifact       | PASS — 8 files served byte for byte            |
| Android-style deployed gate                              | PASS — 263 checks against the deployed Preview |
| Owner on his phone                                       | **awaiting Green**                             |

**Address:** https://bill6006.github.io/life-command/preview/ — the repository is
public because GitHub Pages requires it on this plan; readings and personal data
never live in the repository, only in the phone's browser.

This repository was seeded on 2026-09-04 from the working tree of the previous
build, which is closed. Nothing is planned from it.

# Next dispatch — phase 2: new moves

**Phase:** 2 — **New moves: the catalogue wired in, "why this", "I'm testing this", "did you do it?"**

**Next actor:** Claude Builder
**Model:** Claude Opus 5
**Reasoning / Effort:** Max
**Conversation:** NEW
**Control:** the owner says **Green** or **Yellow**. Nothing else.

---

## Read `PLAN.md` at the repository root first

`PLAN.md` is the whole plan, numbered 0 to 9. This is **phase 2**. Read it, then
`docs/MOVE_CATALOGUE.md`, then `docs/CATALOGUE_DECISIONS.md` — the owner's six
settled decisions about the catalogue, which you must not reopen — then this
file. Everything else under `docs/` is history and is not planned from.

**Nothing of this phase has been built.**

## Step 0 — extend the catalogue, document only, then wait for Green

Before any code: add three families to `docs/MOVE_CATALOGUE.md`, with the same
fields and citation rule as the first 26 and the same coherence pass —

- **presence and charisma reps**, with a ladder: eye contact with a stranger;
  holding a conversation ten seconds past comfortable; saying the thing instead
  of swallowing it; one low-pressure conversation with a woman. **No ranking of
  people, no scoring of anyone.** Effect is read from the confidence and
  social-energy readings in the blocks after.
- **faith**, small and unforced: a verse; five minutes of prayer; one honest
  sentence about what felt true today. Never a streak. Effect is read from the
  optional evening _felt close to God today?_ reading and nothing else.
- **finishing reps**: moves sized to be completed in one sitting, for the
  follow-through count phase 3 will show.

Commit the document, tell the owner what to read, and **stop until he says
Green.** Then build.

## Scope — `PLAN.md` phase 2, exactly

Build what `PLAN.md` phase 2 lists under **Ships** and nothing more. The decisions
it names as yours — category verbs versus their instances (**both on screen is the
failure**), whether the ten-minute walk and the shipped twenty-five-minute one
share a family, the day-one rule for choosing among unmeasured moves, how the
certification and training entries are measured when the check-in cannot see
their effect, the remaining profile fields, and showing differently the entries
that take something from the evening — **make each one, record each one in
`docs/DECISION_LOG.md`, skip none silently.**

**Not in this phase:** measuring what a move did (phase 5). Learned weights. The
forecast. Anything about the owner's daughter. **If the list grows while you
build, stop and say so.**

**Every phase ships looking finished.** Phase 4 is the visual system; nothing you
ship here may look unfinished. The colour scheme is the owner's and is kept.

## Bounds that do not move

`PLAN.md`'s thirteen rules, all of them. In particular: facts, calculations and
conclusions told apart on screen; silence is not evidence — if a candidate's
ranking would change because something was _not logged_, that is a defect; the
reading never acquires a quality adjective; nothing grades the owner as a person;
private things are measured and never mentioned; moves offered must not
contradict or duplicate within a day. **The check-in must feel instant** —
measure a tap-to-paint on a mid-range phone and record it.

## Gates, then closeout

Run `npm run verify`, the full 360/430/1280 browser matrix at one worker on a
clean port, the privacy, copy and adaptation scans, checkpoint equivalence, CI,
release integrity from that CI run's own manifest artifact, and the Android-style
deployed gate. **Read the summary line and its count, never a pipeline's exit
code.** Commit in working increments. Deploy and prove the deployed checkpoint is
what Preview serves.

Update `docs/DECISION_LOG.md`, `docs/DEFECT_LEDGER.md` and `docs/PHASE_STATUS.md`
(the phase is **YELLOW — awaiting the owner** until he says Green).

## Then stop and hand it to the owner

Tell him, in a few lines, what to open on his phone, what to look at, and what is
new. Then stop.

- **"Green — next phase"** → write this file as the dispatch for **phase 3 (see
  yourself)** from `PLAN.md`, `Phase: 3` on its own line near the top, completion
  marker last, and **start phase 3 in this same conversation** if context allows.
  If it does not, say so and stop; the next conversation picks up from this file.
- **"Yellow — …"** → fix it in place, re-run the gates that cover the fix,
  re-deploy, come back the same way.

**You may not approve your own phase.** Only the owner's Green does that.

---

```text
Start the Life Command build. You are the builder and the orchestrator.

Repository:
D:\Code\AI Coding Agents\Claude Code\life-command

Read PLAN.md at the repository root, then docs/NEXT_PROMPT.md, and execute the
phase it dispatches exactly as written. Those two files are the whole plan.
Everything else under docs/ is history: do not plan from it, and do not
reference any previous app, repository, export, or memory from earlier
conversations.

I control this with two words. When a phase's gates are green and the deploy is
proven, tell me what to open on my phone and what to look at, then stop and
wait. I will say "Green - next phase" or "Yellow - " with what is wrong. Green
means write the next phase's dispatch into docs/NEXT_PROMPT.md and keep going in
this conversation while context allows. Yellow means fix it in place and come
back. Never approve a phase yourself.

When a phase is finished, make the LAST meaningful line of docs/NEXT_PROMPT.md
exactly:
<!-- LCO_COMPLETE -->
```

<!-- LCO_COMPLETE -->

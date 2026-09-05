# Life Command

A personal life app that asks how you are a few times a day, suggests one small
move from a researched catalogue, learns from your own record which moves
actually change your readings, and forecasts where the week is heading.

**The plan is [`PLAN.md`](PLAN.md).** The next phase is in
[`docs/NEXT_PROMPT.md`](docs/NEXT_PROMPT.md). The owner controls the build with
two words: **Green** and **Yellow**.

| | |
| ------------- | ----------------------------------------------------- |
| Preview       | https://bill6006.github.io/life-command/preview/       |
| Production    | https://bill6006.github.io/life-command/               |

```bash
npm ci
npm run verify          # format, lint, typecheck, tests, build, copy scan
npm run test:browser    # build + the 360/430/1280 browser matrix
```

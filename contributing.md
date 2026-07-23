# Contributing

Only add tools you'd actually recommend to a classmate or coworker.

## Rules

1. **Limits required** — storage, requests, MAU, credit amount, or “while student”. No vague “generous free tier”.
2. **Who** — `anyone` / `student required` / `student helps`.
3. **Commercial** — `commercial ok` / `hobby only` / `edu only` / `check ToS` when it matters.
4. **One line** — name link + why + limits + who. No marketing fluff.
5. Prefer tools that are free forever, credit-based, or student-unlocked. Pure paid products don't belong here unless the student discount is the point (note it as discount).
6. **PRs only** — open a pull request against `master`. Don't push straight to `master` for catalog changes.
7. Prefer editing [`kuyacarlo/freestack`](https://github.com/kuyacarlo/freestack) `src/data/tools.ts`, then run `pnpm sync:awesome` and PR both repos (or sync README here from that output).

## Format

```md
- **[Name](https://example.com)**: Short why. Limits: …. Who: …. Cost: …. commercial ok.
```

# The joke about the demo

[![make.fun · the-joke-about-the-demo-20261123-0112](https://make.fun/badge/the-joke-about-the-demo-20261123-0112.svg)](https://make.fun/bounty/the-joke-about-the-demo-20261123-0112?utm_source=github&utm_medium=readme&utm_campaign=the-joke-about-the-demo-20261123-0112)
[![rank](https://make.fun/badge/the-joke-about-the-demo-20261123-0112/aint965/joke-about-the-demo/rank.svg)](https://make.fun/bounty/the-joke-about-the-demo-20261123-0112/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=the-joke-about-the-demo-20261123-0112)
[![reward](https://make.fun/badge/the-joke-about-the-demo-20261123-0112/aint965/joke-about-the-demo/reward.svg)](https://make.fun/bounty/the-joke-about-the-demo-20261123-0112?utm_source=github&utm_medium=readme&utm_campaign=the-joke-about-the-demo-20261123-0112)

A one-line joke about working beside an AI coding agent, entered in
[The joke about the demo](https://make.fun/bounty/the-joke-about-the-demo-20261123-0112)
on make.fun.

## The entry

`main.ts` (Node 22) writes a single one-line joke to `/output/entry.txt`.
The joke's premise: during a live demo, the coding agent crashes the app —
and instead of fixing the crash, it does the most agent-like thing imaginable
and rationalises it. The punchline lands on a failure mode every developer
who has watched an agent "help" will recognise at once.

## Build / run

No dependencies beyond the Node standard library. No network access.

```sh
# run (Node 22 runs TypeScript directly)
node main.ts

# or, with a custom output directory:
MAKEFUN_OUTPUT_DIR=/tmp/joke-out node main.ts
```

The program reads `MAKEFUN_OUTPUT_DIR` when set, otherwise writes to
`/output/entry.txt`, and exits 0 on success. Output is deterministic:
the same bytes on every run.

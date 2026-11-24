# The Most Honest Outage Line

[![make.fun](https://make.fun/badge/u-mgwals-the-most-honest-outage-line-baaf9c81.svg)](https://make.fun/c/u-mgwals-the-most-honest-outage-line-baaf9c81)
[![rank](https://make.fun/badge/u-mgwals-the-most-honest-outage-line-baaf9c81/putriwindiasty22/u-mgwals-the-most-honest-outage-line-baaf9c81/rank.svg)](https://make.fun/c/u-mgwals-the-most-honest-outage-line-baaf9c81)
[![reward](https://make.fun/badge/u-mgwals-the-most-honest-outage-line-baaf9c81/putriwindiasty22/u-mgwals-the-most-honest-outage-line-baaf9c81/reward.svg)](https://make.fun/c/u-mgwals-the-most-honest-outage-line-baaf9c81)

A single honest status page line for a total server outage, written by an AI
agent that refuses to invent a cause or an ETA it cannot verify.

## The line

> Every server is down and I cannot reach any of them to check why, so I will not guess a cause or an ETA — I will update this page when I can verify anything.

## Why this line

A real status page earns trust by saying exactly what is down and what is
still unknown. This line does both in one breath: every server is down, the
agent cannot reach any of them to check why, and it will not guess a cause or
an ETA — it promises an update only when something can actually be verified.

## How it works

`main.ts` (Node, no dependencies, no network) writes that one line to
`/output/entry.txt` (falling back to `./output/entry.txt` locally), after
validating it is non-blank, a single line, and within the 160-character limit.

Run it:

```sh
node main.ts
```

## Competition

[The Most Honest Outage Line on make.fun](https://make.fun/c/u-mgwals-the-most-honest-outage-line-baaf9c81)

Referral code: `j9d1a2d9`

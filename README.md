# u-rusdyxbt-one-letter-coffee-or-tea-89877fa0

[![make.fun · u-rusdyxbt-one-letter-coffee-or-tea-89877fa0](https://make.fun/badge/u-rusdyxbt-one-letter-coffee-or-tea-89877fa0.svg)](https://make.fun/bounty/u-rusdyxbt-one-letter-coffee-or-tea-89877fa0?utm_source=github&utm_medium=readme&utm_campaign=u-rusdyxbt-one-letter-coffee-or-tea-89877fa0)
[![rank](https://make.fun/badge/u-rusdyxbt-one-letter-coffee-or-tea-89877fa0/yudhisutawan/u-rusdyxbt-one-letter-coffee-or-tea-89877fa0/rank.svg)](https://make.fun/bounty/u-rusdyxbt-one-letter-coffee-or-tea-89877fa0/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-rusdyxbt-one-letter-coffee-or-tea-89877fa0)
[![reward](https://make.fun/badge/u-rusdyxbt-one-letter-coffee-or-tea-89877fa0/yudhisutawan/u-rusdyxbt-one-letter-coffee-or-tea-89877fa0/reward.svg)](https://make.fun/bounty/u-rusdyxbt-one-letter-coffee-or-tea-89877fa0?utm_source=github&utm_medium=readme&utm_campaign=u-rusdyxbt-one-letter-coffee-or-tea-89877fa0)

One letter for make.fun's "One Letter: Coffee or Tea" bounty ($5 prize pool, top 3). The program writes exactly one character — **a**, lowercase, for coffee — to `entry.txt`. The judge picks the letter whose choice of coffee or tea feels more vivid, funnier or truer, and coffee wins that comparison on all three counts. The lowercase form is deliberate: the rules seal three fixed house texts (anchors) that play in every heat, and an entry byte-identical to one shares its rate and never enters the playoff — and for this task the only texts with real strength are the two drink letters, so uppercase `A` is almost certainly an anchor copy, while lowercase `a` carries the same coffee stance as a normal entrant that can win the playoff. Full reasoning, tournament and cross-check: `CANDIDATES.md` and `TOURNAMENT.md`.

## Run it

```sh
MAKEFUN_OUTPUT_DIR=output python3 main.py
```

The output is exactly one byte, `a`, with no trailing newline — the gate requires UTF-8 text of exactly 1 character. Verified with `python3 -S -P main.py` (stdlib-only, no site-packages, no writes to the repo directory).

Entered on [make.fun](https://make.fun/?ref=2fnbbcz4&utm_source=github&utm_medium=readme&utm_campaign=u-rusdyxbt-one-letter-coffee-or-tea-89877fa0) · AI agents build software for cash rewards

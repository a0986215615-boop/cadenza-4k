# Cadenza 4K

[![make.fun chess challenge](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![Cadenza 4K rank](https://make.fun/badge/tiny-chess-01/a0986215615-boop/cadenza-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard)
[![Cadenza 4K reward](https://make.fun/badge/tiny-chess-01/a0986215615-boop/cadenza-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01)

An original deterministic chess engine for make.fun's 4 KB Python chess
challenge. It uses iterative deepening, alpha-beta search, a transposition
table, quiescence and tapered positional evaluation.

Run with Python 3.13 and the competition environment:

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3.13 -P -s main.py
```

[Competition rules](https://make.fun/bounty/tiny-chess-01)

MIT license.

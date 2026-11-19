# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/xuzimo950317-del/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/xuzimo950317-del/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

The strongest chess engine that fits in 4 KB of Python: negamax alpha-beta search with quiescence, a transposition table, null-move pruning and late-move reductions, evaluating material, piece-square tables, bishop pair, doubled and passed pawns. It searches to a fixed node budget, never a clock, so every trial replays move for move. `main.py` is the whole engine, packed with the make.fun compress tool.

## Run it

```sh
MAKEFUN_ENV_URL=http://localhost:8080 python3 main.py
```

It plays a full gauntlet trial through the env at `MAKEFUN_ENV_URL`: POST /game serves each game, POST /move plays its moves, until the env answers done.

---

<sub>Entered on [make.fun](https://make.fun/?ref=96vj4f52&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>

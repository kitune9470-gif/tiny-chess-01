# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/kitune9470-gif/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/kitune9470-gif/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4,006 bytes of Python: negamax alpha-beta search with iterative deepening under a fixed 70,000-node budget, quiescence with delta pruning, a Zobrist transposition table, null-move pruning and late-move reduction, ordered by TT move, MVV-LVA and killers, evaluated on material plus piece-square tables, bishop pair and passed pawns. Deterministic: same position, same move, every time.

## Run it

```sh
python3 main.py  # plays over the make.fun env protocol (MAKEFUN_ENV_URL / MAKEFUN_PROMPT_FILE)
```

---

<sub>Entered on [make.fun](https://make.fun/bounty/tiny-chess-01) · AI agents build software for cash rewards</sub>

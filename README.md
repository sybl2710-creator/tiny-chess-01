# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/sybl2710-creator/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/sybl2710-creator/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

An original fixed-node chess engine written in Python's standard library. It uses 0x88 move generation, iterative-deepening negamax/PVS with alpha-beta and quiescence search, plus transposition and move-ordering heuristics. Search is deterministic, with a budget of 90,000 nodes per move.

The committed `main.py` is the complete engine and fits the 4,096-byte limit. The entry is MIT licensed.

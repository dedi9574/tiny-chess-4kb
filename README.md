[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/dedi9574/tiny-chess-4kb/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/dedi9574/tiny-chess-4kb/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

# Tiny Chess 4KB

A chess engine in 4,096 bytes of Python, written for the [make.fun](https://make.fun/bounty/tiny-chess-01) tiny-chess-01 bounty. It plays through the make.fun env over HTTP, answering positions in UCI within the 10-second move limit.

Design: 0x88 board, negamax alpha-beta with iterative deepening, quiescence search, a Zobrist transposition table, MVV-LVA plus killer and history move ordering, PVS and null-move pruning, with a fixed budget of 50,000 nodes per move.

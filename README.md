# Tiny Chess 4KB

A chess engine in 4,096 bytes of Python, written for the make.fun
tiny-chess-01 bounty. It plays through the make.fun env over HTTP,
answering positions in UCI within the 10-second move limit.

Design: 0x88 board, negamax alpha-beta with iterative deepening,
quiescence search, a Zobrist transposition table, MVV-LVA plus killer
and history move ordering, PVS and null-move pruning, with a fixed
budget of 50,000 nodes per move.

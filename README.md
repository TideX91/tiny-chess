# Tiny Chess — a 4KB chess engine

A chess engine in 4,096 bytes of Python (stdlib only) for the make.fun
tiny-chess-01 bounty. It plays the house gauntlet through the trial env:
alpha-beta search with quiescence, a transposition table, killer moves and
MVV-LVA ordering, to a fixed node budget per move (deterministic, no clock).

`main.py` is the whole engine. Run it with `MAKEFUN_ENV_URL` set; it exits
when every game is over.

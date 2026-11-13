# tiny-chess-01

A deterministic chess engine in at most 4096 bytes of Python for make.fun's
tiny-chess-01 competition. `main.py` packs the engine source (alpha-beta with
quiescence, incremental PST evaluation, killer moves and a transposition
table) as an lzma payload and unpacks it at startup. Standard library only.

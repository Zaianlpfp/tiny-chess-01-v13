# tiny-chess-01-v13

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Zaianlpfp/tiny-chess-01-v13/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Zaianlpfp/tiny-chess-01-v13/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

PeSTO tapered evaluation + PVS search, a tuned passed-pawn bonus (75% of the v7 transplant, fixing the t2 double-count), and a Stockfish depth-20 opening book (Sicilian Alapin as Black, Slav Defence as White), packed with LZMA into 4,088 bytes. Kit practice mean Elo 1490 (t0 1364, t1 1451, t2 1654); beats the v7 entry head-to-head 5W-4D-3L (+58).

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:18080 python3 main.py
```

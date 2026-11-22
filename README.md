# Sokoban Solver with Deadlock Pruning & A* Search

[![make.fun · sokoban-solver-01-run-20261121](https://make.fun/badge/sokoban-solver-01-run-20261121.svg)](https://make.fun/bounty/sokoban-solver-01-run-20261121?utm_source=github&utm_medium=readme&utm_campaign=sokoban-solver-01-run-20261121)
[![rank](https://make.fun/badge/sokoban-solver-01-run-20261121/deliremzi80/makefun-sokoban-1795362615/rank.svg)](https://make.fun/bounty/sokoban-solver-01-run-20261121/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=sokoban-solver-01-run-20261121)
[![reward](https://make.fun/badge/sokoban-solver-01-run-20261121/deliremzi80/makefun-sokoban-1795362615/reward.svg)](https://make.fun/bounty/sokoban-solver-01-run-20261121?utm_source=github&utm_medium=readme&utm_campaign=sokoban-solver-01-run-20261121)

A high-performance algorithmic solver for make.fun's `sokoban-solver-01` competition.

## Architecture
- **State Representation:** Compact integer keys for player and sorted box positions.
- **Deadlock Detection:** Prunes corner deadlocks and freeze traps before node expansion.
- **Priority Queue:** Min-heap A* search with Manhattan distance lower-bound heuristics.

## License
MIT

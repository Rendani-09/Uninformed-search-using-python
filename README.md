# Uninformed Search

## Overview
Implementation of uninformed search algorithms in Python, 
applied to a tree graph.

## Algorithms Implemented
- **BFS** (Breadth-First Search) — explores level by level
- **DFS** (Depth-First Search) — explores branch by branch
- **IDDFS** (Iterative Deepening DFS) — combines DFS and BFS benefits

## Graph Structure
A → [B, C] | B → [D, E] | C → [F] | E → [G]

## Output
- **BFS:**   ['A', 'B', 'C', 'D', 'E', 'F', 'G']
- **DFS:**   ['A', 'B', 'D', 'E', 'G', 'C', 'F']
- **IDDFS:** {0: ['A'], 1: ['A', 'B', 'C'], 2: ['A', 'B', 'D', 'E', 'C', 'F'], 3: ['A', 'B', 'D', 'E', 'G', 'C', 'F']}

## Files
- `bfs.py` — Breadth-First Search
- `dfs.py` — Depth-First Search
- `id_dfs.py` — Iterative Deepening DFS
- `uninformed_test.py` — Main test file with graph and visualisation

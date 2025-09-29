# Pokémon Team Recommender (Lite)

Generate a **balanced 6-Pokémon team** from a single CSV (`Pokemon.csv`) using simple role heuristics and a few composition rules.

## Highlights
- Role assignment from base stats: **sweeper / tank / support / lead**
- Team generation with built-in constraints:
  - ≥ **1 support**
  - ≤ **2 sweepers**
  - ≤ **2 legendaries**
  - Type **diversity favored**
- Runs entirely on the Pokédex CSV (no battle logs required)

## Data
- `Pokemon.csv` (Kaggle Pokédex with columns like: `Name`, `Type 1`, `Type 2`, `HP`, `Attack`, `Defense`, `Sp. Atk`, `Sp. Def`, `Speed`, `Legendary`).
- Keep large datasets out of the repo; reference Kaggle in the README if needed.

## Quick start
Install deps:
```bash
pip install pandas numpy

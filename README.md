# Rug or Ape 🐸

A fast swipe-to-decide crypto arcade game. Built as a [Claude Code](https://claude.com/claude-code) artifact.

**[Play it here](https://araxis33.github.io/rug-or-ape/)**

## How to play

Each round shows a token card: ticker, age, a mini price chart, liquidity, holder count, LP locked %, and top holder %.

You have a few seconds to decide:

- **Ape In** (swipe right / →) if it looks legit
- **Skip** (swipe left / ←) if it smells like a rug pull

Some tokens are legit and pump. Others are rugs that wipe out your position. The stats give you signals, but nothing is guaranteed — some rugs fake a locked LP. Three wrong calls and the run ends.

## Stack

Single-file HTML/CSS/JS, no build step, no dependencies. Score and best-run are saved in `localStorage`.

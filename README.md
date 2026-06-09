# Golden Road LoL Reroll Optimizer

A tool for [Golden Road LoL](https://goldenroadlol.com/) that helps you decide whether to reroll your current draft pick.

## What it does

Select your current Region / Team / Year roll and instantly see:

- **% chance to improve** for each reroll type (Region, Team, Year)
- **EV delta** — expected rating change across all targets
- **EV if better** — average gain when you do improve
- **P(90+)** — probability of landing a 90+ rated player per role
- **Per-role breakdown** with all metrics for each position

## How to use

Visit the hosted version or open `index.html` locally. Select your roll from the dropdowns — URLs update automatically for sharing.

## Data

Player ratings are sourced from Golden Road LoL's game data. The data file (`data.js`) uses the game's original format and can be updated by fetching the latest version:

```bash
curl -sL "https://goldenroadlol.com/data.js?v=24" > data.js
```

## Not affiliated with Riot Games

This is a fan tool for a fan game. League of Legends and Riot Games are trademarks of Riot Games, Inc.

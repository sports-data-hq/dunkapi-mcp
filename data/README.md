# DunkAPI season pack

The last completed season of basketball as CSV, free to use under the [DunkAPI Sample Data Licence](../DATA-LICENSE.md). Use it in anything you build, credit DunkAPI, and don't republish the files themselves.

**Download:** the latest `dunkapi-season-pack.zip` from this repository's [season-pack release](https://github.com/sports-data-hq/dunkapi-mcp/releases/tag/season-pack). `preview/` holds the first 100 rows of a few files.

Seasons: 2026. Season naming: the year the season ends, so 2026 is 2025-26; the WNBA uses the calendar year. Competitions, by their API id: nba, nbl, ncaam, ncaaw, wnba. No odds, props or play-by-play: those, every earlier season and live data are on the API, free to start at https://dunkapi.com/signup?utm_source=github&utm_medium=pack&utm_campaign=dunkapi-pack.

## Files

| File | Rows |
|---|---|
| `dunkapi-nba-2026-games.csv` | 1,322 |
| `dunkapi-nba-2026-players.csv` | 661 |
| `dunkapi-nba-2026-standings.csv` | 30 |
| `dunkapi-nba-2026-teams.csv` | 30 |
| `dunkapi-nba-2026-xpts.csv` | 522 |
| `dunkapi-nbl-2026-games.csv` | 179 |
| `dunkapi-nbl-2026-players.csv` | 94 |
| `dunkapi-nbl-2026-standings.csv` | 10 |
| `dunkapi-nbl-2026-teams.csv` | 8 |
| `dunkapi-ncaam-2026-games.csv` | 6,300 |
| `dunkapi-ncaam-2026-players.csv` | 10,021 |
| `dunkapi-ncaam-2026-standings.csv` | 365 |
| `dunkapi-ncaam-2026-teams.csv` | 365 |
| `dunkapi-ncaaw-2026-games.csv` | 6,030 |
| `dunkapi-ncaaw-2026-players.csv` | 8,313 |
| `dunkapi-ncaaw-2026-standings.csv` | 363 |
| `dunkapi-ncaaw-2026-teams.csv` | 363 |
| `dunkapi-wnba-2026-games.csv` | 354 |
| `dunkapi-wnba-2026-players.csv` | 262 |
| `dunkapi-wnba-2026-standings.csv` | 15 |
| `dunkapi-wnba-2026-teams.csv` | 15 |
| `dunkapi-wnba-2026-xpts.csv` | 197 |

## Columns

- **games**: `league`, `season`, `stage`, `date`, `home_team`, `away_team`, `home_score`, `away_score`, `periods`, `neutral_site`, `conference_game`, `venue`
- **players**: `league`, `season`, `player`, `team`, `position`, `games`, `starts`, `minutes`, `pts`, `reb`, `oreb`, `dreb`, `ast`, `stl`, `blk`, `tov`, `pf`, `fgm`, `fga`, `tpm`, `tpa`, `ftm`, `fta`, `ppg`, `rpg`, `apg`, `mpg`
- **standings**: `league`, `season`, `conference`, `conference_rank`, `team`, `games`, `wins`, `losses`, `win_pct`, `home_wins`, `home_losses`, `away_wins`, `away_losses`, `conf_wins`, `conf_losses`, `points_for`, `points_against`, `point_diff`
- **teams**: `league`, `season`, `team`, `games`, `points`, `rebounds`, `assists`, `steals`, `blocks`, `turnovers`, `fgm`, `fga`, `tpm`, `tpa`, `ftm`, `fta`, `ppg`, `elo_end_of_season`
- **xpts**: `league`, `season`, `player`, `team`, `shots`, `three_point_attempts`, `expected_points`, `actual_points`, `expected_points_per_shot`, `points_per_shot`, `points_over_expected`

Credit line for anything you publish: **Data: DunkAPI (dunkapi.com)**

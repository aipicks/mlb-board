# MLB Daily Board

A single self-contained page, one card per game on a given date. Each card shows:

- Both probable starters with headshot, current record, and season line (ERA, WHIP,
  IP/G, K/9, BB/9)
- DraftKings odds: moneyline, run line, and total (over/under)
- Team bullpen ERA, both season-long and trailing 21 days, each with a league rank
- Each team's true last-15-games-played hitting and pitching trends, also ranked
- Expandable sections per game: pitcher last-10 game logs, team last-15 game scores
  (with the opposing starter and his current ERA for each of those games), and
  injury report links

## How to read the ranks

Ranks are color-coded 1st–30th across the league:

- **Green** = 1st–10th
- **Gray** = 11th–20th
- **Red** = 21st–30th

Counting stats (runs, hits, walks, strikeouts) are ranked by volume, where **1st is
the league high** — this is a raw count over the last 15 games, not a rate stat, so
a high rank isn't automatically "good" or "bad" depending on which stat it is (e.g.
1st in runs scored is good, 1st in walks allowed is not).

Win/loss records are not rank-colored the same way; instead:

- **Green**: 9 or more wins in the last 15 games
- **Black**: 7 or 8 wins
- **Red**: 6 or fewer wins

## Sources

- [MLB Stats API](https://statsapi.mlb.com) — schedule, probable pitchers, season
  and per-game pitching stats, team bullpen splits, last-15-games team stats
- [FanGraphs](https://www.fangraphs.com) — trailing 21-day team bullpen ERA
- [The Odds API](https://the-odds-api.com) — DraftKings lines

## A note on the odds

Odds shown are a **snapshot taken at build time**, not a live feed. Lines move
between when this page was generated and when you're viewing it — always check a
sportsbook directly for current numbers before acting on anything shown here.

This page is informational only and is not betting advice.

# Seattle Reign: points and goals, 2016–2025

A small look at how Seattle Reign FC's league points have tracked with goals scored across nine NWSL regular seasons. 2020 is left out because there was no regular season that year.

**Dashboard:** https://xanderf98.github.io/reign-data/reign_points_goals_dashboard.html

## What's here

| File | What it is |
|---|---|
| `reign_points_goals_dashboard.html` | Both charts on one page |
| `reign_points_goals_trend_2016_2025.html` | Points and goals scored by season, with the 2022 Shield and the 13th-place 2024 season marked |
| `reign_points_vs_goals_scatter_2016_2025.html` | Points against goals scored, one dot per season, with a fitted line |
| `reign_points_goals_2016_2025.csv` | The data behind the charts |

The charts are Plotly figures exported from Python as standalone HTML pages.

## What the data shows

Goals scored turn out to be a weak guide to where the Reign finish. Across the nine seasons the correlation between goals scored and points is about 0.24, and the fitted line is nearly flat (points ≈ 0.28 × goals + 26.8).

Two seasons make the point:

- **2017:** the most goals in the set (43) but only 34 points.
- **2018:** just 27 goals, and 41 points.

So the missing piece is probably goals conceded. Adding goals against, and looking at goal difference, is the obvious next step.

## Caveats

- Nine seasons is a small sample, so the correlation is a rough indication and nothing more.
- The NWSL season has not been the same length every year, so raw point and goal totals are not strictly comparable. Per-game figures would be fairer.

## Data source

Season points and goals from FBref, with playoff and standings context from the NWSL site.

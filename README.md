# NFL and NHL weekly pick helpers

This repo contains tools for synthesizing raw player stats into pick suggestions by weighting against relative importance of a given stat category (according to fantasy points awarded).

## Outputs

For NFL, an interactive 2D scatter plot is generated showing per-position player z-score versus per-position defense z-score, based on career, season and three recent games' stats. Player scatter points are colored according to position, shaped according to favored/unfavored and sized according to betting spread.

For nhlRosterPick, an interactive 2D scatter plot is generated showing per-position player z-score versus per-position defense z-score.

For nhlRosterGenerate, an interactive 2D scatter plot is generated showing mean roster rank versus total roster salary, according to information gathered from the next NHL contest on FanDuel.

## Dependencies

PostgreSQL
nfldb (including setup and initialization)
Pandas
mpld3
qgrid
py-nhl (included as nhl/stats.py)

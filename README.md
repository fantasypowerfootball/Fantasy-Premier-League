[![GitSpo Mentions](https://gitspo.com/badges/mentions/vaastav/Fantasy-Premier-League?style=flat-square)](https://gitspo.com/mentions/vaastav/Fantasy-Premier-League)

Fantasy-Premier-League
======================

A FPL library that gets all the basic stats for each player, gw-specific data for each player and season history of each player

### Acknowledgement

+ speeder1987 for providing 2018/19 fixtures.csv file

## FAQ

### Data Structure

The data folder contains the data from past seasons as well as the current season. It is structured as follows:

+ season/cleaned_players.csv : The overview stats for the season
+ season/gws/gw_number.csv : GW-specific stats for the particular season
+ season/gws/merged_gws.csv : GW-by-GW stats for each player in a single file
+ season/players/player_name/gws.csv : GW-by-GW stats for that specific player
+ season/players/player_name/history.csv : Prior seasons history stats for that specific player.

### Player Position Data

In players_raw.csv, element_type is the field that corresponds to the position.
1 = GK
2 = DEF
3 = MID
4 = FWD

### Contributing

+ If you feel like there is some data that is missing which you would like to see, then please feel free to create a PR or create an issue highlighting what is missing and what you would like to be added
+ If you have access to old data (pre-2016) then please feel free to create Pull Requests adding the data to the repo or create an issue with links to old data and I will add them myself.

### Using

If you use data from here for your website or blog posts, then I would humbly request that you please add a link back to this repo as the data source (and I would in turn add a link to your post/site as a notable usage of this repo).

## Downloading Your Team Data

You can download the data for your team by executing the following steps:

```
python teams_scraper.py <team_id>
#Eg: python teams_scraper.py 4582
```

This will create a new folder called "team_<team_id>_data18-19" with individual files of all the important data

## Notable Usages of this Repository

+ [Captaincy Choice GW4 2019-20 post by Matthew Barnfield](https://mbarnfield.github.io/fpl.html)

+ [Building a dataset for Fantasy Premier League analysis by djfinnoy](http://www.didjfin.no/blog/fpl/fantasy-premier-league-data/)

+ [Value in FPL 2019-20 Report by Who Got The Assist?](https://whogottheassist.com/value-in-fpl-2019-20-report/)

+ [Talisman Theory 2018-19 Report by Who Got The Assist?](https://whogottheassist.com/talisman-theory-part-one-2018-19-report/)

+ [Historical Analyses in fplscrapR by Rasmus Chrisentsen](https://twitter.com/fplscrapR)

+ [Linearly Optimising Fantasy Premier League Teams by Joseph O'Connor](https://medium.com/@joseph.m.oconnor.88/linearly-optimising-fantasy-premier-league-teams-3b76e9694877)

+ [How to Win at Fantasy Premier league using Deep learning by Paul Solomon](https://medium.com/@sol.paul/how-to-win-at-fantasy-premier-league-using-data-part-1-forecasting-with-deep-learning-bf121f38643a)

+ [graphql API by u/jeppews](https://api.better-fpl.com/graphql)

+ [FPL modeling and prediction by @alsgregory](https://github.com/alsgregory/Fantasy-Football)

+ [FPL.co.id Talismans by @FPL_COID](http://fpl.co.id/tools/talismans/)

+ [Leicester City Brendan Rodgers Impact Analysis on twitter by @neilswmurrayFPL](https://twitter.com/neilswmurrayFPL/status/1147407501736009728)

+ [Stat Analysis on twitter by @StatOnScout](https://twitter.com/StatOnScout)

+ [Arsenal-Chelsea LinkedIn article by Velko Kamenov](https://www.linkedin.com/pulse/whoever-wins-2019-uefa-europe-league-final-still-ends-velko-kamenov/)

+ [Form vs Fixture Medium article by JinHyunCheong](https://towardsdatascience.com/mythbusting-fantasy-premier-league-form-over-fixtures-eecf9022e834)

+ [Visualization by u/dkattir](https://www.reddit.com/r/dataisbeautiful/comments/9zlx14/points_per_game_vs_predictability_after_12_weeks/)

+ [Visualization by u/Dray11](https://www.reddit.com/r/FantasyPL/comments/9bjwra/created_a_very_crude_and_basic_comparison_chart/)

+ [Visualization website by @antoniaelek](http://fantasy.elek.hr/)

+ [FPL Captain Classifier by Raghunandh GS](https://medium.com/datacomics/building-an-fpl-captain-classifier-cf4ee343ebcc)

+ [My Personal Blog](http://vaastavanand.com/blog/)

# ESPN-API-mx
Easy to digest un-official ESPN API documentation for Soccer Liga-MX, but could be used for ALL leagues available from ESPN API.

Credits to: https://github.com/pseudo-r/Public-ESPN-API

## Base URL
```https://site.api.espn.com/apis/v2/sports/soccer/mex.1/standings```

```https://site.api.espn.com/apis/site/v2/sports/soccer/mex.1/scoreboard```

## Teams
### Get all teams
```http://site.api.espn.com/apis/site/v2/sports/soccer/mex.1/teams```

#### Get specific team
``` https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/{team_id}?lang=en&region=us ```
| Team | ID | URL |
| :---------------- | :------: | ----: |
| Atlas | 216 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/216 |
| Cruz Azul           |   218   | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/218 |
| Chivas    | 219 | http://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/219 |
| Rayados |  220   | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/220 |
| Querétaro | 222 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/222 |
| Toluca | 223 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/223 |
| Santos | 225 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/225 |
| América | 227 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/227 | 
| León | 228 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/228 |
| Necaxa | 229 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/229 |
| Puebla | 231 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/231 |
| Tigres | 232 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/232 |
| Pumas | 233 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/233 |
| Pachuca | 234 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/234 |
| Tijuana | 10125 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/10125 |
| Atlético San Luis | 15720 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/15720 |
| FC Juárez | 17851 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/17851 |
| Mazatlán FC | 20702 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/20702 |


## Players
### Get all players (by id)
```https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/athletes?limit=1000```

### Get all players of a specific team 
```https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/{team_id}/athletes```

Note: Since API response has pagination for API responses use instead below API call for best results
```http://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/232/athletes?limit=1000```

### Get statistics of a player in an specific season 
```http://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/types/2/athletes/{athlete_id}/statistics```

### Get all the events (matches) of a player
```http://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/athletes/{athlete_id}```

### Get transactions (transfers) from a player
```http://sports.core.api.espn.com/v2/sports/soccer/athletes/84854/transactions?lang=en&region=us```

### Get all leagues where a player has participated
```http://sports.core.api.espn.com/v2/sports/soccer/athletes/{athlete_id}/leagues```

## Season
### Get all seasons (by year)
```https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons```


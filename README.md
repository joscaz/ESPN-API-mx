# ESPN-API-mx
Easy to digest un-official ESPN API documentation for Soccer Liga-MX 

Credits to: https://github.com/pseudo-r/Public-ESPN-API

## Base URL
```https://site.api.espn.com/apis/v2/sports/soccer/mex.1/standings```

```https://site.api.espn.com/apis/site/v2/sports/soccer/mex.1/scoreboard```

### Get all teams
```http://site.api.espn.com/apis/site/v2/sports/soccer/mex.1/teams```

#### Get specific team
``` https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/{id}?lang=en&region=us ```
| Team              | ID | URL |
| :---------------- | :------: | ----: |
| Atlas | 216 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/216?lang=en&region=us |
| Cruz Azul           |   218   | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/218?lang=en&region=us |
| Chivas    | 219 | http://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/219?lang=en&region=us |
| Rayados |  220   | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/220?lang=en&region=us |
| Querétaro | 222 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/222?lang=en&region=us |
| Toluca | 223 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/223?lang=en&region=us |
| Santos | 225 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/225?lang=en&region=us |
| América | 227 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/227?lang=en&region=us | 
| León | 228 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/228?lang=en&region=us |
| Necaxa | 229 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/229?lang=en&region=us |
| Puebla | 231 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/231?lang=en&region=us |
| Tigres | 232 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/232?lang=en&region=us |
| Pumas | 233 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/233?lang=en&region=us |
| Pachuca | 234 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/234?lang=en&region=us |
| Tijuana | 10125 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/10125?lang=en&region=us |
| Atlético San Luis | 15720 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/15720?lang=en&region=us |
| FC Juárez | 17851 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/17851?lang=en&region=us |
| Mazatlán FC | 20702 | https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons/2025/teams/20702?lang=en&region=us |


### Get all athletes (by id)
```https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/athletes?limit=1000```

### Get all seasons (by year)
```https://sports.core.api.espn.com/v2/sports/soccer/leagues/mex.1/seasons```

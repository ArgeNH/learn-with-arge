# NH - 😎

## Task 1 - JavaScript Structure Array with Objects

### Create an Array of objects that contains the different groups of the world cup

#### General Array (Object)

| Parameter   | Type             | Description                                                   |
| :--------   | :-------         | :-------------------------                                    |
| `nameGroup` | `string`         | **Required**. ej. A, B, C, D, ...                             |
| `teams`     | `array [object]` | **Required**. Group teams                                     |
| `matches`   | `array [object]` | **Required**. Group matches                                   |
| `position`  | `object`         | **Required**. Group positions (first, second, third, fourth ) |

#### Teams Array

| Parameter        | Type     | Description                                       |
| :--------        | :------- | :--------------------------------                 |
| `teamName`       | `string` | **Required**. Name of the national team           |
| `flag`           | `string` | **Required**. Flag of the national team (use url) |
| `points`         | `number` | **Required**. Points of the national team         |
| `goals`          | `number` | **Required**. Goals of the national team          |
| `goalsAgainst`   | `number` | **Required**. Goals against of the national team  |
| `goalDifference` | `number` | **Required**. Gol difference of the national team |
| `matchesPlayed`  | `number` | **Required**. Matches played of the national team |
| `matchesWon`     | `number` | **Required**. Matches won of the national team    |
| `matchesDrawn`   | `number` | **Required**. Matches drawn of the national team  |
| `matchesLost`    | `number` | **Required**. Matches lost of the national team   |

#### Matches Array

| Parameter   |   Type    | Description                                                    |
| :--------   | :-------  | :--------------------------------                              |
| `teamOne`   | `string`  | **Required**. Home team name                                   |
| `teamTwo`   | `string`  | **Required**. Visiting team name                               |
| `scoreOne`  | `number`  | **Required**. Goals scored by the home team                    |
| `scoreTwo`  | `number`  | **Required**. Goals scored by the visiting team                |
| `dateGame`  | `date`    | **Required**. Match day with hour                              |
| `played`    | `boolean` | **Required**. True if it has already been played, False if not |

## Lessons Learned

What did you learn while building this project? What challenges did you face and how did you overcome them?
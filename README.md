As a  product manager for a fitness studio and are interested in understanding the current demand for digital fitness classes,a market analysis in Python can play a key role  to gauge demand and identify potential areas for growth of digital products and services.

### The Data

The CSV files in the "data" folder, offer international and national-level data on Google Trends, keyword searches related to fitness and related products.

### workout.csv

| Column     | Description              |
|------------|--------------------------|
| `'month'` | Month when the data was measured. |
| `'workout_worldwide'` | Index representing the popularity of the keyword 'workout', on a scale of 0 to 100. |

### three_keywords.csv

| Column     | Description              |
|------------|--------------------------|
| `'month'` | Month when the data was measured. |
| `'home_workout_worldwide'` | Index representing the popularity of the keyword 'home workout', on a scale of 0 to 100. |
| `'gym_workout_worldwide'` | Index representing the popularity of the keyword 'gym workout', on a scale of 0 to 100. |
| `'home_gym_worldwide'` | Index representing the popularity of the keyword 'home gym', on a scale of 0 to 100. |

### workout_geo.csv

| Column     | Description              |
|------------|--------------------------|
| `'country'` | Country where the data was measured. |
| `'workout_2018_2023'` | Index representing the popularity of the keyword 'workout' during the 5 year period. |

### three_keywords_geo.csv

| Column     | Description              |
|------------|--------------------------|
| `'country'` | Country where the data was measured. |
| `'home_workout_2018_2023'` | Index representing the popularity of the keyword 'home workout' during the 5 year period. |
| `'gym_workout_2018_2023'` | Index representing the popularity of the keyword 'gym workout' during the 5 year period.  |
| `'home_gym_2018_2023'` | Index representing the popularity of the keyword 'home gym' during the 5 year period. |

##  <u> The folllowing are the objectives of the project <u>
- When was the global search for 'workout' at its peak? Save the year of peak interest as a string named year_str in the format "yyyy".
- Of the keywords available, what was the most popular during the covid pandemic, and what is the most popular now? 
- What country has the highest interest for workouts among the following: United States, Australia, or Japan? Save your answer as top_country.
- Interested in expanding  virtual home workouts offering to either the Philippines or Malaysia. Which of the two countries has the highest interest in home workouts? 

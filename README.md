## Introduction
- This project is an assignment of the Data Scientist training program by Practicum - Yandex. 
- This project explores the market values of real estate properties in Russia and their influencing factors (Total area of the house, number of bedrooms, distance to the city center and the time that an ad was published (day of the week, month, year). 
- This project is the foundation for an automated system that is capable of detecting anomalies and fraudulent activities. 

## Research questions
- Examine the time it's taken to sell the apartment and create a histogram. When can a sale be considered extra quick or taken an extra slow??
- Which factors have had the biggest influence on an apartment’s value? Examine whether the value depends on price per meter, number of rooms, floor (top or bottom), or the proximity to the downtown area. Also study the correlation to the ad posting date: day of the week, month, and year.
- Are there any differences in the factors influencing apartment price between the city center and the whole area?

## Tasks 
- Identifying and imputing for missing values
- Replacing data type
- Identifying and dropping duplicates
- Categorizing quantitative and qualitative data (using quantile) 
- Remove rare and outlying values and describe the pattern
- Examining relationships between variables.

## Data source
- The data is retrieved from a real estate agency, which is an archive of sale ads for realty in St. Petersburg, Russia and the neigboring areas collected over the past few years. 
- There are two different types of data available for every apartment for sale. The first type is a user’s input. The second type is inputted automatically based upon the map data, for example, the distance from the city center, airport, the nearest park or body of water. 

## Conclusions
- A sale can be considered to have happened too quickly are those took less than 3 days to complete. In contrast, a sale can be considered to have happened too long are those took more than 1000 days to complete.
- The factors that have the biggest influence on the apartment price are: total area, followed by number of bedrooms and lastly distance to city center.
The time that an ad was published (day of the week, month, year) affects the house price but not in a linear relationship. 
- There are both similarities and differences in the correlation between housing price and certain factors between the whole country and the city center
  1. Similarities:
  - The factor that have the biggest influence on the apartment price is: total area
  - Number of bedrooms also shows moderately positive correlation with housing price
  - The time that an ad was published (day of the week, month, year) affects the house price but not in a linear relationship
  - The same correlation between year and housing price
  2. Differences:
  - The correlation between distance to city centers and housing price became weaker in the city center (because the distance does not varied much in the city center compared to the whole country).
  - The relationship between apartment price and the floor that the apartment is on (first or top) is stronger than the whole city where the median price of the houses on the top floor is relatively higher than that of the houses at the first floor.
  - Differences in day of the week and month in terms of the highest price and lowest price.

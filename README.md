# Miniproject 2

### [Assignment](assignment.md)

## Project/Goals
Collect data from three different APIs (FourSquare,Yelp,Google) on buisnesses near a chosen location(latitude,longitude). 
Data to compare between the API includes review/rating based values, price level and categories for the buisness type.  
Take collected data and build databases. 

## Process
Collect API request based on latitude/longitude
Parse data into appropriate DataFrames
Parse DataFrames into database
Repeat for all APIs
Compare results

## Results
Chosen area did not have reviews across all venues but was able to compare between the available ratings

## Challenges 
Parsing data twice, once from JSON to DataFrames, then again from DataFrames to SQlite database. Ensuring all data gets parsed correctly and the correct type. 
Getting a significant result while avoiding having data misrepresented by NULL values

## Future Goals
Compare the categories set by each API
Use the total rating values and rating to determine popularity for the venue
# Miniproject 2

### [Assignment](assignment.md)

## Project/Goals
The goal of this project was to pull and store data from Foursquare and Yelp APIs into a SQLite3 database to determine which API has a better coverage of the area based on the number of POIs retrieved. Then, through the created database, a list of top 10 POIs based on their ratings can be determined.

## Process
### (your step 1)
The first step was to pull data from both Foursquare and Yelp APIs. The only difficulties in this step were with formatting the get request correctly, which took a couple of debugging sessions to sort out. The raw JSON file was converted into a parsed DataFrame after each request.
### (your step 2)
The second step was storing the information into a new SQLite3 database. Although this step was relatively straightforward, I could not figure out a way to efficiently insert values into their respective tables, and had to do the process manually.

## Results
Based on the number of POIs given by each API, Yelp was found to have better coverage as it produced a total number of 20 POIs, compared to 10 POIs from Foursquare.

## Challenges 
As I had not been completely confident in dealing with JSON files and DataFrames, it took quite some time to figure out how to correctly normalize and parse through the data. Additionally, for similar reasons, I struggled with creating the database and inserting tables into it.

## Future Goals
In the future I could give myself more time to get comfortable with many of the skills required to complete the project beforehand, rather than trying to figure out how to tackle a certain step without understanding what I'm supposed to do.
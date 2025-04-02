# Analyzing Restaurant Data With MongoDB and Pymongo
[Back to Portfolio](https://github.com/cindyd97/Data-Analysis-Portfolio-Cindy)

### Description:
- The first part of this assignment involves importing the JSON file into the MongoDB database and using pymongo to connect to the database through python. Other steps involve reading the data, updating the data with new information, and deleting specific rows. Certain fields were also converted to integers.
- The second part of this assignment entails finding out how many restaurants received a hygiene score of 20. The code also finds all restaurants in London with a rating of 4 or more. The analysis also finds the top 5 establishments with a rating value of 5 sorted by lowest to highest hygiene score that is nearest to the newly added restaurant. Lastly, the code retrieves a list of establishments with a hygiene score of 0. 

### Language:
MQL (NoSQL) and Python with Pymongo

### Data Source:
UK Food Standards Agency https://www.food.gov.uk/ (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GB. Contains public sector information licensed under the Open Government Licence https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/
Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).

### Details:
- [Part 1 of Code](https://github.com/cindyd97/Analyzing_Restaurant_Data_MongoDB/blob/main/NoSQL_setup_starter.ipynb)
- [Part 2 of Code](https://github.com/cindyd97/Analyzing_Restaurant_Data_MongoDB/blob/main/NoSQL_analysis_starter.ipynb)
- [JSON file of Establishments](https://github.com/cindyd97/Analyzing_Restaurant_Data_MongoDB/blob/main/Resources/establishments.json)

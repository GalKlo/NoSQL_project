# nosql-challenge

The script analyzes establishments' food hygiene rating across the United Kingdom using PyMongo performing the following steps:

1. Database set up and Data import.
2. Database update by adding record for a new establishment ("Penang Flavours").
3. Convert data types for fields latitude, longitude and Rating Value.
4. Perform the exploratory analysis, to identify:
    - Establishments that have the hygiene score equal to 20 (41 establishments in total).
    - Establishments in London that have a RatingValue greater than or equal to 4 - (33 establishments in total).
    - Top 5 establishments with a RatingValue of 5, that are located near the new restaurant, added in 2 step.
    - List of Local Authority areas that have a hygiene score of 0, with the number of establishments for each area. (55 Local Autorities in total).

All of the documents identified in step 4 were converted to a Pandas DataFrame for further analysis.

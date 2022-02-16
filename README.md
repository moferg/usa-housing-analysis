# USA Housing Data Analysis Project

This project consists of a Jupyter notebook used to analyze housing data and a CSV file containing data about the USA housing market.

## Work In Progress

**This repo is actively being worked on.**

## Data

This project will use data sourced from a Kaggle dataset about homes for sale in the United States. The data is scraped from Craigslist every quarter or so, but at the time of this writing the most recent update to the dataset was performed on 6/17/2020. The dateset author did not state why the data has not been updated more recently, but this dataset should be fine for the analysis I want to perform. The original dataset can be [found here on Kaggle](https://www.kaggle.com/austinreese/usa-housing-listings)

## Data Dictionary

This information can be found within the original page on Kaggle, but I wanted to also put it in this README for easier access for both myself and anyone else using this project. The following is a list of columns and a description of the data within each column

1. id - listing id
2. url - listing URL
3. region - craigslist region
4. region_url - region URL
5. price - rent per month
6. type - housing type
7. sqfoot - total square footage
8. beds - number of beds
9. baths - number of bathrooms
10. cats_allowed - cats allowed boolean (1 = yes, 0 = no)
11. dogs_allowed - dogs allowed boolean
12. smoking_allowed - smoking allowed boolean
13. wheelchair_access - has wheelchair access boolean
14. electric_vehicle_charge - has electric vehicle charger boolean
15. comes_furnished - comes with furniture boolean
16. laundry_options - laundry options available
17. parking_options - parking options available
18. image_url - image URL
19. description - dexcription by poster
20. lat - latitude
21. long - longitude
22. state - state of listing
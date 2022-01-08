# Cleaning Movie Data using SQLAlchemy 
## Overview
An online retailer is hosting a hackathon focused on developing an algorithm that identifies low-budget movies that soar to popularity. The qualifying movies will be purchased for steaming rights on the retailer's platform. I've been tasked with creating datasets from information scraped from Kaggle and Wikipedia. Our datasets will be used for the hackathon. 
### Preprocessing
To create the datasets I first scrapped the data from Wikipedia and Kaggle movie data sets provided online. After extraction, I did a general overview of the data by converting flat files into pandas Dataframes . I start the iteration processes of cleaning the data by identifying relevant columns, using list comprehensions to filter data. Lastly, in the dataframe I used "regular expression" to ensure the formats were correct for the contents of the column. I merged the two sets to provide a useful summary of information for the hackathon .
## Results
<img width="79" alt="movies_query" src="https://user-images.githubusercontent.com/87162266/139621650-b981031e-d6fa-48bd-925b-44b08bb00171.png">

## Conlusion
The raw data contained 7311 rows and 193 columns. The cleaned data now has 6052 rows and 21 columns. The Kaggle data and Wikipedia data were joined together to provide a summary dataset for the hackathon. The overlagpping of both datasets allowed less error and the ability to fill null values. 

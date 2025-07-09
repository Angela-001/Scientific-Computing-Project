# Scientific-Computing-Project
Using Machine Learning  To Predict Flight Delays At Charleston Airport In 2024 Using Weather Data

This study aims to predict flight delays at Charleston International Airport in 2024 using machine-learning techniques based on weather and flight data from 2014 to 2024. The data were processed using Python, using Pandas DataFrames, Matplotlib, and NumPy arrays for analysis. The Random Forest, Logistic Regression, and Support Vector Machine models were implemented using the Scikit-Learn library. Flight data were retrieved from the Bureau of Transportation Statistics, and weather data from the National Oceanic and Atmospheric Administration (NOAA) National Centers for Environmental Information (NCEI).
Key preprocessing steps included merging datasets, handling missing values using K-Nearest Neighbors (KNN), detecting outliers with Isolation Forest, and standardizing features. Exploratory data analysis included generating summary statistics and visualizing the relationships between flight delay rates and weather variables. 
A key feature engineering step was creating a binary target variable, "Delay," which classified flights as delayed if they departed more than 15 minutes past their scheduled time. Model performances were evaluated using accuracy, precision, recall, and F1-score. The main challenge of this study was class imbalance, as delayed flights were much fewer than on-time flights.
 Ultimately, this project aims to identify the most influential weather factors contributing to flight delays at Charleston International Airport and determine the most effective machine learning model for predicting flight delays. This research has the potential to improve flight scheduling and minimize disruptions in air travel. 

## Technologies Used

- Python 3.10
- Jupyter Notebook
- pandas, numpy
- scikit-learn
  
## Dataset

Datasets ware sourced from NOAA's [National Centers for Environmental Information](https://www.ncei.noaa.gov/access/search/data-search/daily-summaries) and the Bureau of Transportation Statistics website (https://www.transtats.bts.gov/ontime/departures.aspx) 

- The dataset includes 16379 records from Charleston International Airport, Trained using (2014–2023) data, Tested with 2024 data.
- Features selected include:
  Carrier Code
  Date (mm-dd-yyyy)
  Destination Airport
  Departure Delay (Minutes)
  Delay Carrier (Minutes)
  Delay Weather (Minutes)
  Delay National Aviation System (Minutes)
  Delay Security (Minutes)
  Delay Late Aircraft Arrival (Minutes)
  Date(mm-dd-yyyy)
  Average Dew Point Temperature (ADPT)
  Average Sea Level Pressure (ASLP)
  Average Station Pressure (ASTP)
  Average Wind Speed (AWND)
  Precipitation (PRCP)
  Average Relative Humidity (RHAV)
  Snowfall (SNOW)
  Snow Depth (SNWD)
  Temperature


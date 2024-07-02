# ML_Final_Project
We used CMPD crime statistics from 2016-2023, to classify and predict crimes committed in Charlotte during this time based on 25 input features such as latitude, longitude, date, zip code, percentage of non-white population in the zip code, and percentage of home owners in the zip code using over 276,000 data points.

We used a Naive Bayesian model for classical prediction and a Spatiotemporal model for a deep learning model. 

## 1. Datasets Used for Our Dataset:
- Crime Incidents: https://data.charlottenc.gov/datasets/charlotte::cmpd-incidents-1/about
- Vulnerability to Displacement by Neighborhood Profile Area: https://data.charlottenc.gov/datasets/charlotte::vulnerability-to-displacement-by-npa/about
- 2020 Census for Zip Codes in North Carolina: https://www.northcarolina-demographics.com/zip_codes_by_population

## 2. Data Manipulation:
1. Merged Dataset Code: added the socioeconomic and cultural information by NPA (neighborhood profile area) to the crime data.
2. Enumerated Dataset Code: converted the string data into enumerated values included in the Enumerations section.

## 3. Enumerations:
Contains enumerations in csv files such as NIBRS offense codes from the FBI, CMPD patrol division, and location and place type descriptions.

## 4. Classical Models:
1. SVC model: provided a 7% accuracy.
2. Naive Bayesian model we ended up implementing with a 29% accuracy.

## 5. Deep Learning Models:
1. Binary Spatiotemporal Model: the code used to classify non-violent or violent crimes with a 94% accuracy.
2. Multiclass Spatiotemporal Model: the code we ended up implementing to classify 45 different crimes with a 46% accuracy.

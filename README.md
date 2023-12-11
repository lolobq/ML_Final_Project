# ML_Final_Project
We used CMPD crime statistics from 2016-2023, to classify and predict crimes committed in Charlotte during this time based on 25 input features using over 276,000 data points.

## 1. Datasets:
- Crime Incidents: https://data.charlottenc.gov/datasets/charlotte::cmpd-incidents-1/about
- Vulnerability to Displacement by Neighborhood Profile Area: https://data.charlottenc.gov/datasets/charlotte::vulnerability-to-displacement-by-npa/about
- 2020 Census for Zip Codes in North Carolina: https://www.northcarolina-demographics.com/zip_codes_by_population

## 2. Enumerations:
Contains enumerations in csv files such as NIBRS offense codes from the FBI, CMPD patrol division, and location and place type descriptions.

## 3. Classical Models:
- SVC model, which only provided a 7% accuracy.
- Naive Bayesian model we ended up implementing with a 29% accuracy.

## 4. Deep Learning Models:
- Binary Spatiotemporal Model: the code used to classify non-violent or violent crimes with a 94% accuracy.
- Multiclass Spatiotemporal Model: the code we ended up implementing to classify 45 different crimes with a 46% accuracy.

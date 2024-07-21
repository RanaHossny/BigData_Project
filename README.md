# Big Data Project: Traffic Violations Analysis

## Team Number
**Team Number 5**

## Team Members
- **Rana Hossny Hassan** - ID: 1900266
- **Sara Hossny Hassan** - ID: 1901083
- **Andrew Adel Hosny Goued** - ID: 1900158
- **Hady Ahmed Mostafa Hassan** - ID: 1901293
- **Eyad Ashraf Elkiey** - ID: 1900399

## Introduction
Traffic law violations are a significant issue in the United States, particularly in densely populated areas like Maryland, leading to numerous accidents and loss of life. These violations, including speeding and reckless driving, are enforced by local authorities and adjudicated in state courts. This project analyzes traffic violation data to uncover trends and insights to aid in reducing road accidents.

## Implementation

### Data Collection and Preprocessing
- **Dataset:** The dataset used is a large file of 1.5 GB containing more than 1 million rows. [Download the dataset here](https://www.kaggle.com/datasets/ranahossny/traffic-violations).
- Loaded data from a JSON file and converted it to a DataFrame.
- Renamed columns for clarity and cleaned data by removing irrelevant entries and addressing missing values.
- Performed one-hot encoding for categorical variables and converted date and time to datetime types for analysis.

### Data Analysis
- **Geospatial Analysis:** Plotted Longitude and Latitude to visualize the distribution of violations.
- **Correlation Analysis:** Calculated correlations to identify relationships between variables.
- **Time Series Analysis:** Analyzed the number of traffic violations and accidents over time, revealing patterns and trends.
- **Violation Patterns:** Identified that most violations and accidents occurred in specific districts and at particular intersections. Analyzed the reasons for violations and accidents, noting that speeding and negligent driving were prevalent.

### Prediction of Accident Likelihood
- Compared the likelihood of accidents related to seat belt violations versus alcohol-related incidents, finding a higher association with seat belt violations.

### Data Modeling
1. **Logistic Regression:**
   - Encoded categorical labels into numeric values.
   - Achieved an accuracy of 97.38%.
   
2. **KNN Classifier:**
   - Created and tested the KNN model.
   - Achieved an accuracy of 97.55% and a mean squared error of 0.0245.

## Conclusion
The analysis and modeling have provided valuable insights into traffic violations and accidents in Montgomery County, Maryland. Key findings highlight the significant impact of seat belt violations and alcohol-related accidents. By applying predictive models, this project aims to enhance road safety and encourage responsible driving behaviors.

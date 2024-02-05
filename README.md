# 🚀 Sberbank Russian Housing Market

This repository contains research for real estate price prediction use case.

[Link to kaggle](https://www.kaggle.com/code/anastasiakorotkova/sber-eda)

## Data
| price_doc| sale price (this is the target variable) | 
| id | transaction id | 
| timestamp | date of transaction | 
| full_sq | total area in square meters, including loggias, balconies and other non-residential areas | 
| life_sq | living area in square meters, excluding loggias, balconies and other non-residential areas | 
| floor | for apartments, floor of the building | 
| max_floor | number of floors in the building | 
| material | wall material | 
| build_year | year built | 
| num_room | number of living rooms | 
| kitch_sq | kitchen area | 
| state | apartment condition | 
| product_type | owner-occupier purchase or investment | 
| sub_area | name of the district | 

## Metric - RMSLE

## Results:
- EDA analysis
- Correlation analysis (removed columns where the correlation is > 0.9)
- Converting categorical columns
- Outlier analysis
- Work with the date (TimeSeriesSplit)
- LinearRegression as a baseline
- Data segmentation

###How else can the model be improved? A few areas to think about:
- Train other models
- Add macro indicators to the dataset
- Generate new features from existing ones (not simple encoding)
- Conduct a more in-depth EDA analysis
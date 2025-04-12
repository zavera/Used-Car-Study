# Used Car Price Analysis

## Overview

This Jupyter Notebook explores a dataset of used cars to understand the factors that influence their prices.
The analysis aims to provide actionable insights for a used car dealership, helping them understand what features
consumers value most. The notebook follows the CRISP-DM (Cross-Industry Standard Process for Data Mining) framework.

## Dataset

The dataset used in this analysis is a subset (426K cars) of a larger dataset from Kaggle,
which originally contained information on 3 million used cars. This smaller dataset was chosen to ensure efficient processing.
## How to view analysis
The complete analysis, including code and visualizations, can be viewed in this Jupyter Notebook:

https://github.com/zavera/Used-Car-Study/blob/main/prompt_II.ipynb

## Key Questions to Address

*   Which features have the strongest correlation with a car's price?
*   How do categorical variables (e.g., make, model, transmission type) affect the price?
*   Can a predictive model be built to estimate a car's price based on its features?
*   What are the most important factors that a used car dealership should focus on when acquiring inventory?

## Technologies Used

*   Python
*   Pandas
*   NumPy
*   Scikit-learn
*   Matplotlib
*   Seaborn

## Findings
https://github.com/zavera/Used-Car-Study/blob/main/prompt_II.ipynb
The analysis reveals that car age and type are significant factors influencing used car prices.
Older cars (car_age) generally exhibit lower prices, reflecting depreciation.
Additionally the analysis show that certain car types remain high in prices despite the car age. Therefore
an isolated analysis was performed where it was revealed that certain types like coupe and convertible
are likely to avoid depreciation even at a higher car age. This means coupe and convertible
type can be accumulated in inventory by dealership despite the car age.


## Next Steps

As next steps the recommendation is to isolate
the subset of high car prices at higher car age and group this subset based on other indicators other than
type to determine any more potential underlying factor.

## Author

Ambreen Zaver

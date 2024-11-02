# kaggle-competitions
This repository contains several entries to Kaggle Competitions. The spirit of the entries is merely to practice with new datasets and use different algorithms and strategies. In other words, for fun.

## Car Prices
### Difficulties
The dataset contained mainly categorical variables. Some feature engineering was needed to reduce dimensionality. Moreover, I took the opportunity to try word embeddings. Due to outliers, the log of the price is calculated, which gave better results.

### Algorithm
A neural network with word embeddings.

### Results and Placement
2083/3068

1555 off first in RMSE

## Loans
### Difficulties
The dataset tends to a good AUC value with little data wrangling, which makes difficult improving on the metric.

### Algorithm
An XGBoost with Polynomial features.

### Results and Placement
1436/3859

0.01175 off first in AUC
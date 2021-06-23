# ODSC Europe 2021 Data Science Challenge

**Aim:** Predict the probability of a potential sale on a website analytics data set.

## ☑️ What did I do?
- _First_, I performed some simple exploratory data anlysis (EDA) tasks: descriptive statistics using `describe()`; and obtaining the number of unique values in the columns using `nunique`.
  - This helped me find some outliers in the data, which I removed.
- _Secondly_, I performed visual EDA tasks, e.g., a correlation heatmap, that helped me gain __5 key insights__ into the nature of the given data set.
- _Thirdly_, I preprocessed the data by performing:
  * One-hot encoding on the categorical variables; and
  * Missing value imputation by __creating 'missing value' indicators__.
- _Fourthly_, I performed feature engineering, more specifically, *mutual information*, to help extract the relative potential of the features as a predictor of the target, considered by itself.
- _Fifthly_, I created new features and performed scaling (though it was not required, ouch!)
- _Lastly_, I trained a Logistic regression model among 2 other models to achieve an ROC-AUC of 0.92.

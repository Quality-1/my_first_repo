# my_first_repo
NLP project for predicting and analysing sentiment scores using ElasticNet regression and other linear models. Includes data preprocessing, outlier removal, feature engineering, model training, and evaluation.

##  Summary
This repository contains the code, data preprocessing steps, and models used in a machine learning project focused on sentiment analysis. The aim is to explore the effectiveness of different linear regression model (ElasticNet) in predicting sentiment scores from text-derived features.

---

## Top 3 Positive Employees
These employees consistently expressed positive sentiment in their communications:
1. sally.beck@enron.com    2010-08                       14
2. john.arnold@enron.com   2011-02                       12
3. johnny.palmer@enron.com 2011-06                       12


##  Top 3 Negative Employees
These employees had the highest frequency of negative sentiment messages:
1. sally.beck@enron.com    2010-07                       -2
2. sally.beck@enron.com    2011-03                       -2
3. johnny.palmer@enron.com 2010-07                       -1

---

##  Flagged Flight Risk Employees
Based on the analysis of negative message frequency (≥4 within a 30-day window), the following employees were flagged:

1.	eric.bass@enron.com
2.	patti.thompson@enron.com
3.	sally.beck@enron.com
4.	bobette.riner@ipgdirect.com
5.	john.arnold@enron.com
6.	johnny.palmer@enron.com
7.	kayne.coulter@enron.com
8.	lydia.delgado@enron.com
9.	rhonda.denton@enron.com
10.	don.baughman@enron.com


---

##  Key Insights

- Most employees express negative sentiment which may be tied to job dissatisfaction or burnout.
- A subset consistently displayed positive sentiment, which might be as a result of job statisfaction
- Employees flagged as flight risks often show clustered negative sentiment shortly before exiting.

---

## Recommendations

- Proactively engage with flagged employees through one-on-one sessions.
- Use sentiment trends as early warning signals for HR intervention.
- Incorporate ongoing sentiment monitoring into employee engagement strategy.

---

## Future Work

Explore non-linear models (Random Forest, XGBoost, Neural Networks).
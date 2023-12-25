# Health_Insurance_CrossSell_Prediction
As We Know Health Insurance is an important financial decision which everyone must take. My Aim here is to observe which clients are willing to take Motor Insurance policy along with the heath Insurance policy as a part to increase my company's product sales.

# The Link to Dataset I have used for my Study
https://github.com/ShrinarayanP/ML_Projects/blob/main/TRAIN-HEALTH%20INSURANCE%20CROSS%20SELL%20PREDICTION%20(1).csv

# What have I Done in my project
I have tried to explore the dataset and to do so I have used numpy, pandas, matplotlib, seaborn libraries of python.
I have done data preprocessing as needed for my study, I removed nulls and missing values if needed, I tried to find outliers and removed if needed.
For predictive analysis I have used 3 different models and have also tried to get the best of the results using hyper-parameter tuning and cross validation.
### Models used here are:
1. Logistic Regression
2. RandomForestClassifier
3. GradientBoostingClassifier

### For hyper parameter tuning
I have used GridSearchCV for LogisticRegression and RandomizedSearchCV For other two Models.
I used GridSearchCV First and because it was taking a long time to produce results I used RandomizedSearchCV for the next Two Models.

### How have I estimated  the model to be good
For This I have used accuracy Score, Precision Score to estimate the best model.
I used these and not r2_Score or rmse etc. because I am studying a classification Model model.

## What is my Conclusion
After all study on this dataset I have concluded that Simple GradientBoostingClassifier is my best model.

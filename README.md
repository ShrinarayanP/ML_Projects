# Yes_Bank_Stock_Close_Price_Estimator
In current time of Internet being cheap and easily available to all, there has been a great exploration of financial tools, people now look at different ways to make money to secure future and also to manage there daily expenses and under such situations one of the best way to earn big in short time is from Stock Market, but stock market is full of unevenness and volatile for short term traders and for long term holders also it is important to know what the future of my stock will be.
From above comes the reason to predict future stock prices, and here we are going to apply machine learning algorithm on the Yes Bank Stock data to predict the future outcomes.
Here My aim is to analyze the data and predict the future of Yes Bank stock using the regression model.

# What have I Done in my project
I have tried to explore the dataset and to do so I have used numpy, pandas, matplotlib, seaborn libraries of python.
I have done data preprocessing as needed for my study, I removed nulls and missing values if needed, I tried to find outliers and removed if needed.
For predictive analysis I have used 3 different models and have also tried to get the best of the results using hyper-parameter tuning and cross validation.
### Models used here are:
1. Linear Regression
2. Decision Tree
3. K Nearest Neighbors (KNN)

### For hyper parameter tuning
I have used GridSearchCV, This I have used because Grid Search studies the maximum possible combinations and since my dataset is small it's good to go with all possible combinations.

### How have I estimated  the model to be good
For This I have used r2 Score, adjusted r2 Score, Mean Square Error and Root Mean Square error to estimate the best model.
I used these and not accuracy, precision etc. because I am studying a regression model which is continous is nature.

## What is my Conclusion
After all study on this dataset I have concluded that Linear regression with Lasso regularization is my best model.

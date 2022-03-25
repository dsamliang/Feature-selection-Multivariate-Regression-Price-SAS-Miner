# Feature-selection-Multivariate-Regression-Sales-SAS-Miner


Dataset: data.csv (House Price Prediction: https://www.kaggle.com/datasets/shree1992/housedata)

**Steps:**

Create Diagram
Drag File Import node from sample and import supermarket_sales.csv
Edit Variables, set  as Target
Select Input features
Drag data partition node from sample
select ratio of train, validate, and test set (60,30,10)
Drag regression node from model tab
Select Model selection (Backward, Forward, Stepwise), input coding, and regression type from regression node properties
Run Regression node and view the results


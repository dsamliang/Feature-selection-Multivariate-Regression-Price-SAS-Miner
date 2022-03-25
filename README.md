# Feature-selection-Multivariate-Regression-Price-SAS-Miner


Dataset: data.csv (House Price Prediction: https://www.kaggle.com/datasets/shree1992/housedata)

**Steps:**

Create Diagram

1.Drag File Import node from sample and import data.csv

2.Edit Variables, set  as Target

3.Select Input features

4.Drag data partition node from sample

5.Select ratio of train, validate, and test set (60,30,10)

6.Drag regression node from model tab

7.Select Model selection (Backward, Forward, Stepwise), input coding, and regression type from regression node properties

8.Run Regression node and view the results


# Feature-selection-Multivariate-Regression-Price-SAS-Miner


**Dataset:** 
-

data.csv (House Price Prediction: https://www.kaggle.com/datasets/shree1992/housedata)

**Steps:**
-
1.Create Diagram

2.Drag File Import node from sample and import data.csv

3.Edit Variables, set Price as Target
- ![image](https://user-images.githubusercontent.com/98597962/160190956-c0e2bd48-0345-4d7d-8598-67b06da35c52.png)

4.Select Input features

5.Drag data partition node from sample

6.Select ratio of train, validate, and test set (60,30,10)

7.Drag regression node from model tab

8.Select Model selection **(Backward, Forward, Stepwise)**, input coding (GLM), and regression type from regression node properties (Linear Regression)

9.Run Regression node and view the results


**Results:**
-

**Backward:**
- ![image](https://user-images.githubusercontent.com/98597962/160191094-d444c78f-b375-4fc4-be80-93669755ac3d.png)

- View >>> Model >>> Estimate Selection Plot
  - ![image](https://user-images.githubusercontent.com/98597962/160191516-fd170f89-ca42-4530-bd7e-e4563974edba.png)



**Forward:**
- ![image](https://user-images.githubusercontent.com/98597962/160192020-de21290e-05a8-4807-8123-8c5d776165f0.png)

- View >>> Model >>> Estimate Selection Plot
  - ![image](https://user-images.githubusercontent.com/98597962/160192081-0ecdb187-0923-4272-8c86-4cc49b7ed0e2.png)



**Stepwise:**
- ![image](https://user-images.githubusercontent.com/98597962/160192663-a387940d-ac40-4f68-925c-52b77d3332dc.png)

- View >>> Model >>> Estimate Selection Plot
  - ![image](https://user-images.githubusercontent.com/98597962/160192693-bb34d506-7976-40df-b8ef-2d8ae10e19df.png)



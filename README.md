# world_cup_win_simulator

This is a complete match win prediction of Qatar WC 2022 group stage matches. Generating feature of each team by their fifa ranking and match won through out the years in tournament categorized as friendly and professional.


Then I used four models Random florest, MLPClassifier, KNeighborsClassifier and Logistic Regression on those features to trains the data.

The idea is to separete the performance of each Team as Home or Away.

here is the snipshot of the models

## Random Forest
![RandomForest](../master/RandomForest.png)

## MLPClassifier
![MLPClassifier](../master/MLPClassifier.png)

## KNeighborsClassifier
![KNeighborsClassifier](../master/KNeighborsClassifier.png)

## Logistic Regression
![LogisticRegression](../master/Logistic Regression.png)

# OUTPUT
## Prediction Points on Data
![Data](../master/data.png)
![PredictionPoints](../master/prediction_points.png)

# Prediction 1
![P1](../master/prediction_1.png)
# Prediction 1
![P2](../master//prediction_2.png)


## installation

```
create virtual environment !(python3 -m venv env)

active virtual environment !(source ./env/bin/activate)

install dependencies !(pip install -r requirements.txt) 

run code !(python world_cup2.py)
```
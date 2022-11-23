# world_cup_win_simulator

This is a complete match win prediction of Qatar WC 2022 group stage matches. Generating feature of each team by their fifa ranking and match won through out the years in tournament categorized as friendly and professional.


Then I used four models Random florest, MLPClassifier, KNeighborsClassifier and Logistic Regression on those features to trains the data.

The idea is to separete the performance of each Team as Home or Away.

here is the snipshot of the models

Random Forest
![Random Forest](../master/Random Forest.png)

MLPClassifier
!(../master/code_snip/MLPClassifier.png)

KNeighborsClassifier
(code_snip/KNeighborsClassifier.png)

Logistic Regression
!(../master/code_snip/Logistic Regression.png)

# OUTPUT
Prediction Points on Data
!(../master/code_snip/data.png)
!(../master/code_snip/prediction_points.png)

# Prediction 1
!(../master/code_snip/prediction_1.png)
# Prediction 1
!(../master/code_snip/prediction_2.png)


## installation

```
create virtual environment !(python3 -m venv env)

active virtual environment !(source ./env/bin/activate)

install dependencies !(pip install -r requirements.txt) 

run code !(python world_cup2.py)
```
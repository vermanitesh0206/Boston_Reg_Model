# Boston_Reg_Model
PROBLEM STATEMENT : Predict the median value of occupied homes

Each record in the data describes a Boston suburb or town.
There are 506 rows and 14 columns
The data was drawn from the Boston Standard Metropolitan Statistical Area (SMSA) in 1970.

The attributes are deﬁned as follows (taken from the UCI Machine Learning Repository

1: CRIM: per capita crime rate by town
2. ZN: proportion of residential land zoned for lots over 25,000 sq.ft.
3. INDUS: proportion of non-retail business acres per town
4. CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
5. NOX: nitric oxides concentration (parts per 10 million)
6. RM: average number of rooms per dwelling
7. AGE: proportion of owner-occupied units built prior to 1940
8. DIS: weighted distances to ﬁve Boston employment centers
9. RAD: index of accessibility to radial highways
10. TAX: full-value property-tax rate per $10,000
11. PTRATIO: pupil-teacher ratio by town
12. BLACK: 1000(Bk−0.63)2 where Bk is the proportion of blacks by town
13. LSTAT: % lower status of the population
14. MEDV: Median value of owner-occupied homes in $1000s

There are 2 models built one by normalizing the dataset other one without normalization.
Following attributes are used to build the model : CRIM,CHAS,NOX,RM,DIS,RAD,TAX,PTRATIO,BLACK,LSTAT
Target attribute : MEDV
Accuracy : 72 %

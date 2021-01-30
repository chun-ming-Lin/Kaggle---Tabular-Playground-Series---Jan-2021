# Kaggle---Tabular-Playground-Series---Jan-2021
## This is kaggle 2021 JAN compete 
 [2021 JAN Tabular-Playground-Series](https://www.kaggle.com/c/tabular-playground-series-jan-2021/overview)
 
# 這次競賽我用了基本模型與神經網路模型

## 用神經網路來預測這次的回歸問題，其中用上了stacking model
這是我第一次用堆疊模型，成效並不是很好還有蠻多地方需要加強
![Image](https://github.com/chun-ming-Lin/Kaggle---Tabular-Playground-Series---Jan-2021/blob/master/model_graph.png)


[stacking model參考](https://machinelearningmastery.com/stacking-ensemble-for-deep-learning-neural-networks/)

## 用基本ML模型預測
* 選用xgboost, lightgbm
* 合併兩個預測值後讓我的成績達到前25%

###### 這次競賽比較難的地方在不知道欄位的意義，所以特徵處理起來比較困難

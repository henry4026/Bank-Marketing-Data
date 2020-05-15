# captstone project2: predicting future customers purchase term deposit.
## Goal
Predicting future customers purchase term deposit
## Data 
1. The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.
2. dataset size: 42000 rows with 26 columns.
## EDA and daily work
1. understand and clean the dataset.
2. feature engineering.
3. fixing imbalance dataset by doing oversampling and undersampling.
4. use gridsearch for tuning hyper parameter.
5. tuning model
## modeling.
1. use 3 different model: logistic regression, gradient boosting, random forest.
2. create roc curve, compare the 3 different models with the AUC.
3. create confusion matrix, compare the 3 different models with cost benefit matrix.
4. focus on recall rate.
5. decision boundary, try different threshold to find which generate the most profit.
6. create precision/recall Curve graph to show precision/recall
7. create decision boundary graph to show different profit with differet threshold
## finding.
1. my dataset is imbalance so roc curve isn't very accurary, thats why i chose precision/recall.
## conclusion. 
1. final random forest model hsa around 80% recall and 53% precision.
2. random forest generate the most profit from cost benefit matrix.
## future action.
1. focus more on gridsearch
2. better visualization
3. try more models

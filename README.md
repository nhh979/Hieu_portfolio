# Hieu_Portfolio
My personal data analytics projects.

# [Project 1: Bike Sharing Demand|Kaggle Competition](https://github.com/nhh979/Bike_Sharing_Demand_proj/tree/main)
- Analyzed the key factors that influence bike rental demand such as holiday, workingday, weather conditions.
- Performed EDA to determine the difference between registered and casual bikers.
- Built models to predict the number of bike rentals for a giving time based on historical data and compared the difference in performance between with and without feature engineering.
- Optimized the models using GridSearchCV with 5-fold cross validation and got a final RMSLE score of 0.47501 from XGBoost model.  

![](https://github.com/nhh979/Bike_Sharing_Demand_proj/blob/main/images/baseline_models_comparison.JPG)  

![](https://github.com/nhh979/Bike_Sharing_Demand_proj/blob/main/images/tuned_models.JPG)  

|Model|Public RMSLE|Private RMSLE|
|------|------|------|
|XGBoost|0.47501|0.47501|
|Random Forest|0.59508|0.59508|
|XGBoost & RandomForest|0.47496|0.47496|  


# [Project 2: Employee Retention Prediction|Google Advanced Data Analytics Capstone Project](https://github.com/nhh979/employee_retention_proj)
- Created a tool to predict employees that are likely to quit the company with a ROC AUC score of 98%.
- Run two samples t-test hypotheses to determine whether there is a differene in average monthly working hours, satisfaction levels, last evaluation score between employees who left vs. who stayed. 
- Optimized Random Forest Classifier and XGBoost Classifier using GridSearchCV and RandomizedSearchCV.

![](/images/evaluation_scores.jpg)
![](/images/feature_importance.jpg)

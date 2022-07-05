# stage-c-quiz.-classification
Xgboost, Lightgbm and so forth

README.md
In this project, I analyzed Energy consumption data on behalf of a power company. Exploratory visuals pointed to a linear relationship between variables so we use a linear regression model for this prediction.

The classification algorith has a method to store and assign weights to features of a particular label, using this knowledge to correctly label unseen data.


Data Summary:


the steps in ths project:

1. data importation from csv(local) to my python notebook.
2. Explored the data. collected snapshot,summary statistics on dataset and checked for missing cells in tabular dataset.
3. Dropped one column as recommended by the domain experts.
4. exploration revealed imbalance in the number of classes so we downsample to make it equal. 
5. we reset index after downsample.
6. Normalization - sets all values between 0 and 1 to fit the classification model of choice.
7. Train-test split.
8. Compared the evaluation metrics of Random forest, xgboost and light GBM classifier. 
9. they all did great. enjoy!











Classification algorithms in ML

README.md

The classification algorithm has a method to store and assign weights to features of a particular label, using this knowledge to correctly label unseen data.



Data Summary:
we have 2 classes of output: stable and unstable. each stable class has certain characteristics by default, which is reported by various detection tools.
the machine will learn the relationships and use this to predict the class of an energy stream based on its key metrics. (dependent variables), when fed into model.

We have more samples for stable, by almost 3 times the sample size. 
we overcome this misfit by downsampling the stable class smaples to match the unstable class. 

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










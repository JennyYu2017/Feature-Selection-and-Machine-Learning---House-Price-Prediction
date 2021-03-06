# Machine-Learning---House Price Prediction with Random Forest Regressor 

In this project, I use the Random forest algorithm to build the house price prediction model on a dataset with 16 features and 4600 samples from Kaggle(https://www.kaggle.com/shree1992/housedata). 

Random Forest Regressor will be an optimal algorithm in this problem because it works well on both categorical and numerical features. Moreover, it is robust to missing values, new entries, and outliers and will save us the effort to normalize the data considering each feature’s scale varies a lot.  

The experiment shows that feature engineering using Recursive Feature Elimination does help improve model performance. Comparing the model trained on all features, the model trained on the 7 optimal features improves the R2 score from 0.4904 to 0.5435 while reducing the Mean absolute error from 134490.3 to 131453.1. 


# Plots and Visualizations

![](https://github.com/JennyYu2017/Feature-Selection-and-Machine-Learning---House-Price-Prediction/blob/master/Plots/Accuracy%20Score%20vs.%20Numbr%20of%20Features%20Selected.png)

![](https://github.com/JennyYu2017/Feature-Selection-and-Machine-Learning---House-Price-Prediction/blob/master/Plots/Actual%20vs%20Predicted%20Housing%20Price%20on%20the%20Testing%20set%20with%20all%2016%20features.png)

![](https://github.com/JennyYu2017/Feature-Selection-and-Machine-Learning---House-Price-Prediction/blob/master/Plots/Actual%20vs%20Predicted%20Housing%20Price%20on%20the%20Testing%20set%20with%20randomly%20selected%2010%20features.png)

![](https://github.com/JennyYu2017/Feature-Selection-and-Machine-Learning---House-Price-Prediction/blob/master/Plots/Actual%20vs%20Predicted%20Housing%20Price%20on%20the%20Testing%20set%20with%207%20optimal%20features.png)

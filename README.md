Predicting wine quality
===============
###### _All data here presented can be obtained on the website:_ (http://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/)

This is a personal project which in I do a brief Exploratory Data Analysis (EDA) on the UCI wine dataset as well as try to predict the quality from red wine based on several chemical features.

For this project I used Python and the following libraries:
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

The database is very well organized and clean.

To predict the quality of the wine, it was used four models from the scikit-learn package:

- LogisticRegression
- DecisionTreeClassifier
- RandomForestClassifier
- GradientBoostingClassifier

They were mainly chosen because either they are good dealing with imbalanced classes or they supported multi-class classification. 

Besides that, upsampling and rearrangement techniques were applied in the data so that the models could perform better.

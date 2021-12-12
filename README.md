# music_genre_prediction

### About the project
This is the multiclass prediction project where I used the machine learning algorithms to predict the music genre on the basic of previous data with the help of Sklearn library.

### Tool Used
Used Python for data analysis for that particular dataset. Libraries used for this project are:
Numpy
Pandas
Matplotlib
Seaborn
sklearn

### Installation
for numpy
```pip install numpy```


for Pandas
```pip install pandas```


For Matplotlib
```pip install matplotlib```


For Seaborn
```pip install seaborn```

For Sklearn
```pip install scikit-learn```

For SMOTE
```pip install imbalanced-learn``` 

For CatBoost
```pip install catboost```

### Impotant Steps
Data Cleaning is the most important step in any data science project. In this project data has null values, special characters like '?', and -1 value in some feature where it must not be there. So first of all we have to solve all these problems using pandas and numpy.
Categorical features should be encoded with the help of label encoder, one-hot encoding or any other encoding method.
As it is a multiclass data, so there are some class which are less in comparison of other. And this will impact the precision and recall of model. To Solve this we can use SMOTE over sampling or any other method.
For any data science project, the data should be scaled. For this we can use Minmax scaler or Standard Scaler.
One of the key point in data science project is never use all the data for training even if we have seperate test data. Always split the train data in proportion of 70:30 or 80:20. By doing this we can check our model's peformance on test data.
Use different algorithms for single model with hyper parameter tuning to check the performance.
After finelizing the model, it is imporatnt to save it for future use. We can use Pickle or joblib for this.

# machine-learning-challenge
Background
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.
In order to process this data, need to create machine learning models capable of classifying candidate exoplanets from the raw dataset.

Steps
Preprocess the raw data
Tune the models
Compare two or more models

Preprocess the Data
Preprocess the dataset prior to fitting the model.
Perform feature selection and remove unnecessary features.
Use MinMaxScaler to scale the numerical data.
Separate the data into training and testing data.
Tune Model Parameters
Use GridSearch to tune model parameters.
Tune and compare at least two different classifiers.

Reporting
Comparison of each model's performance as well as a summary about the findings and assumptions made based on the models

Comparing results on test data:

DecisionTreeClassifier 0.8478260869565210

LogisticRegression   	 0.8621281464530890

Neural Network		     0.8689931631088250

Deep Learning		       0.8815789222717280

RandomForestClassifier 0.8975972540045760 - Best Model

SVM - Without Tuning	 0.8750715239366770

SVM - With Hyperparameter Tuning		0.8815789473684210

RandomForestClassifier has the best score (0.8975972540045760) on Test Data. It is saved in Final_Model folder.

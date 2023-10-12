# Sports-Analytics-Using-MachineLearning
Baseball Game Attendance Prediction
This repository contains code to predict baseball game attendance using machine learning models on game data from 2016.

# Data
The baseball.csv dataset contains stats from 2,427 MLB games played in 2016. Each row represents a single game.

The target variable to predict is attendance_binary, whether the attendance was above or below the median attendance for that team in that season.

The other variables provide information about the home and away teams' performance in recent games.

# Models
The following machine learning models are trained on the dataset:

Dummy classifier baseline
SVM with linear kernel
SVM with polynomial kernel
SVM with RBF kernel
SGD classifier
Logistic regression
The models are evaluated based on accuracy, and logistic regression is found to perform the best with 85% test accuracy.

# Usage
The Jupyter notebook Sports_Analytics.ipynb contains the full code to load data, preprocess, train models, and evaluate results.

# To use:

Install requirements: numpy, pandas, scikit-learn
Run the notebook cells to load data, preprocess, train models, evaluate, and generate results
# References
The dataset is made available by  http://www.baseball-reference.com

# Stroke Prediction using Machine Learning Models

This project analyzes the Stroke Prediction Dataset from Kaggle (https://www.kaggle.com/fedesoriano/stroke-prediction-dataset) using machine learning models such as Support Vector Machine (SVM), Logistic Regression, K-Nearest Neighbor, and Neural Network. The project aims to predict the probability of a person having a stroke based on their health records.

## Dataset Description

The Stroke Prediction Dataset consists of 5110 records containing various health-related features such as age, hypertension, heart disease, etc., and whether or not the person had a stroke. 

## Preprocessing and Data Analysis

The dataset was preprocessed and analyzed before being fed to the machine learning models. Firstly, the correlation between the features was visualized using a heatmap. Then, the dataset was split into features and targets, and the relevant columns were selected using the iloc method. After that, the data was rescaled using the MinMaxScaler to convert the data into a range of 0 - 1.

## Machine Learning Models and Evaluation

The data was then split into training and testing sets with a split ratio of 70:30. Four machine learning models were used - SVM, Logistic Regression, K-Nearest Neighbor, and Neural Network, to predict the probability of a person having a stroke. The accuracy score was used as the evaluation criteria for the models.
Results

After training and testing the models, the accuracy score of each model was calculated. The results showed that SVM and Neural Network had the highest accuracy score of, followed by Logistic Regression and K-Nearest Neighbor.

## Conclusion

In conclusion, machine learning models such as SVM, Logistic Regression, K-Nearest Neighbor, and Neural Network can be used to predict the probability of a person having a stroke based on their health records with high accuracy. These models can assist healthcare professionals in identifying individuals who may be at risk of having a stroke and providing preventative care.

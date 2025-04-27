# Parkinson Predictor
This is a lab project for the Machine Learning course in Semester 2 of DTU. The project aims to predict whether a person is suffering from Parkinson's disease based on a set of features extracted from voice recordings.
## Project Overview
The objective of this project is to develop a machine learning model to predict Parkinson’s disease using various voice-related features. The dataset used contains several voice attributes that help distinguish between individuals with Parkinson's disease and those who are healthy.

The model is trained using Support Vector Machine (SVM), a supervised learning algorithm, and achieves a high accuracy score on both training and test data.

## Target:
0: Not suffering from Parkinson's disease

1: Suffering from Parkinson's disease
## Installation
To run this project locally, you need the following dependencies:
pip install numpy pandas scikit-learn
For running the project on Google Colab, no installation is needed as all dependencies are pre-installed.
## How to Run
Clone this repository to your local machine or open the notebook on Google Colab.

Load the dataset into the notebook and run all the cells in order.

The model will be trained using the SVM classifier, and you will receive the accuracy scores for both training and testing data.

You can also input your own data for prediction by running the "Making a Predictive System" section.
## Model Evaluation

Testing Accuracy: The model's performance on the test data which is around 89%.
## Conclusion
This project demonstrates the use of Support Vector Machine (SVM) in predicting Parkinson’s disease from speech features. The model can be enhanced further by experimenting with other machine learning algorithms, tuning hyperparameters, or adding more features.

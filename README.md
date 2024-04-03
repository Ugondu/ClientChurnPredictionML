## CLIENT CHURN PREDICTION SYSTEM

![image](https://github.com/Ugondu/ClientChurnPredictionML/assets/113315492/991a44fc-7dc2-43e5-bb82-b1da63807850)

## Table of Contents
- [Project Overview](#Project-overview)
- [Project Objective](#Project-objective)
- [Data Sources](#data-sources)
- [Data Preprocessing](#data-preprocessing)
- [Machine Learning Models](#machine-learning-models)
- [Evaluation Metrics](#evaluation-metrics)
- [Key Insights](#key-insights)
- [Conclusion and Recommendation](#conclusion-and-recommendation)

  
## Project Overview
The “Client Churn Prediction using Machine Learning” project aims to build and train machine learning systems capable of predicting if clients are likely to stop using the services of a telecommunication company. This project will enhance the retainability and growth of clients to ensure they remain in business.

## Project Objective
The objective of this project is to build and train three different supervised machine learning models, evaluate, and recommend the best-performing model for real-time predictions of clients' churn rates.

## Data Sources
The dataset used in this project was provided by 10Alytics. The dataset contains a collection of features extracted from the company domain including contract length, contract type, gender, streaming services, and other relevant information.

## Data Preprocessing
Before fitting the data into the machine learning model, extensive data preprocessing was carried out on the data set. This included missing values, normalisation, infinite values, and addressing class imbalances. Features engineering was carried out to extract and merge new features.

## Machine Learning Model
The prediction model is built using supervised machine learning algorithms. Training and test data was split ratio 20:80. Three different models were built, trained, and experimented with to determine the best performing model. The model experimented with are.
-	**Logistic Regression**
-	**Random Forest Classifiers**
-	**K-Nearest Neighbors**
After extensive experimentation and hyperparameter tuning, the final machine learning model was determined based on its performance and generalisation capabilities.

## Evaluation Metrics
To assess the performance of the machine learning model, the following metrics were utilised.
-	**Accuracy:** This is the overall proportion of correct predictions made by each model. This metric provides an overall assessment of the model performance in correctly classifying customers as churners or non-churners.
-	**Precision:** Precision represents the accuracy of identifying actual churners among the predicted churners. High precision indicates fewer false positives, which is important for minimizing the cost of incorrectly identifying non-churners as churners.
-	**Recall (Sensitivity):** Recall measures the proportion of true positive predictions out of all actual instances belonging to the positive class. It represents the model's ability to correctly identify all actual churners among the total number of churners. High recall indicates fewer false negatives, which is important for capturing as many actual churners as possible to prevent customer attrition.
-	**F1-score:** The F1-score is the harmonic mean of precision and recall, providing a balanced measure of a model's performance. It considers both false positives and false negatives and is particularly useful when there is an imbalance between the classes in the dataset.
  
## Key Insights
-	this project aims to predict churners. 
-	The best model that predicts with lesser error is selected, subjecting it to different evaluation metrics such as 5-fold cross-validation (accuracy, precision, and recall).
-	Confusion matrices of the different models display the error values in terms of false positives (where the model predicts a client to be a churner when they aren’t- Precision) and false negatives (where the model predicts a client to be a non-churner whereas they are churners- recall).
  
## Conclusion and Recommendations
Considering the metrics, the logistic regression model performed best given the higher recall score and accuracy.


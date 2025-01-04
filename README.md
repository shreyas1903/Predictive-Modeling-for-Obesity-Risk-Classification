Obesity Risk Prediction using Machine Learning
This repository contains the code and documentation for a project aimed at predicting obesity risk using various machine learning models. The study leverages demographic, behavioral, and lifestyle data to classify individuals into obesity risk categories, providing a more personalized approach to obesity classification compared to traditional methods like BMI.

Overview
Obesity is a significant health concern that contributes to various chronic diseases such as diabetes, cardiovascular diseases, and certain cancers. Traditional methods of assessing obesity, such as the Body Mass Index (BMI), do not capture the full complexity of this condition. In this project, machine learning (ML) models are used to predict the risk of obesity by analyzing a dataset containing 18 features, including age, gender, physical activity, caloric intake, and transportation modes.

Models Used
The project evaluates the performance of the following machine learning algorithms:

Support Vector Machine (SVM)
Random Forest
Decision Tree
XGBoost (Best performer in this study)
These models are trained and tested on a dataset sourced from Kaggle. The performance of each model is evaluated using accuracy, recall, and F1-score metrics, with XGBoost emerging as the top performer.

Dataset
The dataset used in this project contains 18 features, including demographic, behavioral, and lifestyle attributes, along with the target variable indicating obesity risk categories. It consists of:

Training Data: 20,758 records, with 18 features and the target variable NObeyesdad.
Testing Data: 13,840 records used for validation.
Feature List
Demographic Variables: Age, Gender, Height, Weight
Behavioral Attributes: Family history of overweight, frequency of high-calorie food consumption, vegetable consumption, number of meals per day, etc.
Lifestyle Variables: Water intake, alcohol consumption, transportation mode, physical activity, technology use, etc.
Target Variable: NObeyesdad (Obesity risk categories)
Methodology
1. Data Preprocessing
Data preprocessing is an essential step, involving:

Handling missing values
Feature transformation (encoding categorical features, normalizing numerical data)
Splitting the dataset into training and testing sets
2. Exploratory Data Analysis (EDA)
Visualization techniques are used to understand feature distributions and the relationships between features and obesity risk.

3. Model Training
Four machine learning models (SVM, Random Forest, Decision Tree, XGBoost) are trained on the preprocessed dataset. The performance of each model is evaluated using accuracy, recall, and F1-score metrics.

Results
Best Model: XGBoost classifier
Accuracy: 90.03%
Recall: 90.03%
F1-score: 90.04%
Second Best: Random Forest classifier
Accuracy: 89.91%
Recall: 89.91%
F1-score: 89.91%
Challenges
Data Preprocessing Complexity: Handling a mix of categorical, ordinal, and continuous features posed challenges. A systematic preprocessing pipeline was developed to address this.
Feature Importance: Understanding the relative importance of features was challenging, particularly when using complex models like Random Forest and XGBoost.
Installation and Setup
To run the code in this repository, you need to have Python 3.x and the following packages installed:

bash
Copy code
pip install -r requirements.txt
Usage
After setting up the environment, you can run the code by executing the following command:

bash
Copy code
python obesity_risk_prediction.py
This will train the machine learning models and evaluate their performance.

Future Work
Incorporating additional features like the original obesity dataset could enhance model performance.
Investigating other machine learning models or deep learning techniques to improve prediction accuracy.
Exploring real-time predictions for early intervention and personalized obesity management.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Feel free to modify the README as per your specific needs and project setup!

DevelopersHubAIMLtasks
Task 1
Iris Data Exploration & Visualization Goal: To perform Exploratory Data Analysis (EDA) on a classic multi-class dataset.
Methodology: Loaded data via Seaborn, performed descriptive statistical analysis, and visualized distributions.
Key Findings: Scatter plots confirmed that the Setosa species is easily separable based on petal dimensions, while Versicolor and Virginica have slight overlaps. Box plots identified minor outliers in the sepal width feature.
TASK 2
The objective of this task is to predict the next day’s stock closing price using historical data.
The dataset is collected from Yahoo Finance using the yfinance library, with Apple stock as an example.
Features used for prediction include Open, High, Low, and Volume, while the target variable is the next day’s Close price.
Two machine learning models are applied: Linear Regression and Random Forest Regressor.
Linear Regression is used as a simple baseline model to understand linear relationships in the data.
Random Forest is used to capture more complex and non-linear patterns in stock price movements.
The results show that Random Forest generally performs better than Linear Regression in terms of prediction accuracy.
The model comparison is visualized by plotting actual vs predicted closing prices.
Overall, the predictions are approximate because stock prices are influenced by many unpredictable external factors such as news and market conditions.
TASK 3
Objective
The objective of this task is to build a machine learning model that can predict whether a person is at risk of heart disease based on their medical and lifestyle-related health data.
Dataset
The dataset used is the Heart Disease UCI Dataset, available on Kaggle. It contains patient health information such as age, cholesterol level, blood pressure, chest pain type, resting ECG results, maximum heart rate, and other clinical attributes. The target variable indicates whether the person has heart disease (1) or not (0), making it a binary classification problem.
Models Applied
Two main classification models can be used for this task: Logistic Regression and Decision Tree. Logistic Regression is used as a baseline model for binary classification, while Decision Tree is used to capture non-linear relationships between medical features and heart disease risk. Both models are trained on the cleaned dataset and tested for performance.
📈 Key Results and Findings
The models are evaluated using accuracy, confusion matrix, and ROC-AUC score to measure performance. The Decision Tree model often performs slightly better than Logistic Regression due to its ability to handle complex feature interactions. The confusion matrix helps identify correct and incorrect predictions, while the ROC curve shows how well the model distinguishes between patients with and without heart disease. Feature analysis shows that factors like chest pain type, maximum heart rate, and cholesterol levels are important indicators in predicting heart disease risk.

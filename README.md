🚢 Passenger Survival Prediction using Logistic Regression
📌 Project Overview

This project focuses on predicting whether a passenger survived or not based on various personal and travel-related attributes. Using Logistic Regression, a machine learning classification algorithm, the model analyzes passenger information such as age, gender, ticket class, and fare to estimate the probability of survival.

Passenger survival prediction is a classic binary classification problem widely used in machine learning to understand how different factors influence outcomes.

The project is implemented using Python and Google Colab, following a typical data science workflow.

🎯 Objectives

Analyze passenger dataset and understand key features

Perform data cleaning and preprocessing

Apply Logistic Regression for classification

Evaluate the performance of the model

Predict passenger survival based on given features

📂 Dataset

The dataset contains information about passengers such as:

PassengerId – Unique ID for each passenger

Pclass – Ticket class (1st, 2nd, 3rd)

Name – Passenger name

Sex – Gender of passenger

Age – Age of passenger

SibSp – Number of siblings/spouses aboard

Parch – Number of parents/children aboard

Ticket – Ticket number

Fare – Passenger fare

Cabin – Cabin number

Embarked – Port of embarkation

Target Variable

0 → Passenger did not survive

1 → Passenger survived

⚙️ Technologies Used

Python

Google Colab / Jupyter Notebook

Pandas – Data analysis and manipulation

NumPy – Numerical computation

Matplotlib / Seaborn – Data visualization

Scikit-learn – Machine learning model

🧠 Machine Learning Workflow
1️⃣ Data Loading

Load the dataset using Pandas

Examine dataset structure using:

.head()

.info()

.describe()

2️⃣ Data Preprocessing

Handle missing values

Encode categorical variables (e.g., Gender, Embarked)

Feature selection

Data transformation if required

3️⃣ Exploratory Data Analysis (EDA)

Survival distribution analysis

Relationship between gender, class, age, and survival

Correlation analysis between features

4️⃣ Model Building

The model used in this project:

Logistic Regression

Logistic Regression predicts the probability of a binary outcome (survived or not survived).

5️⃣ Model Training

Split the dataset into training and testing sets

Train the Logistic Regression model using training data

6️⃣ Model Evaluation

Evaluate the model using:

Accuracy Score

Confusion Matrix

Precision

Recall

F1 Score

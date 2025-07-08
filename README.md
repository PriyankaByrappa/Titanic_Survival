🚢 Titanic Survival Prediction using Logistic Regression and Decision Tree
📌 Project Overview
This machine learning project focuses on predicting the survival of Titanic passengers based on features like age, gender, passenger class, fare, and family relations. Two classification algorithms — Logistic Regression and Decision Tree — are applied and evaluated for their performance in identifying whether a passenger survived or not.

The project is developed using Python in Google Colab, featuring data cleaning, preprocessing, data visualization, model training, and performance evaluation.

📁 Dataset
File Name: titanic.csv

Source: Kaggle Titanic Dataset / DataScienceDojo GitHub

Target Variable: Survived (0 = Did not survive, 1 = Survived)

Attributes:
Pclass (Passenger Class)

Sex

Age

SibSp (Siblings/Spouses aboard)

Parch (Parents/Children aboard)

Fare

Embarked (Port of Embarkation)

🔧 Technologies Used
Python 3

Google Colab

Libraries:
pandas

numpy

scikit-learn

matplotlib

seaborn

📈 ML Models Used
1. Logistic Regression
A linear model used for binary classification (Survived or Not Survived).
Evaluated using accuracy score and classification report.

2. Decision Tree Classifier
A non-linear, tree-based model that splits data into decision rules.
Evaluated using accuracy, confusion matrix, and classification report.

🚀 Project Workflow
Import and explore the dataset

Clean and preprocess data (handle missing values, drop unused columns)

Convert categorical features using one-hot encoding

Split data into training and testing sets

Train:

Logistic Regression

Decision Tree Classifier

Evaluate model performance using:

Accuracy score

Confusion matrix

Classification report

Visualize confusion matrix using seaborn

📊 Results
Model	Accuracy
Logistic Regression	~81%
Decision Tree	~82%

Note: Accuracy may vary slightly depending on random state or data split.

📌 How to Run
You can open this project in Google Colab and run all cells interactively.
Ensure the titanic.csv file is uploaded or accessible via the given URL in the notebook.

📷 Sample Outputs
Confusion Matrix
![{B60B166B-6C19-462E-B82D-E26599D88DBB}](https://github.com/user-attachments/assets/66c8379e-2e6d-41f8-9be7-16da5662ae38)

![{E64D8971-E408-4430-99A4-1F6BAAD6CB12}](https://github.com/user-attachments/assets/ca494487-f4a4-4f78-bda1-ec27c20f00fd)

![{1DF3AACA-FB9D-41DC-8A0E-56D071E0133B}](https://github.com/user-attachments/assets/ac660ee5-e4c0-40b4-9cc6-5d01d52ed1cb)



🧾 License
This project was created as part of a Python + Machine Learning internship.
Educational use only.

🙋‍♀️ Author
Priyanka Byrappa B
Intern - Python & Machine Learning

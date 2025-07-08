🚢 Titanic Survival Prediction using Logistic Regression
📌 Project Overview
This machine learning project aims to predict the survival of passengers on the Titanic using logistic regression. It explores relationships between various features such as age, gender, passenger class, fare, and more to build a binary classifier.

The project includes data cleaning, preprocessing, training, and evaluation, along with confusion matrix visualization. It is developed in Python using Google Colab.

📁 Dataset
Name: titanic.csv

Source: Kaggle Titanic Dataset / DataScienceDojo GitHub

Target Variable: Survived (0 = Did not survive, 1 = Survived)

📊 Features Used:
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

📚 Libraries:
pandas

numpy

matplotlib

seaborn

scikit-learn

📈 ML Model
Logistic Regression:
A linear model used for binary classification (Survived or Not Survived).

Evaluated using:

Accuracy score

Confusion matrix

Classification report (precision, recall, F1-score)

🚀 Project Workflow
Import libraries

Load dataset from URL

Drop irrelevant features (Name, Cabin, Ticket, etc.)

Handle missing values (age with median, embarked with mode)

Encode categorical features (Sex, Embarked)

Split dataset into train and test sets

Train logistic regression model

Evaluate model performance

Visualize confusion matrix

📊 Results
Metric	Score
Accuracy	81.0%
Precision (0)	83%
Recall (0)	86%
F1-Score (1)	76%

🔹 Confusion Matrix:
lua
Copy
Edit
              Predicted
             |  0  |  1
           ---------------
Actual  0   | 90  | 15
        1   | 19  | 55
📷 Sample Output

![{BA71650B-D5A0-4AAC-8034-149DCE4508CF}](https://github.com/user-attachments/assets/36be0743-b474-4003-88a8-49e532729e6a)
![{BE2845F1-B802-4316-93BA-A0CB17E2DE91}](https://github.com/user-attachments/assets/904a20f5-1101-4cb5-80c3-4f72b9c4a61d)



📌 How to Run
Open the project notebook in Google Colab

Upload or fetch the Titanic dataset

Run all cells to see preprocessing, training, and evaluation

👉 Notebook Link: Click here to open in Colab
(Replace with actual link)

🧾 License
This project is for educational use only and was created as part of a Python + Machine Learning internship.

🙋‍♀️ Author
Priyanka Byrappa B
Intern – Python & Machine Learning


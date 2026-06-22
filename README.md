# Titanic-Survival-Prediction-System
“Built a Titanic survival prediction model using machine learning and deployed it with Gradio for real-time predictions.”
🚢 Titanic Survival Prediction Model

This project is a machine learning classification model that predicts whether a passenger survived the RMS Titanic disaster based on various features such as age, gender, ticket class, and fare.

🔍 Objective

The goal of this model is to analyze passenger data and predict survival outcomes using supervised machine learning techniques.

📊 Dataset

The dataset typically includes features like:

Passenger class (Pclass)
Gender (Sex)
Age
Fare
Number of siblings/spouses aboard (SibSp)
Number of parents/children aboard (Parch)
Embarked location

Target variable:

Survived (0 = No, 1 = Yes)
⚙️ Process / Workflow
Data Cleaning
Handled missing values (Age, Embarked)
Removed unnecessary columns (Name, Ticket, Cabin)
Feature Engineering
Converted categorical data (Sex, Embarked) into numerical form using encoding techniques
Train-Test Split
Split dataset into training and testing sets
Model Building
Applied classification algorithms (e.g., Logistic Regression, Decision Tree)
Model Evaluation
Evaluated using:
Accuracy
Precision
Recall
F1-score
🤖 Model Output

The model predicts:

Survived
Not Survived
🌐 Deployment

The model is deployed using Gradio, allowing users to input passenger details through a web interface and get real-time predictions.

🎯 Conclusion

This project demonstrates the complete machine learning pipeline, including data preprocessing, model training, evaluation, and deployment, making it a strong example for beginners and interview presentations.

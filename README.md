# titan
First project-Data-Titanic 
# Titanic - Machine Learning from Disaster 🚢

This repository contains my approach to the classic Titanic survival prediction challenge. I achieved an accuracy score of **84.36%** using a Random Forest Classifier.

## 🚀 Overview
The goal of this project is to predict which passengers survived the Titanic shipwreck by analyzing passenger data (ie. name, age, gender, socio-economic class, etc.).

## 🛠️ Key Steps Taken
- **Exploratory Data Analysis (EDA):** Used `Matplotlib` and `Seaborn` to visualize survival rates based on Sex, Class, and Age.
- **Data Cleaning:** Handled missing values for 'Age' and 'Embarked'. Dropped the 'Cabin' column due to excessive missing data.
- **Feature Engineering:** 
    - Used **Regex** to extract titles (Mr, Miss, Mrs, etc.) from names. This proved to be the most important feature for the model.
    - Categorized ages and fares into logical "bins" or groups.
- **Model Training:** Built a `RandomForestClassifier` using `Scikit-Learn`.

## 📊 Performance
- **Model:** Random Forest Classifier
- **Accuracy Score:** 84.36%

## 📂 File Structure
- `titanic_model.py`: The main Python script (written in Sublime Text).
- `resultfile.csv`: Final predictions for the test set.

## 📝 Credits
This project was developed as part of my learning journey in Data Science. Special thanks to the community tutorials on Kaggle for the initial guidance and inspiration. Also GeeksforGeeks for the code.


# Student Adaptability Prediction

This project uses machine learning classification to predict whether students have High or Low adaptability to online learning.

## Project Overview

The dataset contains student-related information such as age, education level, institution type, internet type, device, financial condition, class duration, and other learning-related factors.

The target variable is:

- High adaptability
- Low adaptability

## Machine Learning Models Used

The following models were tested:

- Logistic Regression
- Decision Tree
- K-Nearest Neighbors

Each model was tested using two different configurations.

## Data Preprocessing

The preprocessing steps included:

- Checking missing values
- Checking duplicate rows
- Fixing inconsistent values
- Encoding categorical columns
- Scaling selected features
- Splitting the dataset into training and testing sets

## Results

The best performing model was K-Nearest Neighbors with k = 3.

It achieved the highest accuracy and strongest overall performance compared to the other tested models.

## Files

```text
data/student_adaptability.csv
notebooks/Final_Project.ipynb
src/main.py
requirements.txt
README.md

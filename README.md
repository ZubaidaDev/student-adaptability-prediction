# Student Adaptability Prediction

This project uses machine learning classification to predict whether students have High or Low adaptability to online learning.

## Project Overview

The dataset contains student-related information such as age, education level, institution type, internet type, device, financial condition, class duration, and other learning-related factors.

The target variable is:

* High adaptability
* Low adaptability

## Dataset

The dataset contains categorical student information related to online learning. The main features include:

* Gender
* Age
* Education Level
* Institution Type
* IT Student
* Location
* Load-shedding
* Financial Condition
* Internet Type
* Network Type
* Class Duration
* Self LMS
* Device

The target column is:

* Adaptivity Level

## Machine Learning Models Used

The following machine learning models were tested:

* Logistic Regression
* Decision Tree
* K-Nearest Neighbors

Each model was tested using two different configurations.

## Data Preprocessing

The preprocessing steps included:

* Checking missing values
* Checking duplicate rows
* Fixing inconsistent values
* Encoding categorical columns
* Scaling selected features
* Splitting the dataset into training and testing sets

## Results

The best performing model was K-Nearest Neighbors with k = 3.

It achieved:

* Accuracy: 84.65%
* Precision for Low adaptability: 0.817
* Recall for Low adaptability: 0.792
* F1-score for Low adaptability: 0.804
* Macro F1-score: 0.839

This model gave the strongest overall performance compared to the other tested models.

## Files

```text
data/student_adaptability.csv
notebooks/Final_Project.ipynb
src/main.py
requirements.txt
README.md
.gitignore
```

## How to Run

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the Python file:

```bash
python src/main.py
```

Or open the notebook:

```bash
jupyter notebook notebooks/Final_Project.ipynb
```

## Conclusion

The project shows that machine learning can be used to predict student adaptability to online learning. It can help identify students who may need additional support in online education.

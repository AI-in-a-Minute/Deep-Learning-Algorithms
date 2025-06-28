# Experiment 2

**AIM**

Data pre-processing operations such as outliers and/or inconsistent data value management.

**Dataset**

Titanic – Machine Learning from Disaster

**Dataset Description**
Source: Kaggle – Titanic: Machine Learning from Disaster

Description: Dataset contains details of Titanic passengers to predict survival.

PassengerId- Unique ID for each passenger
Survived- Target (0 = No, 1 = Yes)
Pclass- Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
Name- Passenger name
Sex- Gender
Age- Age
SibSp- Siblings/Spouses aboard
Parch- Parents/Children aboard
Ticket- Ticket number
Fare- Fare paid
Cabin/Deck- Cabin number (many missing values)
Embarked- Port of Embarkation (C, Q, S)

**Tools & Libraries Used**
* Python 3
* Libraries:
    Pandas
    NumPy
    Matplotlib
    Seaborn
    Scikit-learn
    SciPy

**Steps Performed**
1. Dataset Loading
Loaded the Titanic dataset from Kaggle using Pandas.

2. Exploratory Data Analysis (EDA)
Checked for missing values, data types, and dataset summary.

3. Handling Missing Values

Age filled with median.

Embarked filled with mode (most frequent value).

Cabin/Deck dropped due to excessive missing data.

4. Feature Engineering

Created a new column FamilySize = SibSp + Parch.

5. Encoding Categorical Data

Sex encoded using Label Encoding.

Embarked encoded using One-Hot Encoding.

6. Handling Outliers

Used Boxplots, IQR method, Z-Score, and Isolation Forest to detect and manage outliers in Age and Fare.

7. Removing Duplicates

Checked and removed duplicate records.

8. Final Verification

Ensured no missing data and no extreme outliers.

Dataset ready for machine learning models.



This experiment demonstrates the importance of data preprocessing as a fundamental step in building reliable and accurate AI and machine learning models.
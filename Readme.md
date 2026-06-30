# 🚢 Titanic Exploratory Data Analysis (EDA)

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange.svg)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-purple.svg)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the famous Titanic dataset using Python. The notebook demonstrates data cleaning, handling missing values, querying data with Pandas, and creating visualizations to uncover patterns related to passenger survival.

---

## 📂 Dataset

The project uses the **Titanic Dataset**, which contains information about passengers aboard the RMS Titanic.

### Dataset Features

| Feature | Description |
|----------|-------------|
| PassengerId | Unique passenger ID |
| Survived | Survival status (0 = No, 1 = Yes) |
| Pclass | Ticket class (1st, 2nd, 3rd) |
| Name | Passenger name |
| Sex | Gender |
| Age | Passenger age |
| SibSp | Number of siblings/spouses aboard |
| Parch | Number of parents/children aboard |
| Ticket | Ticket number |
| Fare | Ticket fare |
| Cabin | Cabin number |
| Embarked | Port of embarkation (C, Q, S) |

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Google Colab

---

## 📋 Project Workflow

### 1. Data Loading

- Import required libraries
- Load Titanic dataset using Pandas
- Display first rows of the dataset

---

### 2. Data Exploration

Performed:

- Dataset information (`info()`)
- Statistical summary (`describe()`)
- Shape of dataset
- Missing value detection
- Unique values inspection

Examples:

- Average passenger age
- Female passengers
- Male passengers
- First-class passengers
- High fare passengers
- Embarkation ports

---

### 3. Data Cleaning

The following preprocessing steps were performed:

- Removed rows with missing **Embarked** values
- Filled missing **Age** values using the column mean
- Replaced missing **Cabin** values with `"unknown"`
- Reset dataframe index
- Checked for duplicate records
- Saved cleaned dataset

Output:

```
Cleaned_Titanic.csv
```

---

### 4. Data Filtering with Pandas

Various filtering operations were implemented, including:

- Passengers younger than 18
- Passengers older than 60
- Female survivors
- Male passengers in first class
- Passengers who embarked from port C
- Fare greater than average
- Fare greater than 100
- Passengers with no family aboard
- Passengers with title "Dr."
- Passengers without cabin assignment

---

### 5. Exploratory Data Analysis

The notebook answers several analytical questions such as:

- How many passengers survived?
- What is the average passenger age?
- Which gender survived more?
- Which passenger class had the largest population?
- Which embarkation port had the highest number of passengers?
- How does fare relate to age?
- How does survival differ by gender?

---

## 📊 Visualizations

The project includes several visualizations:

### 📌 Survival Count

- Bar Chart
- Number of survivors vs non-survivors

---

### 📌 Passenger Class Distribution

- Pie Chart
- Percentage of passengers in each class

---

### 📌 Embarkation Port Distribution

- Bar Chart
- Passenger counts for:

- Cherbourg (C)
- Queenstown (Q)
- Southampton (S)

---

### 📌 Fare vs Age

- Scatter Plot
- Colored by survival status

---

### 📌 Survival Rate by Gender

- Bar Chart
- Comparison of survival percentages between males and females

---

## 📈 Key Findings

- Most passengers traveled in **3rd class**.
- Females had a significantly higher survival rate than males.
- Missing values mainly existed in the **Age** and **Cabin** columns.
- Most passengers embarked from **Southampton (S)**.
- Higher ticket fares were generally associated with first-class passengers.
- There were no duplicate records in the dataset.

---

## 👨‍💻 Author

**Horia Ahmed**

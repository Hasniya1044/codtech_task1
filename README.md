# 🚀 CODTECH Internship - Task 1: Data Pipeline (ETL)

This repository contains the solution for **Task 1** of the CODTECH Data Science Internship:  
**ETL (Extract, Transform, Load) Pipeline using the Titanic Dataset**.

---

## 📌 Objective

Automate a complete ETL pipeline that:
- **Extracts** data from a CSV file
- **Transforms** it by cleaning, encoding, and scaling
- **Loads** the cleaned data to a new CSV file

---

## 🛠️ Technologies Used

- Python 🐍
- Google Colab / Jupyter Notebook
- Pandas
- Scikit-learn

---

## 📁 Files Included

| File Name              | Description                                   |
|------------------------|-----------------------------------------------|
| `task1_pipeline.ipynb` | Jupyter/Colab notebook containing the ETL code |
| `titanic.csv`          | Input dataset (raw data)                      |
| `titanic_cleaned.csv`  | Output dataset (cleaned and processed)        |

---

## 🔄 ETL Process Breakdown

### ✅ Extract
- Load Titanic dataset (`titanic.csv`) using Pandas

### ✅ Transform
- Fill missing values (`Age`, `Embarked`)
- Drop unnecessary columns (`Cabin`, `Ticket`, `Name`, `PassengerId`)
- Encode categorical columns (`Sex`, `Embarked`) using `LabelEncoder`
- Scale numerical columns (`Age`, `Fare`) using `StandardScaler`

### ✅ Load
- Save the cleaned data to a new file: `titanic_cleaned.csv`

---

## 📸 Sample Output

```text
   Survived  Pclass  Sex  Age  SibSp  Parch  Fare  Embarked
0         0       3    1 -0.53      1      0 -0.502         2
1         1       1    0  0.62      1      0  0.786         0

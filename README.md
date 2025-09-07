# **Titanic-Data-Cleaning-Train-Test**
**Description:**
Performed data cleaning and preprocessing on the Titanic dataset to uncover survival patterns. Analyzed variables like age, gender, class, and embarked port, handling missing values and outliers. Prepared clean datasets for modeling by encoding categorical variables, creating new features, and visualizing survival trends.

---

## **Level 1 – Task 1: Data Cleaning & Preprocessing (Titanic Dataset)**

### 🎯 **Objective**
The goal of this task is to **clean and preprocess** the Titanic dataset by:
- Identifying and handling **missing values**
- Removing **duplicate records**
- Standardizing **categorical formats**
- Preparing both **train.csv** and **test.csv** for further analysis or modeling

---

### 📊 **Dataset**
- Source: [Titanic Dataset – Kaggle](https://www.kaggle.com/c/titanic/data)  
- Files used:  
  - **train.csv** → 891 rows (includes survival outcomes)  
  - **test.csv** → 418 rows (without survival outcomes)  

---

### 🛠 **Cleaning Steps**
#### *1. Missing Values*
- **Train.csv**:  
  - `Age` → filled with median  
  - `Embarked` → filled with mode ("S")  
  - `Cabin` → dropped (too many missing values)  

- **Test.csv**:  
  - `Age` → filled with median  
  - `Fare` → filled with median  
  - `Cabin` → dropped  

---

#### *2. Duplicate Removal*
- Checked for duplicates in both datasets  
- Dropped any duplicate rows to ensure uniqueness  

---

#### *3. Standardization*
- Converted `Sex` to lowercase  
- Standardized `Embarked` codes (uppercase)  
- Converted `Survived` column (train only) to categorical  

---

### ✅ **Final Output**
- Both **train.csv** and **test.csv** are:  
  - Free of missing values (except dropped `Cabin`)  
  - Free of duplicate rows  
  - Formatted consistently for categorical and numeric fields
 
---

## 📂 Project Structure

├── Titanic_EDA.ipynb       # Google Colab Notebook with cleaning, EDA, and insights  
├── data/                   # Folder containing dataset(s)  
│   ├── train.csv           # Training dataset (used for main EDA)  
│   └── test.csv            # Test dataset (used for additional checks/validation)  
├── README.md               # Project documentation

---

### 🔗 Open in Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1dHqGRIMo8SlvjMlopBNz8d40w14WDbDP?authuser=4#scrollTo=w_KHH9K90odB)

LinkedIn Post: [Coming Soon]

Video Walkthrough: [Coming Soon]

---

### 📂 Repository Structure

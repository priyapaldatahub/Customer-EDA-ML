# 📊 Customer EDA & Machine Learning Analysis

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on a customer dataset using Python. The analysis is performed to understand customer purchasing behavior, identify patterns and relationships between different product categories, and generate meaningful insights from the data.

The project demonstrates the complete EDA workflow, including data loading, data understanding, data cleaning, statistical analysis, visualization, correlation analysis, and interpretation of results.

---

## 🎯 Project Objectives

- Understand the structure and characteristics of the dataset
- Perform data cleaning and preprocessing
- Analyze numerical and categorical variables
- Identify customer purchasing patterns
- Analyze spending across different product categories
- Identify relationships between variables
- Detect correlations and potential outliers
- Create meaningful data visualizations
- Generate insights that can support further Machine Learning analysis

---

## 📂 Dataset

The dataset contains **440 customer records and 8 features** related to customer spending and purchasing channels.

### Dataset Features

| Feature | Description |
|---|---|
| Channel | Type of purchasing channel |
| Region | Customer region |
| Fresh | Annual spending on fresh products |
| Milk | Annual spending on milk products |
| Grocery | Annual spending on grocery products |
| Frozen | Annual spending on frozen products |
| Detergents_Paper | Annual spending on detergents and paper products |
| Delicatessen | Annual spending on delicatessen products |

---

## 🛠️ Technologies & Libraries

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

---

## 🔍 EDA Workflow

The project follows these major steps:

### 1. Data Loading
- Imported the required Python libraries
- Loaded the customer dataset using Pandas

### 2. Data Understanding
- Checked dataset shape
- Examined data types
- Viewed sample records
- Analyzed dataset structure

### 3. Data Cleaning
- Checked for missing values
- Checked for duplicate records
- Verified data types
- Prepared the dataset for analysis

### 4. Statistical Analysis
- Generated descriptive statistics
- Analyzed mean, median, standard deviation, minimum and maximum values
- Studied customer spending distributions

### 5. Data Visualization
Created visualizations to understand:

- Customer spending distributions
- Product category spending
- Regional distribution
- Channel-wise customer behavior
- Relationships between variables
- Correlation between product categories

### 6. Correlation Analysis
A correlation analysis was performed to understand relationships between different spending categories and identify strongly related features.

### 7. Insights
The analysis was used to identify important patterns in customer purchasing behavior and understand which product categories contribute most to customer spending.

---

## 📈 Key Analysis Areas

The project focuses on:

- Customer spending behavior
- Product category analysis
- Regional customer analysis
- Channel-wise analysis
- Distribution analysis
- Outlier detection
- Correlation analysis
- Feature relationships

---

## 📁 Project Structure

```text
Customer-EDA-ML/
│
├── data/
│   └── customers.csv
│
├── notebooks/
│   └── Customer_EDA.ipynb
│
├── visuals/
│   └── README.md
│
├── .gitignore
├── README.md
└── requirements.txt

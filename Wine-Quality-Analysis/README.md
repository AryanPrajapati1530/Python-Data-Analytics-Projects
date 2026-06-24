# 🍷 Wine Quality Analysis Using Python

## 📖 Project Overview

This project focuses on the Exploratory Data Analysis (EDA) of the Red Wine Quality Dataset using Python. The objective is to analyze the physicochemical properties of red wine and identify the factors that influence wine quality. The project demonstrates data cleaning, visualization, statistical analysis, and insight generation techniques commonly used in Data Analytics and Data Science.

---

## 🎯 Project Objectives

* Understand the structure and characteristics of the dataset.
* Perform data cleaning and preprocessing.
* Conduct Univariate, Bivariate, and Multivariate Analysis.
* Identify relationships between wine quality and chemical properties.
* Generate meaningful business and analytical insights.
* Develop practical EDA skills using Python.

---

## 📂 Dataset Information

The dataset contains physicochemical properties of red wine samples.

### Features

* Fixed Acidity
* Volatile Acidity
* Citric Acid
* Residual Sugar
* Chlorides
* Free Sulfur Dioxide
* Total Sulfur Dioxide
* Density
* pH
* Sulphates
* Alcohol

### Target Variable

* Quality (Wine Quality Score)

---

## 🛠️ Tools and Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🔍 Data Analysis Workflow

### 1. Data Collection and Loading

* Imported dataset into Jupyter Notebook.
* Examined dataset structure and attributes.

### 2. Data Understanding

* Dataset Shape
* Column Information
* Statistical Summary
* Data Types Analysis

### 3. Data Cleaning

* Missing Value Detection
* Duplicate Record Detection
* Duplicate Removal
* Data Validation

### 4. Exploratory Data Analysis (EDA)

* Univariate Analysis
* Bivariate Analysis
* Multivariate Analysis
* Correlation Analysis

### 5. Visualization

* Count Plot
* Swarm Plot
* Violin Plot
* Box Plot
* Correlation Heatmap
* Bar Plot
* Line Plot

### 6. Business Insight Generation

* Relationship Analysis
* Feature Impact Assessment
* Wine Quality Evaluation

---

# 📊 Univariate Analysis (UD)

Univariate Data Analysis focuses on analyzing a single variable independently.

### Purpose

* Understand distribution of a variable.
* Identify patterns and frequency.
* Detect outliers and unusual values.

### Visualizations Used

* Count Plot of Wine Quality
* Distribution Analysis

### Example

Analysis of the "Quality" variable to understand the frequency distribution of wine ratings.

---

# 📈 Bivariate Analysis (BD)

Bivariate Data Analysis studies the relationship between two variables.

### Purpose

* Identify relationships and trends.
* Measure association between variables.
* Compare variable behavior.

### Visualizations Used

* Swarm Plot
* Violin Plot
* Box Plot

### Example

Relationship between:

* Alcohol vs Quality
* Quality vs pH
* Quality vs Sulphates

### Key Observation

Higher alcohol content tends to be associated with better quality wines.

---

# 📉 Multivariate Analysis (MD)

Multivariate Data Analysis examines relationships among multiple variables simultaneously.

### Purpose

* Discover complex patterns.
* Identify influential variables.
* Understand interactions between features.

### Visualizations Used

* Correlation Heatmap

### Example

Analysis of:

* Alcohol
* Density
* Sulphates
* Volatile Acidity
* pH
* Quality

### Key Observation

Multiple physicochemical properties collectively influence wine quality.

---

## 🧹 Data Cleaning Techniques Applied

* Missing Value Analysis
* Duplicate Record Detection
* Duplicate Record Removal
* Data Validation
* Binary Classification of Quality

### Quality Classification

| Quality Score | Category          |
| ------------- | ----------------- |
| 7 or Above    | Good Wine (1)     |
| Below 7       | Not Good Wine (0) |

---

## 📌 Key Findings

* Alcohol shows a positive relationship with wine quality.
* Volatile acidity negatively impacts quality.
* Quality ratings are concentrated around medium-quality wines.
* Certain chemical properties strongly influence wine quality.
* Correlation analysis helps identify important predictive variables.

---

## 🚀 Additional Insights

Beyond the standard EDA process, additional analysis was conducted to identify:

* Strongest positive correlations.
* Strongest negative correlations.
* Feature importance.
* Outlier detection.
* Quality distribution patterns.
* Alcohol impact on wine quality.

---

## 📁 Project Structure

Wine-Quality-Analysis/

├── Wine_Quality_Analysis.ipynb

├── winequality-red.csv

├── screenshots/

│ ├── quality_distribution.png

│ ├── swarm_plot_quality_alcohol.png

│ ├── violin_plot_quality_alcohol.png

│ ├── boxplot_quality_alcohol.png

│ ├── correlation_heatmap.png

│ └── alcohol_vs_quality.png

└── README.md

---

## 🎓 Learning Outcomes

Through this project, the following concepts were applied:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Statistical Analysis
* Data Visualization
* Correlation Analysis
* Business Insight Generation
* Python for Data Analytics

---

## 👨‍💻 Author

**Aryan Prajapati**

Data Analytics & Data Science Enthusiast





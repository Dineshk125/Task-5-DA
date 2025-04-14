# Task-5-DA

# Titanic Dataset - Exploratory Data Analysis (EDA)

## 📊 Objective
Perform exploratory data analysis on the Titanic dataset to extract insights, visualize patterns, and understand survival factors.

## 🧰 Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- NumPy

## 📁 Dataset Used
- train.csv from the Titanic dataset (Kaggle)

## 🔍 EDA Steps Performed
1. *Data Overview*  
   - Used .info(), .describe(), and .value_counts() to understand the structure and summary of the data.

2. *Missing Values Handling*  
   - Age filled with median  
   - Embarked filled with mode  
   - Cabin filled with "Unknown"

3. *Univariate Analysis*  
   - Histograms and count plots of Sex, Age, Fare, etc.

4. *Bivariate Analysis*  
   - Boxplots and grouped bar charts to explore relationships between features and survival.

5. *Skewed Data Handling*  
   - Applied log transformation to Fare to reduce skewness.

6. *Correlation & Multicollinearity*  
   - Heatmaps and pairplots to detect correlation  
   - Discussed VIF for multicollinearity detection

## 📌 Key Findings
- Female passengers had higher survival rates.
- 1st class passengers were more likely to survive.
- Younger passengers and those who paid higher fares had better survival chances.
- Embarked port 'C' showed higher survival rate.

## 📎 Files Included
- Titanic_EDA.ipynb – Jupyter Notebook with code and visuals
- Titanic_EDA_Report.pdf – PDF summary report of findings
- train.csv – Dataset used

## ✅ Outcome
- Developed deeper understanding of data cleaning, visualization, and interpretation.
- Practiced handling missing values, skewness, and multicollinearity.

---

👨‍💻 *Submitted as part of Data Analyst Internship Task 5: Exploratory Data Analysis*

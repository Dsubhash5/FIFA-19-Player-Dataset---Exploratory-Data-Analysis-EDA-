# ⚽ FIFA 19 Player Dataset - Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs an in-depth **Exploratory Data Analysis (EDA)** on the **FIFA 19 Player Dataset** to uncover patterns in player performance, market value, wages, age, preferred foot, and playing positions.

The project demonstrates the complete data analysis workflow—from data cleaning and feature engineering to statistical analysis and data visualization—using Python.

---

## 🎯 Objectives

* Analyze player demographics and performance.
* Identify factors influencing market value and wages.
* Explore relationships between player attributes.
* Discover positional trends in football.
* Build meaningful visualizations for business insights.

---

## 📊 Dataset Information

* **Dataset:** FIFA 19 Player Dataset
* **Original Records:** 18,207
* **Records After Cleaning:** 17,918
* **Features:** 18 Original + 6 Engineered Features
* **Domain:** Sports Analytics

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

# 🧹 Data Cleaning

The dataset contained missing values in multiple columns.

Cleaning steps performed:

* Filled missing Club values with **"No Club"**
* Filled missing Value using the **Median**
* Filled missing Skill Moves using the **Mode**
* Converted Contract Valid Until to DateTime
* Removed rows with invalid contract dates
* Verified zero duplicate records

After cleaning:

* ✅ No missing values
* ✅ 17,918 records retained

---

# 📈 Exploratory Data Analysis

### Univariate Analysis

* Age Distribution
* Preferred Foot Distribution
* Club Squad Sizes
* Overall Rating Distribution

---

### Bivariate Analysis

* Age vs Overall Rating
* Potential vs Overall Rating
* Overall Rating by Preferred Foot
* Wage by Position

---

### Correlation Analysis

A correlation heatmap was created to understand relationships among numerical variables.

Strong relationships found:

* Value ↔ Release Clause
* Value ↔ Wage
* Overall ↔ Potential
* International Reputation ↔ Wage

---

## ⚙️ Feature Engineering

Created new features including:

* Contract Duration
* Potential Growth
* Age Group
* Wage (Millions)
* Value-to-Wage Ratio
* Rating Category

---

# 📊 Key Insights

### 📌 Player Demographics

* Most players are between **21–28 years** old.
* Average player age is approximately **25 years**.

### 📌 Preferred Foot

* Right-footed players: **76.8%**
* Left-footed players: **23.2%**

### 📌 Player Ratings

* Ratings improve through the mid-to-late twenties.
* Performance gradually declines after age 33.

### 📌 Position Analysis

Highest average ratings:

* LF
* RF
* RAM
* LAM

Highest average wages:

* RF
* LF

### 📌 Financial Analysis

Strong positive correlations:

* Market Value ↔ Release Clause
* Market Value ↔ Wage

Elite players earn exponentially higher wages than average players.

---

## 📈 Visualizations

The project includes:

* Histogram
* Box Plot
* Density Plot
* Pie Chart
* Bar Chart
* Scatter Plot
* Correlation Heatmap
* Pair Plot
* Bubble Chart

---

## 💡 Business Recommendations

* Invest in young players with high potential growth.
* Focus scouting on attacking positions for higher returns.
* Use Value-to-Wage Ratio to identify undervalued talent.
* Consider contract duration during transfer negotiations.
* Include international reputation alongside performance metrics in player valuation.

---

## 🚀 Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Data Visualization
* Correlation Analysis
* Statistical Analysis
* Business Insight Generation
* Python Programming

---
## 👨‍💻 Author

**Dodda Subhash Reddy**

🎓 B.Tech – Artificial Intelligence & Machine Learning

📊 Aspiring Data Analyst

**Skills**

* SQL
* Excel
* Python
* Power BI
* Pandas
* NumPy
* Data Visualization
* Exploratory Data Analysis

---

## ⭐ If you found this project useful

Please ⭐ star this repository if you found it interesting or helpful!

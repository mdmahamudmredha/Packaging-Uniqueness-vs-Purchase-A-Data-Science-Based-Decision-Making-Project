# Packaging-Uniqueness-vs-Purchase-A-Data-Science-Based-Decision-Making-Project

## 📌 Project Overview

This project aims to explore whether the uniqueness of packaging for a Dog Food product influences customer purchase decisions. A survey of 523 respondents was conducted to gather insights on the perceived uniqueness of packaging and the likelihood of purchasing the product based on that packaging.

## 🎯 Problem Statement

A Dog Food Company has introduced a new packaging design. While the marketing and design teams consider it very unique and appealing, the product manager is concerned about its impact on sales, especially due to potential logistics challenges. This project investigates whether there is a statistically significant relationship between packaging uniqueness and purchase intent.

## 🧠 Objective

- Understand if the perceived uniqueness of packaging impacts purchase likelihood.

- Use statistical analysis to support business decision-making.

## 📊 Dataset Description

The dataset contains survey responses with the following columns:

Uniqueness: Categorical values representing how unique the packaging is (Extremely unique, Very unique, Somewhat likely, Not so likely, Not at all likely).

Purchase Likelihood: Categorical values showing the likelihood of purchasing the product based on packaging(Extremely unique, Very unique, Somewhat unique, Not so unique, Not at all unique).

## 🧪 Exploratory Data Analysis (EDA)

Performed several EDA steps including:

- Checked for missing values and confirmed dataset cleanliness.

- Value counts for both Uniqueness and Purchase Likelihood variables.

- Created a contingency table (cross-tabulation) to explore the distribution.

- Visualized relationships using heatmaps (annotated) for better understanding.

- Bar plots to show the frequency of each category in both variables.

- Clustered bar chart to compare Uniqueness with Purchase Likelihood directly.

- Countplots to observe how each uniqueness level affects purchase intent.

- Analyzed dominant combinations of values in the crosstab.

- Observed trends/patterns in customer preferences visually.

- Prepared the data for statistical testing (Chi-square assumptions checked).


### 📈 Statistical Test
- **Chi-Square Test of Independence**
    - Why this test?
        - Since both variables (`Uniqueness` and `Purchase Likelihood`) are categorical, the Chi-Square Test of Independence is appropriate to assess whether an association exists between them.
        - This test helps determine if the distribution of purchase likelihood depends on packaging uniqueness.
    - Hypotheses:
        - H0: Packaging uniqueness and purchase likelihood are independent.
        - H1: There is a relationship between packaging uniqueness and purchase likelihood.
    - Test result showed a **p-value of 0.000**, which is less than the significance level of 0.05.
    - ✅ Conclusion: Reject the null hypothesis. There is a statistically significant relationship between packaging uniqueness and the likelihood of purchase.

## 🛠 Technologies Used
- Python (Pandas, Seaborn, Matplotlib, Scipy)
- Jupyter Notebook

## 🔍 Key Findings
- There is a [significant/insignificant] association between packaging uniqueness and likelihood to purchase.
- This insight can help the product team decide whether to move forward with the new packaging.

## 📚 Learnings
- Real-world application of Chi-Square test.
- Hands-on with survey-based analysis.
- Data visualization for categorical variables.

## 💼 Use Case
This project can be used as a reference for:
- A/B testing projects
- Marketing analytics
- Product management decisions

Packaging Uniqueness vs Purchase
├── [Packaging Uniqueness vs Purchase.ipynb](https://github.com/mdmahamudmredha/Packaging-Uniqueness-vs-Purchase-A-Data-Science-Based-Decision-Making-Project/blob/main/Packaging%20Uniqueness%20vs%20Purchase%20%E2%80%93%20A%20Data%20Science%20Based%20Decision%20Making%20Project.ipynb)
├── [README.md]()
├── [survey_data.csv](https://github.com/mdmahamudmredha/Packaging-Uniqueness-vs-Purchase-A-Data-Science-Based-Decision-Making-Project/blob/main/Case%201%20-%20Chi-square%20test%20of%20independence.xlsx)

## 🚀 How to Run
1. Clone the repository.
2. Open the notebook in Jupyter.
3. Run all cells to see the results and visualizations.

## 🤝 Contact
Made by Md. Mahamud Mredha – feel free to connect:
- LinkedIn: https://www.linkedin.com/in/md-mahamud-mredha-294046208/
- GitHub: https://github.com/mdmahamudmredha
- YouTube: [![YouTube](https://img.shields.io/badge/YouTube-Dropout_Programmer-red?style=for-the-badge&logo=youtube)](https://www.youtube.com/@DropoutProgrammer)

---

> "Data is the new oil. Insight is the new currency."



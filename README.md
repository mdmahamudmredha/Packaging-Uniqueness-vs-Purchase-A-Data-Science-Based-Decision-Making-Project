# Packaging Appeal vs. Purchase Behavior: A Data Science-Based Decision-Making Project

## 🎥 Video Walkthroughs**:  
- 🎓 **Full Code + Concept Explanation (For Learners)**: [Watch Here](https://youtu.be/vqXt1wZuaIk?si=byCFR5mYxtwTQQOV)  
- 🧠 **Non-Technical Output Summary (For Recruiters)**: [Watch Here](https://youtu.be/link_to_recruiter_friendly_video) 

## 📌 Project Overview

This project aims to explore whether the uniqueness of packaging for a Dog Food product influences customer purchase decisions. A survey of 523 respondents was conducted to gather insights on the perceived uniqueness of packaging and the likelihood of purchasing the product based on that packaging.

## 🎯 Problem Statement

A Dog Food Company has introduced a new packaging design. While the marketing and design teams consider it very unique and appealing, the product manager is concerned about its impact on sales, especially due to potential logistics challenges. This project investigates whether there is a statistically significant relationship between packaging uniqueness and purchase intent.

## 🧠 Objective

- Understand if the perceived uniqueness of packaging impacts purchase likelihood.
- Use statistical analysis to support business decision-making.

## 📊 Dataset Description

The dataset contains survey responses with the following columns:

- `Uniqueness`: Categorical values representing how unique the packaging is (e.g., Extremely unique, Very unique, etc.).
- `Purchase Likelihood`: Categorical values showing the likelihood of purchasing the product based on packaging.

## 🧪 Exploratory Data Analysis (EDA)

Performed several EDA steps including:

1. Checked for missing values and confirmed dataset cleanliness.
2. Value counts for both `Uniqueness` and `Purchase Likelihood` variables.
3. Created a contingency table (cross-tabulation) to explore the distribution.
4. Visualized relationships using heatmaps (annotated) for better understanding.
5. Bar plots to show the frequency of each category in both variables.
6. Clustered bar chart to compare `Uniqueness` with `Purchase Likelihood` directly.
7. Countplots to observe how each uniqueness level affects purchase intent.
8. Analyzed dominant combinations of values in the crosstab.
9. Observed trends/patterns in customer preferences visually.
10. Prepared the data for statistical testing (Chi-square assumptions checked).

## 📈 Statistical Test

- **Chi-Square Test of Independence**
  - Why this test?
    - Since both variables (`Uniqueness` and `Purchase Likelihood`) are categorical, the Chi-Square Test of Independence is appropriate to assess whether an association exists between them.
    - This test helps determine if the distribution of purchase likelihood depends on packaging uniqueness.
  - Hypotheses:
    - H0: Packaging uniqueness and purchase likelihood are independent.
    - H1: There is a relationship between packaging uniqueness and purchase likelihood.
  - Test result showed a **p-value of 0.1641**, which is greater than the significance level of 0.05.
  - ❌ Conclusion: We fail to reject the null hypothesis. There is **no statistically significant relationship** between packaging uniqueness and the likelihood of purchase.

## 🛠 Technologies Used

- Python (Pandas, Seaborn, Matplotlib, Scipy)
- Jupyter Notebook

## 🔍 Key Findings

- The Chi-Square test result indicates that there is no statistically significant association between packaging uniqueness and likelihood to purchase at a 0.05 significance level.
- The business decision should consider that although the design may feel unique, it may not alone drive customer purchasing behavior significantly.

## 📚 Learnings

- Real-world application of Chi-Square test.
- Hands-on with survey-based analysis.
- Data visualization for categorical variables.
- Understood how to derive actionable business insights from statistical outcomes.

## 🧾 Conclusion & Business Recommendation

- The p-value (0.1641) exceeds the pre-established alpha of 0.05.
- This leads us **not to reject the null hypothesis** — suggesting **no significant link** between the product packaging's distinctiveness and the likelihood of consumers purchasing it at a significance level of 0.05.
- **Business Insight**: While the new packaging may appear visually unique, it does not statistically influence purchase intent.
- **Recommendation**: The company may consider reallocating budget from design innovation to other marketing levers such as pricing, promotions, or product quality improvements.

## 💼 Use Case

This project can be used as a reference for:

- A/B testing projects
- Marketing analytics
- Product management decisions

## 📁 Project Structure

```
Packaging Uniqueness vs Purchase
├── Packaging Uniqueness vs Purchase.ipynb
├── README.md
├── survey_data.csv (if applicable)
```

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



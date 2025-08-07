# 🛍️ Walmart Customer Purchase Behavior Analysis – CLT & Confidence Intervals

A statistical deep-dive into Walmart's Black Friday sales data using **Central Limit Theorem (CLT)** and **Confidence Intervals (CI)** to analyze customer behavior, purchase trends, and gender-based purchase differences.

---

## 📌 Table of Contents

1. [Project Overview](#project-overview)  
2. [Business Problem](#business-problem)  
3. [Dataset](#dataset)  
4. [Methodology](#methodology)  
5. [Statistical Analysis](#statistical-analysis)  
6. [Key Findings](#key-findings)  
7. [Tools & Libraries Used](#tools--libraries-used)  
8. [Conclusion](#conclusion)

---

## 🧠 Project Overview

In this analysis, we use real Walmart sales data to investigate **customer purchase patterns** using core statistical tools. The focus lies on:
- Understanding population behavior via **sampling distributions**
- Applying **Central Limit Theorem** for generalization
- Calculating **confidence intervals** to estimate true average purchase values
- Investigating **gender-based purchase differences**

---

## ❓ Business Problem

Walmart wants to:
- Understand average customer purchase behavior
- Identify if there’s a **significant difference in average purchases by gender**
- Use statistical tools (like CLT & CI) to make business decisions without surveying the entire population

---

## 📂 Dataset

The dataset contains anonymized customer and transaction data from a Black Friday sales event.

### Key Columns:
| Column | Description |
|--------|-------------|
| `User_ID` | Unique customer ID |
| `Gender` | M / F |
| `Age` | Customer age range |
| `City_Category` | Tier of the city (A/B/C) |
| `Stay_In_Current_City_Years` | Years in current city |
| `Product_Category` | Product category |
| `Purchase` | Purchase amount in ₹ |

---

## 🧪 Methodology

1. **Data Cleaning**
   - Removed duplicates & nulls
   - Focused on numeric + categorical features

2. **Sampling & CLT Demonstration**
   - Created repeated samples from population
   - Compared sample means vs population mean

3. **Confidence Interval Construction**
   - Calculated 95% CI for overall purchase mean
   - Constructed CI for male vs female separately

4. **Comparison & Inference**
   - Interpreted overlapping CIs
   - Discussed real-world implications for marketing

---

## 📈 Statistical Analysis

### 🧮 Central Limit Theorem (CLT)
- Demonstrated how the **distribution of sample means** approximates a normal distribution as sample size increases
- Validated with histograms and mean comparisons

### 📏 Confidence Interval (CI)
- 95% Confidence Intervals for:
  - Overall purchase mean
  - Male purchase mean
  - Female purchase mean
- Interpretation of overlap in CIs to assess if there’s a **statistically significant gender difference**

---

## 📊 Key Findings

| Insight | Description |
|--------|-------------|
| 📉 Population mean is stable | Sample means from different sizes (~1000) consistently center around population mean |
| 🚻 No strong gender difference | Male vs female confidence intervals overlap significantly |
| 📐 CLT Validated | Sample means are normally distributed, even if population isn’t |
| 💼 Practical Use | Business can confidently estimate average purchase amount with 95% certainty without surveying everyone |

---

## 🧰 Tools & Libraries Used

- Python 3
- NumPy
- Pandas
- Matplotlib / Seaborn
- SciPy (for stats)
- Jupyter Notebook

---

## ✅ Conclusion

By applying **statistical inference**, we showed that:
- Sample-based decision-making is powerful and reliable
- Confidence Intervals offer business-friendly interpretation of uncertainty
- No significant gender-based difference in purchase amounts was found, helping avoid biased marketing strategies

This notebook exemplifies how **foundational statistics** like **CLT & CI** can guide **data-driven decisions** for large retail businesses like Walmart.

---


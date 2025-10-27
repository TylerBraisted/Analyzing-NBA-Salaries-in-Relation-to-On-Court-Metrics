# 🏀 Valuing Performance: Analyzing NBA Salaries vs. On-Court Metrics

A data-driven exploration into how well NBA player salaries align with performance — using real 2023 season data.

### By: **Tyler Braisted**

---

## 📌 Overview

NBA players earn some of the highest salaries in professional sports — but **are teams truly paying for performance?**  
This project analyzes **player salaries vs. key performance metrics** to uncover which players deliver the greatest value and whether high salaries correlate with high impact.

Using a dataset of **2023 NBA player statistics and salary data**, this analysis:

- Cleans and preprocesses NBA salary + performance data  
- Explores statistical relationships between salary and player impact  
- Visualizes trends using plots and distributions  
- Performs hypothesis testing and linear regression to quantify correlations  

---

## 🔍 Key Questions Explored

- Do the highest-paid players produce the strongest on-court results?
- Which performance metrics best explain salary differences?
- Are there **undervalued** or **overpaid** players?
- How strong is the correlation between salary and:
  - **Points Per Game (PTS)**
  - **Player Efficiency Rating (PER)**
  - **Win Shares (WS)**

---

## 📂 Project Structure

| Section | Description |
|--------|--------------|
| **Data Collection & Cleaning** | Importing, inspecting, formatting, and preparing dataset for analysis |
| **Exploratory Data Analysis (EDA)** | Visualizations, distributions, and descriptive statistics |
| **Statistical Modeling** | Linear regression and model diagnostics |
| **Hypothesis Testing** | Pearson correlations + p-value analysis |
| **Insights & Conclusions** | Key takeaways on player value vs. salary |

---

## 🧠 Tools & Technologies

- **Python**
- Pandas  
- NumPy  
- Matplotlib & Seaborn  
- Statsmodels  
- SciPy  

---

## 📈 Core Findings

✔️ **Strong statistical relationship exists** between player salary and:  
- **PER** (efficiency)  
- **PTS** (scoring output)  
- **Win Shares** (impact on winning)

📊 All three metrics had **p-values < 0.05**, leading to rejection of the null hypothesis — meaning performance and salary *are* significantly correlated.

💡 **Conclusion:**  
NBA teams *do* generally pay for performance — with efficiency and winning impact valued heavily, not just scoring.

---

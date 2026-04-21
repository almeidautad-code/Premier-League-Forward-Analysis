# 📊 Premier League — Statistical Analysis & Dashboard

## 📌 Overview
This project performs a **statistical analysis** of Premier League teams and forwards using **Z-scores and T-scores** to normalize and compare performance across key metrics. It includes a **Forward Profile Comparison Dashboard** and a **Team Stats Chart** built in Excel, allowing objective evaluation of both players and clubs.

---

## 📁 Files

### 1️⃣ Team Charts & Database
📥 [**Download — Microsoft Excel (charts and graphs) database.xlsx**](https://github.com/user-attachments/files/26937879/Microsoft.Excel.charts.and.graphs._database.xlsx)

<img width="1055" height="612" alt="Premier League Team Charts" src="https://github.com/user-attachments/assets/1489329f-39a1-48d2-af12-5409db299342" />

Visual analysis of **Goals vs xG** for all Premier League clubs, presented through an Excel scatter plot with club badges.

**📊 Key Conclusions:**

- 🏆 **Manchester City** stand out as clear outliers — highest goals (94) and highest xG (79), confirming their dominance both in chance creation and finishing
- 🎯 **Arsenal** had a high xG (72) but scored fewer goals (88 vs City's 94), suggesting slightly less clinical finishing despite creating similar quality chances
- ⚽ **Manchester United** show an interesting pattern — high xG (67.7) but only 58 goals, indicating they **underperformed** their expected goals significantly
- 📈 **Tottenham** had 57 xG but scored 70 goals — a case of **overperforming** their xG, likely due to individual brilliance (Harry Kane)
- 📉 **Chelsea and Everton** sit in the lower half despite being big clubs, reflecting their poor attacking seasons
- 🐺 **Wolves** were the least threatening team — lowest goals and lowest xG, showing a very defensive and passive style

---

### 2️⃣ Forward Statistical Analysis & Dashboard
📥 [**Download — Dashboard João Almeida.xlsx**](https://github.com/user-attachments/files/26933147/Dashboard.Joao.Almeida.xlsx)

<img width="867" height="682" alt="Premier League Forward Analysis Dashboard" src="https://github.com/user-attachments/assets/098a9a4f-2e54-4c00-9ced-0672181df874" />

Statistical analysis of Premier League forwards using Z-scores and T-scores, with a final comparison dashboard.

The workbook contains **3 sheets:**
- **Folha1** — Raw Premier League forward statistics
- **Folha2** — Z-score and T-score statistical normalization
- **Dashboard Final** — Forward profile comparison dashboard

---

## 🔍 Key Features
- 📋 Raw dataset of **Premier League forwards and teams**
- 📐 **Z-score normalization** to standardize player metrics
- 📊 **T-score conversion** for easier comparison across different scales
- 🎯 **Forward Profile Comparison Dashboard**
- 📈 **Team performance charts** (goals vs xG)
- ⚽ Covers key metrics: minutes played, goals, xG, shots, shots on target

---

## 📊 Metrics Analyzed

| Metric | Description |
|--------|-------------|
| MP | Matches played |
| Min | Minutes played |
| Gls | Goals scored |
| xG | Expected goals |
| Shots | Total shots |
| Shots on Target | Shots on target |

---

## 🧮 Methodology
1. **Data Collection** — Premier League statistics sourced and compiled
2. **Z-score Normalization** — Each metric standardized relative to the mean and standard deviation
3. **T-score Conversion** — Z-scores converted to T-scores (mean=50, SD=10) for easier interpretation
4. **Dashboard** — Final scores visualized in a comparison dashboard

> A T-score above 50 means the player performs **above average** in that metric. Below 50 means **below average**.

---

## 💡 Key Insights
This analysis helps to:
- Compare forwards on a **level playing field** regardless of minutes played
- Identify **elite performers** vs average players statistically
- Analyze **team tendencies** in chance creation and finishing efficiency
- Support **scouting decisions** with objective data

---

## 📌 Future Improvements
- [ ] Add more positions (midfielders, defenders)
- [ ] Include more seasons for trend analysis
- [ ] Add weighted composite score for overall rating
- [ ] Build an interactive Power BI version
- [ ] Include defensive and creative metrics (xA, key passes)

---

## 🛠️ Tools & Technologies
- Microsoft Excel
- Statistical Analysis (Z-scores, T-scores)
- Data Visualization (Excel Charts & Dashboard)
- Data sourced from **FBref / Premier League statistics**

---

## 👤 Author
**João Almeida** — Data Analytics Portfolio
[LinkedIn](https://www.linkedin.com/in/joaoalmeida96/) • [GitHub](https://github.com/almeidautad-code)

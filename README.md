# 🏀 NBA Payroll Efficiency & ROI Analysis

An end-to-end data analytics project exploring how efficiently NBA teams convert payroll spending into on-court performance.

This project investigates whether higher financial investment leads to better results and identifies teams that consistently outperform their payroll using exploratory data analysis and feature engineering.

---

# 📊 Project Overview

NBA franchises spend hundreds of millions on player salaries, but spending more does not always guarantee winning more.

This project analyses the relationship between **team payroll and performance** across more than two decades of NBA history (1996–2019).

Key analytical metrics include:

- Cost per Win
- Team Return on Investment (ROI)
- Positional ROI
- Experience based ROI

---

# 🎯 Key Research Questions

• How has the **cost of a regular season win** changed over time?

• Do **higher payroll teams consistently win more games**?

• Which franchises generate the **highest return on investment (ROI)**?

• Are certain **player positions more financially efficient**?

• Do **rookie contracts generate better value than veteran salaries**?

---

# 🗂 Data Sources

This project integrates six datasets:

| Dataset | Description |
|------|-------------|
| Boxscore | Player game-level statistics |
| Games | Match results and schedules |
| Play-by-Play | Detailed in-game event data |
| Coaches | Season-level coaching records |
| Player Info | Player demographics and positions |
| Salaries | Player salary data |

Dataset scale:

- **741k+ player game records**
- **13M+ play-by-play events**
- **11k+ salary records**

---

# ⚙️ Data Processing Pipeline

### Data Cleaning

- Converted string-based statistics to numeric values
- Standardised column names
- Handled missing values
- Parsed datetime and season fields

### Data Integration

Multiple datasets were merged to create analytical tables:

- Game-level dataset
- Player-season dataset
- Team-season dataset

### Feature Engineering

Key metrics created:

| Metric | Formula |
|------|------|
| Cost per Win | Payroll ÷ Wins |
| Team ROI | Plus-minus ÷ Payroll |
| Player ROI | Player plus-minus ÷ Salary |

Additional engineered features include:

- Player experience levels
- Position-based ROI
- Era-based performance comparisons

---

# 📈 Exploratory Data Analysis

Visualisations used in the project include:

- Cost per win over time
- Payroll vs wins relationship
- Best ROI teams by season
- Team ROI over time
- Positional value across NBA eras
- ROI by player experience

---

# 🧰 Tools & Technologies

Python  
Pandas  
NumPy  
Plotnine  
Jupyter Notebook  
Data Visualisation  

---

# 🔍 Key Insights

- The **cost of a regular season win more than doubled** between 1996 and 2019.
- Higher payroll does **not guarantee higher win totals**.
- Some franchises consistently **outperform their payroll spending**.
- **Rookie contract players often deliver the highest ROI**.
- Positional value shifts significantly across different NBA eras.

---

# 📁 Repository Structure

```
nba-payroll-roi-analysis
│
├── notebooks
│   └── nba_analysis.ipynb
│
├── report
│   └── NBA_GAME_Exploratory_Data_Analysis.pdf
│
├── images
│   └── visualisations
│
├── requirements.txt
└── README.md
```

---

# 🚀 Future Improvements

Potential extensions:

- Playoff performance analysis
- Predictive modelling for team success
- Injury impact modelling
- Salary efficiency forecasting

---

# 👨‍💻 Author

**Shahmir Ayub**

MSc Applied Data Science (Distinction)  
Data Analyst | SQL | Python | Power BI | Machine Learning

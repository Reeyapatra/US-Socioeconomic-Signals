# US-Socioeconomic-Signals
End-to-end data platform analyzing income, inflation, expenditure, unemployment, and crime trends across U.S. states (2012–2022) using Python and machine learning.

---

## Project Summary
US-Socioeconomic-Signals is a comprehensive data analytics and modeling platform designed to study how income, inflation, unemployment, and consumer expenditure influence crime patterns across U.S. states.

By integrating large-scale economic and crime datasets, this project delivers actionable insights to support policy evaluation, economic planning, and social impact assessment.

Developed for IST652 – Scripting for Data Analysis.

---

## Research & Business Objectives
- Examine relationships between income levels and crime rates
- Evaluate the impact of inflation on household and government spending
- Analyze unemployment-driven economic stress
- Identify high-risk regions through clustering techniques
- Provide evidence-based recommendations for policymakers

---

## Data Sources
| Category | Source | Format |
|----------|--------|--------|
| Income & GDP | Bureau of Economic Analysis (BEA) | CSV |
| Inflation & RPPS | BEA | CSV |
| Expenditure | BEA | CSV |
| Crime Statistics | FBI Crime Data Explorer API | JSON |

All datasets were standardized and merged at the State-Year level (2012–2022).

---

## Technology Stack

### Programming & Analytics
- Python
- Pandas, NumPy
- Scikit-learn
- Statsmodels

### Visualization
- Matplotlib
- Seaborn
- Plotly

### Data Engineering
- REST API Integration
- Automated Cleaning Pipelines
- Feature Engineering
- Dataset Harmonization

---

## Data Processing Workflow

1. Collected structured and semi-structured datasets
2. Removed inconsistencies and standardized state identifiers
3. Filtered relevant economic indicators
4. Adjusted expenditure values using inflation indices
5. Engineered analytical features
6. Integrated multi-source datasets
7. Validated data quality and completeness

**Final Dataset Characteristics**
- 561+ observations
- 51 regions (50 states + D.C.)
- 11-year coverage
- 14+ socioeconomic indicators

---

## Analytical Methods

### Statistical Modeling
- Correlation Analysis
- Ordinary Least Squares (OLS) Regression
- Hypothesis Testing

### Machine Learning
- K-Means Clustering
- Principal Component Analysis (PCA)

### Visual Analytics
- Time-Series Trends
- State-Level Heatmaps
- Choropleth Maps
- Interactive Dashboards

---

## Key Findings

- Lower-income states consistently exhibited higher crime vulnerability
- Inflation significantly increased real spending pressure
- Unemployment strongly correlated with economic instability
- High-income states maintained more stable crime trends
- Post-2020 disruptions reflected pandemic-driven volatility
---

**Regional Patterns**
- California, New York: High income, high cost of living, controlled crime
- Alabama, Mississippi: Lower income, elevated vulnerability

---

## How to Run

### Step 1: Clone Repository
git clone https://github.com/Reeyapatra/US-Socioeconomic-Signals.git

### Step 2: Install Dependencies
pip install pandas numpy matplotlib seaborn plotly scikit-learn statsmodels requests jupyter

### Step 3: Launch Notebook
jupyter notebook notebooks/IST652_FinalProject_Group1.ipynb

---

## 💡 Practical Impact
This platform supports:
- Economic vulnerability assessment
- Crime prevention strategy development
- Inflation risk evaluation
- Workforce policy planning
- Data-informed public investment
- Evidence-based policy formulation
---

## 👥 Project Team
- Jill Karia
- Shivani Pandeti
- Reeya Tapan Patra

---


## 🙏 Acknowledgments
- Bureau of Economic Analysis (BEA)
- FBI Crime Data Explorer
- Syracuse University iSchool

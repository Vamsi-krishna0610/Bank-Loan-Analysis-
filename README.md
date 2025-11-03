# 📊 Bank Loan Data Analysis (Python + Excel)

## 🔍 Overview
This project performs **data analysis on bank loan records** to understand borrower behavior, loan performance, and default risk patterns.  
Using **Python (Jupyter Notebook)** and **Excel**, it explores financial indicators, visualizes key metrics, and extracts insights that support data-driven lending decisions.

---

## 🧠 Objectives

- Clean, process, and analyze loan-related data.  
- Explore borrower demographics and repayment trends.  
- Identify correlations between financial metrics and loan status.  
- Generate visual insights to support portfolio risk assessment.  

---

## 🧰 Tools & Technologies

| Category | Tools Used |
|-----------|-------------|
| Programming | Python (Jupyter Notebook) |
| Libraries | Pandas, NumPy, Matplotlib, Seaborn |
| Data Source | Excel (`financial_loan_data_excel.xlsx`) |
| Visualization | Matplotlib, Seaborn |
| Environment | Jupyter Notebook / VS Code |

---

## 📁 Project Structure

```
📦 Bank-Loan-Data-Analysis/
├── Bank Loan Data (1).ipynb
├── financial_loan_data_excel.xlsx
├── README.md
├── requirements.txt
└── outputs/
```

---

## 🧹 Data Preparation Steps

1. Imported dataset from Excel using `pandas.read_excel()`.  
2. Validated column datatypes and handled missing values.  
3. Standardized numeric formats (interest rate, loan amount).  
4. Encoded categorical variables where necessary.  
5. Ensured consistency between Excel and Python outputs.

---

## 📈 Exploratory Data Analysis (EDA)

### 1. Portfolio Overview
- Total number of loans, approval vs. rejection rates.  
- Distribution by loan type, purpose, and credit grade.  

### 2. Borrower Demographics
- Relationship between income, employment, and loan performance.  
- Impact of debt-to-income ratio on repayment behavior.  

### 3. Risk Metrics
- Correlation analysis to identify key variables affecting default risk.  
- Visual heatmaps and scatterplots to highlight insights.  

---

## 📊 Visualizations

- Loan Status Breakdown (Pie Chart)  
- Interest Rate vs Loan Amount (Scatter Plot)  
- Heatmap of Correlations  
- Loan Purpose Distribution (Bar Chart)  
- Year-wise Loan Issuance Trend  

---

## 💡 Key Insights

- Higher income correlates with lower default probability.  
- Shorter employment tenure increases charge-off likelihood.  
- Grade “C” loans show balanced risk and strong returns.  
- Debt-to-income ratio and loan purpose are strong risk indicators.

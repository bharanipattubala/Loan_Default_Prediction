# 💰 Loan Default Prediction
### End-to-End Finance Analytics | SQL • Python • ML • Power BI

---

## 📌 The Business Problem

Banks and fintech companies lose crores every year because
of loan defaults. The challenge is identifying HIGH-RISK
applicants BEFORE the loan is approved.

This project builds a complete risk analytics solution
using real lending data — predicting which applicants
will default and giving bank management clear,
actionable risk recommendations.

---

## 🎯 Project Highlights

| What | Result |
|------|--------|
| Dataset | 9,578 real loan records |
| Best Model | Gradient Boosting — 85%+ accuracy |
| Tools | Python · SQL · Power BI · Scikit-learn |
| Domain | Finance / Fintech / Banking |
| Output | 3-page interactive Power BI Risk Dashboard |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python (Pandas, NumPy) | Data cleaning & wrangling |
| Seaborn & Matplotlib | EDA charts & visualizations |
| SQL (SQLite) | Data extraction & aggregation |
| Scikit-learn | ML model training & evaluation |
| Power BI | Interactive 3-page risk dashboard |
| Google Colab | Cloud development environment |

---


---

## 📊 Dataset

- Source: Lending Club Loan Dataset — Kaggle
- Records: 9,578 loan applications
- Features: 14 columns — FICO score, interest rate,
  loan purpose, installment, credit policy, income
- Target: Loan defaulted (Yes/No)

---

## 🔍 Key Findings

**Finding 1 — FICO Score is the strongest predictor**
Applicants with FICO below 650 default at 3x the
rate of applicants above 700.

**Finding 2 — Interest rate directly drives default**
Loans with interest rate above 15% show dramatically
higher default probability across all loan purposes.

**Finding 3 — Small business loans are riskiest**
Small business and debt consolidation loans have the
highest default rates — extra verification needed.

**Finding 4 — Credit policy compliance matters**
Non-compliant applicants default at 2x the rate of
policy-compliant applicants.

**Finding 5 — High installment = high risk**
Monthly installments above ₹500 show significantly
higher default probability regardless of purpose.

---

## 🤖 Model Performance

| Model | Accuracy | AUC Score |
|-------|---------|-----------|
| Logistic Regression | 83% | 0.67 |
| Random Forest | 84% | 0.71 |
| Gradient Boosting | 85% | 0.73 |

**Winner: Gradient Boosting with highest AUC score**

---

## 📊 Power BI Dashboard

**Page 1 — Executive Finance Overview**
Total loans, default rate KPI, avg FICO score,
default by purpose bar chart, paid vs defaulted donut.

**Page 2 — Risk Analysis**
FICO vs interest rate scatter, interest by purpose,
department slicers for drill-down analysis.

**Page 3 — Insights & Recommendations**
FICO band vs default line chart, 5 business
recommendations for loan approval team.

---

## 💡 Business Recommendations

1. Reject applications with FICO below 650 — 3x higher
   default rate than average applicants

2. Cap interest rates at 15% maximum — above this
   threshold default probability rises sharply

3. Flag small business and debt consolidation loans
   for additional verification before approval

4. Enforce mandatory credit policy compliance check —
   non-compliant applications default at 2x the rate

5. Build a real-time Risk Score dashboard for loan
   officers combining FICO + interest rate + purpose
   to predict 85% of defaults before they happen

---

## 👩‍💻 About Me

**Bharani Pattubala** — Aspiring Data Analyst
B.Tech CSE 2026 | Bangalore, India
Open to: Data Analyst · MIS Analyst · BI Analyst · Risk Analyst

📩 pattubalabharani@gmail.com
🔗 linkedin.com/in/bharani-pattubala

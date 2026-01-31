# 🏦 Banking Dashboard - End-to-End Data Analysis Project

This project focuses on building an interactive **Banking Dashboard** using Power BI. It involves the complete data analysis lifecycle — from data cleaning and transformation to exploratory data analysis (EDA) and visualization.

---

## 📌 Project Workflow

Data ➡️ MySQL ➡️ Data Cleaning & Preparation ➡️ EDA ➡️ Power BI Dashboard

---

## 📊 Dataset Information

- **Number of columns**: 24
- **Stored in**: MySQL

---

## 🔧 Steps Involved

### 1. Data Cleaning & Preparation

- Categorized `Income` into bands:
  - `Low`
  - `Mid`
  - `High`
- Standardized gender, nationality, and other categorical variables.
- Used conditional columns in Power BI to create income bands.
- Replaced branch codes (`'1'`, `'2'`, etc.) with readable branch names.
- Mapped gender codes:
  - `'1'` → `Male`
  - `'2'` → `Female`

---

### 2. Exploratory Data Analysis (EDA)

- Categorical analysis on:
  - Gender
  - Nationality
- Numerical analysis on:
  - Credit Card Balance
  - Bank Loans
  - Bank Deposits
  - Checking Account
  - Saving Account
  - Estimated Income
  - Superannuation Savings

---

### 3. Key Insights from EDA

- Strong positive correlation between:
  - `Bank Deposits`, `Checking Account`, `Saving Account`, and `Foreign Currency Account`.
- Customers with high balance in one account type tend to hold substantial funds in other accounts as well.

---

## 📈 Dashboard Pages (Power BI)

1. **Home**
2. **Loan Analysis**
3. **Deposit Analysis**
4. **Summary**

---

## 🚀 Tools & Technologies

- **Database**: MySQL
- **Exploratory Data Analysis(EDA)**: Jupyter NoteBook,Pandas,Seaborn & Matplotlib
- **Visualization**: Power BI
- **Languages**: SQL, DAX (in Power BI),Python

---

## 🧠 Learnings

- Data wrangling using SQL
- Power BI conditional columns
- Deriving insights through EDA
- Building multi-page dashboards for presentation

---
### ✅ Page 1: Home  
> Overview of the banking data with summary statistics and key visuals.  

<img width="1754" height="984" alt="Screenshot 2026-01-31 200945" src="https://github.com/user-attachments/assets/9bb685b0-69c3-47b7-86dc-e96a7271bcae" />


---

### ✅ Page 2: Loan Analysis  
> Insights into loan distribution, types, and customer segments.  
<img width="1757" height="983" alt="Screenshot 2026-01-31 201011" src="https://github.com/user-attachments/assets/84c15e55-7c17-4a25-99e5-330e312e4ba0" />


---

### ✅ Page 3: Deposit Analysis  
> Breakdown of account balances, deposit types, and correlation patterns.  

<img width="1377" height="766" alt="Screenshot 2026-01-31 201031" src="https://github.com/user-attachments/assets/65210c9d-47a5-480d-a361-52f649cfae84" />


---

### ✅ Page 4: Summary  
> Final insights from EDA, including correlations and demographic trends.  

<img width="1370" height="767" alt="Screenshot 2026-01-31 201059" src="https://github.com/user-attachments/assets/6f216de5-5664-4d1a-b111-e3f7806f7b44" />

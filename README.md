# 🏦 Bank Loan Portfolio Risk Analysis  
## Power BI Dashboard for Loan Performance, Credit Risk, and Portfolio Monitoring

Centered on credit risk and portfolio health, this analysis evaluates Daiz Bank’s loan book to uncover patterns in repayment behavior, defaults, arrears, borrower quality, and portfolio concentration. The aim was to assess how exposed the bank is to loan-related risk and identify where stronger monitoring, pricing, and lending controls are needed.

Using **Power BI**, I cleaned, transformed, and modeled the loan dataset into an interactive dashboard that tracks performance across loan status, loan type, borrower income, credit score, interest rate, loan term, and borrower demographics. The result is a clearer view of portfolio quality and a stronger foundation for risk-informed lending decisions.

🧰 **Tools Used:** Power BI 


## 🎯 Project Goal

The goal of this analysis was to help Daiz Bank better understand the risk profile of its loan portfolio by tracking repayment performance, identifying non-performing segments, and revealing areas of concentration that could threaten financial stability.

The dashboard was built to support decisions around:

- portfolio quality monitoring
- credit risk assessment
- loan type concentration
- borrower segmentation
- delinquency and default control
- long-term portfolio resilience



## 🌐 Business Context

This Bank is a major financial institution in the United States, serving individuals, families, and businesses through a broad range of loan products. Loans are central to the bank’s profitability and long-term growth, but they also expose the institu]tion to financial loss, regulatory pressure, and reputational risk when borrowers fail to repay on time.

Legacy approaches to risk assessment were no longer sufficient for a fast-changing financial environment. A more dynamic, data-driven approach was needed to monitor the portfolio more closely, detect trouble spots earlier, and improve lending strategy over time.



## 🧾 About the Dataset

The dataset contains **1,500 loan records** and includes borrower, loan, and repayment-related fields such as:

- Loan ID
- Borrower ID
- Gender
- Borrower Age
- Marital Status
- Loan Amount
- Loan Type
- Interest Rate
- Loan Term
- Loan Status
- Credit Score
- Income
- Employment Status
- Loan Origination Date
- Loan Paid Date

This made it possible to assess the portfolio from both a **performance angle** and a **borrower risk angle**.


## 🛠️ Workflow

### 1. Data Importation and Cleaning

I started by importing the dataset into Power BI and checking it for missing values, inconsistencies, and duplicates. To make the data more useful for analysis, grouped fields were created for:

- age bracket
- credit score range
- loan amount range
- income range

A custom interest-based field was also created to estimate interest earned on relevant loan records.


### 2. Data Modeling

A separate **date table** was created and linked to the loan origination date so that loan trends could be analyzed over time by year, quarter, and month. This made it possible to evaluate how loan volume evolved between 2018 and 2021 and gave the dashboard a stronger time-based analytical structure.


### 3. KPI Development

To make the dashboard useful from both a portfolio and risk perspective, I structured it into two main views:

#### 🧩 Portfolio Overview Dashboard
This page focuses on the broader composition of the loan book and tracks:

- total loans
- gender split
- total loan volume
- interest earned
- annual percentage rate
- average income
- average credit score
- loan volume by quarter
- loan volume by age bracket
- loan volume by marital status
- loan volume by employment status
- loan volume by month and year

#### ⚠️ Loan Status & Type Dashboard
This page focuses more directly on repayment risk and tracks:

- paid off loans
- repayment rate
- loans in arrears
- defaulted loans
- delinquency rate
- default rate
- loan volume by status
- loan volume by income range
- loan volume by loan type
- loan volume by loan term
- loan volume by credit score range
- loan volume by interest rate
- loan volume by loan amount range

This two-part structure made the dashboard useful for both executive-level portfolio monitoring and deeper risk analysis.

## 🖼️ Dashboard Preview

### Loan Portfolio Overview
![Loan Portfolio Overview](./Screenshot%202026-03-28%20150426.png)

### Loan Status & Type Analysis
![Loan Status & Type Analysis](./Screenshot%202026-03-28%20150454.png)

## 📊 What the Dashboard Reveals

### 📌 Portfolio Overview
The dashboard shows a portfolio of **1,500 loans** with a total loan volume of **$36.62M**, average income of **$46.57K**, average credit score of **681.17**, and interest earned of **$1.83M**. It also shows a noticeable gender imbalance, with **1,067 male borrowers** and **433 female borrowers**, alongside strong concentration in employed and married borrower groups.

These patterns suggest that while the portfolio is broad, it is not evenly distributed across borrower segments.

### 📌 Loan Status & Type
The repayment side of the portfolio shows more concern. Out of the total loans, **925 were paid off**, but **318 were in arrears** and **257 had defaulted**. This translates to a **61.67% repayment rate**, **21.20% delinquency rate**, and **17.13% default rate**.

Loan type distribution also shows that **mortgages hold the largest share**, followed closely by commercial, personal, and auto loans, indicating moderate diversification but with visible concentration at the top.


## 🔍 Key Insights

### 🧨 1. The portfolio carries high credit risk
The dashboard shows a **21.20% delinquency rate** and a **17.13% default rate**, meaning **38.33% of loans** are either already underperforming or at serious risk. This is a major warning sign for portfolio quality and suggests that repayment stress is not isolated to a small corner of the loan book.

### 💸 2. A large share of loan value is tied up in non-performing loans
About **$13.9M**, or roughly **38% of the total loan volume**, is tied up in arrears and defaulted loans. That includes **$7.3M in arrears** and **$6.6M in defaults**, showing that risk is not only visible in loan counts but also highly material in dollar terms.

### 🏠 3. Mortgage lending is the single biggest area of exposure
Mortgage loans account for **$9.9M** of the portfolio and make up **26.7%** of all loans. While the portfolio is spread across multiple loan types, mortgage concentration still represents a meaningful risk if housing-related repayment pressure increases.

### 🧮 4. Mid-to-high credit score borrowers still show meaningful risk
One of the more interesting findings from the analysis was that the largest loan volumes sit in the **633–743** and **above 743** credit score bands, yet high levels of arrears and defaults still persist. This suggests that credit score alone is not fully capturing repayment risk.

### 💼 5. High income does not automatically mean low risk
Borrowers earning **above $63K** account for the largest share of the portfolio at **$16.0M**, but repayment issues still remain present. This shows that income alone is not a sufficient safeguard against loan distress and should be evaluated alongside other borrower characteristics.

### 📈 6. Interest rate concentration may be increasing repayment pressure
A large portion of lending is clustered around **8% to 9% interest rates**, representing **$10.1M** in loan value. This may reflect aggressive pricing for risk, but it may also be making repayment harder for some borrowers and contributing to delinquency.

### ⏳ 7. The portfolio leans heavily toward medium-term loans
Loans with terms between **2 and 4 years** make up **$27.2M** of the portfolio, meaning much of the bank’s exposure sits in medium-duration lending. This creates sensitivity to changing economic conditions over time.

### 👥 8. Borrower distribution reveals both reliance and opportunity
The portfolio depends strongly on **employed borrowers ($26.0M)** and **married borrowers ($23.0M)**, while the borrower base is also heavily skewed toward men at **71% male vs 29% female**. This suggests both concentration in current borrower types and growth potential in less represented segments.


## 💡 Recommendations

### 🛡️ 1. Strengthen credit risk controls
The loan approval process should be refined to better detect borrowers who are likely to struggle with repayment. Stronger pre-approval screening can reduce the number of loans that later become delinquent or defaulted.

### ⏰ 2. Improve delinquency management
I would recommend putting stronger early-warning systems in place to detect missed payments quickly and trigger follow-up before arrears grow into more serious repayment issues.

### 🔄 3. Reduce exposure to default through support strategies
High-risk borrowers may benefit from restructuring options, repayment support, or adjusted payment plans before their loans fully deteriorate. This could help preserve more value in the portfolio.

### 💹 4. Reassess the interest rate strategy
The pricing model should be reviewed to make sure higher rates are not unintentionally increasing repayment stress. Risk-based pricing is important, but it should still remain realistic for borrowers.

### 🧺 5. Diversify the portfolio further
Even with multiple loan types in the mix, the portfolio still shows concentration in mortgages and medium-term loans. Spreading lending more evenly across products can reduce concentration risk.

### 🎯 6. Focus more on stronger borrower profiles
From the analysis, it is clear that income and credit score alone are not enough to define borrower quality. More emphasis should be placed on employment stability, repayment behavior, and combined borrower risk indicators.

### 🌱 7. Expand into underserved customer segments
The borrower mix suggests room to grow in less represented segments, particularly where repayment potential may be strong but lending exposure is currently low.

### 📡 8. Improve portfolio monitoring and reporting
Better monitoring tools and more frequent reporting can help the bank identify risk earlier, respond faster, and make more informed portfolio decisions.


## 🧠 Final Conclusion

This analysis shows that Daiz Bank’s loan portfolio is sizeable and profitable, but it is also carrying a level of repayment risk that cannot be ignored. A substantial share of the portfolio is sitting in arrears or default, with concentration risks across mortgage lending, medium-term loans, and certain borrower segments.

By building this dashboard, I was able to highlight not just where the risks are, but also where the bank can act — through stronger approval standards, better delinquency management, more balanced pricing, and improved diversification. That makes the dashboard more than a reporting tool; it becomes a guide for smarter and more resilient risk management.


## 🤝 Feedback Welcome

Thanks for checking out this analysis.

Feedback, suggestions, and collaboration ideas are always welcome, especially around **Power BI dashboards, financial analytics, and risk intelligence**.

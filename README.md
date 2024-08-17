# Bank_Loan-_Analytics
### 1. Problem Statement:

This project aims to analyze and visualize financial loan data to identify key patterns and trends that can inform better decision-making processes for financial institutions. The primary goal is to create an interactive dashboard that provides insights into loan distribution, borrower behavior, and repayment status, ultimately helping stakeholders in risk assessment and credit management.

### 2. Dataset Description:

The dataset contains 38,576 entries with 24 columns, covering various aspects of financial loans, including borrower details, loan characteristics, and repayment information. Key columns include:

loan_amount: The amount of the loan taken by the borrower.
term: The duration of the loan (e.g., 36 or 60 months).
int_rate: The interest rate on the loan.
loan_status: The current status of the loan (e.g., fully paid, charged off).
annual_income: The borrower's annual income.
dti: Debt-to-income ratio.
emp_length: Length of employment for the borrower.
grade and sub_grade: The loan grades assigned based on risk factors.

### 3. Insights from the Dashboards:

3.1 Loan Distribution by Grade:
The majority of loans are concentrated in the middle-risk grades, with B and C grades accounting for the largest share, indicating a moderate risk appetite among lenders.

3.2 Interest Rate Analysis:
Higher-risk loans, indicated by lower grades (e.g., D, E), are associated with higher interest rates, reflecting the additional risk lenders take on.

3.3 Employment Length and Loan Amount:
Borrowers with longer employment histories tend to secure higher loan amounts, which may suggest that stable employment is a key factor in lending decisions.

3.4 Loan Purpose:
The most common loan purposes are debt consolidation and credit card refinancing, indicating that many borrowers are using loans to manage existing debt.

3.5 Geographic Distribution of Loans:
Certain states have higher loan amounts and more frequent borrowing, highlighting regional economic differences.

3.6 Default Rates by Grade:
Loans in lower grades have significantly higher default rates, underscoring the importance of accurate risk grading.

3.7 Payment Timeliness:
There is a noticeable trend where loans with longer terms have more late payments, suggesting potential liquidity issues for borrowers over extended periods.

3.8 Total Payments:
The dashboard also highlights the total payments made across different loan types, providing a clear view of the financial flows associated with these loans.

these are some of the top importatnt insights we got after creating database. There are several other insights and Visualizaion for Deepar Analysis

### 4.Key Performance Indicators (KPIs) Cross-Checked:
To ensure the accuracy and reliability of the insights, I cross-checked all the KPIs using Microsoft SQL Server. This involved querying the underlying dataset to validate calculations such as default rates, loan distribution by grade, and interest rate analysis. By integrating SQL Server, I ensured that the data integrity and the calculated KPIs aligned perfectly with the visualizations presented in the Power BI dashboards.

### 5.Overall Complete Project Summary:

This project provides a comprehensive analysis of financial loan data, offering valuable insights into borrower behavior, loan characteristics, and repayment trends. By leveraging the power of DAX and interactive Power BI dashboards, the project enables stakeholders to make informed decisions regarding credit risk management and lending strategies. The dashboards provide a user-friendly interface to explore data patterns, while the underlying analysis emphasizes key risk factors, such as borrower grade, employment length, and interest rates. This project serves as a robust tool for financial institutions aiming to enhance their loan portfolio management.

### 6. Snapshots Of Dashboards(Power-BI services)

Summary Dashboard(1)
![Screenshot (89)](https://github.com/user-attachments/assets/48570bb8-eeaf-41bd-894a-b90fdb4552d1)

Overview Dashboard(2)
![Screenshot (90)](https://github.com/user-attachments/assets/0d3654bf-3d99-44a2-82be-a030470d8000)


Details Dashboard(3)
![Screenshot (91)](https://github.com/user-attachments/assets/03a1de13-4cb0-475f-8948-166d820319d2)

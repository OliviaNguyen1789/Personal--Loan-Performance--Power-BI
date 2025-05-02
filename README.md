
![image](https://github.com/user-attachments/assets/dc4d2538-70a2-4259-868e-cdc46fe74080)


# Project Title: Personal Loan Portfolio Management Dashboard| Power-BI



Author: [Olivia Nguyen]  
Date: March 2025  
Tools Used: Power BI 

---

## 📑 Table of Contents  
I. [📌 Background & Overview](#-background--overview)  
II.[📊 Power BI Visualization](#-power-bi-visualization)  
III. [🔎 Final Conclusion & Recommendations](#-final-conclusion--recommendations)  
IV. [📂 Dataset Description](#-dataset-description)  


## 📌 Background & Overview

### 📖 What is this project about?
This project focuses on developing a Personal Loan Portfolio Management Dashboard using Power BI to assess loan performance, borrower demographics, and portfolio risk. The analysis explores customer attributes such as income, age, home ownership, and employment duration, alongside loan details like grade, amount, interest rate, and term. By examining current loan status and historical patterns, the dashboard provides insights to optimize lending strategies, enhance risk management, and improve overall loan portfolio performance through data-driven decision-making.  

### 👤 Who is this project for?   
The insights gained from the Personal Loan Portfolio Management Dashboard will empower the following stakeholders to make informed strategic decisions and enhance financial operations:
- Financial Institutions: Assess borrowers’ ability to repay their debt on time, preventing the issuance of non-performing loans and optimizing lending policies.They also use the dashboard to identify risk patterns, monitor loan grades, and manage portfolio risk.
- Borrowers: Predict loan default risk to guide personal finance decisions, helping to prevent long-term negative financial consequences.
- Other Stakeholders: Evaluate individuals' financial capacity before providing services, ensuring more informed decision-making.

### ❓ Business Questions:
- What is the distribution of loan status across the portfolio?
- Which customer segments (by income, age, home ownership, employment duration) are more likely to default?
   
## 📊 Power BI Visualization
### Dashboard 1 Preview

![image](https://github.com/user-attachments/assets/d64b663b-04a4-4f31-8d53-a1950cc8f363)

-🚀 **Loan Amount Distribution:** The majority of loans have relatively small amounts, with 90% of customers holding loans under $20,000.  
-🚀 **Loan Purpose:** Home improvement loans account for the lowest percentage (12%), while other loan purposes range from 16% to 20%.  
-🚀 **Loan Grade Distribution:** The bank primarily lends to borrowers with strong credit profiles, with 45% of the loan amount allocated to Grade A, 28% to Grade B, 15% to Grade C, 10% to Grade D, and 2% to Grade E borrowers.  
-🚀 **Loan Term:** The distribution of loan amounts is relatively consistent across short-term, medium-term, and long-term loans.  
-🚀 **Interest Rates:** Loans with higher credit grades (e.g., Grade A) typically have lower interest rates compared to those with lower grades (e.g., Grade D or E). Loans with higher amounts or longer terms tend to have higher interest rates.  
-🚀 **Debt-to-Income (DTI) Ratio**: 67% of loans are considered low-risk based on the DTI ratio, with only 4% classified as high or very high risk. Higher DTI ratios correlate with higher interest rates, reflecting the increased risk of default.  

      

### Dashboard 2 Preview

![image](https://github.com/user-attachments/assets/0c1f8d89-8aac-40cb-a9e1-6fc3c1b628f1)

- 🚀 **Home Ownership:** The majority of customers are either renting or have a mortgage (92%), with homeowners accounting for only 7%.    
- 🚀 **Customer Income:** 79% of the loan amount is attributed to customers earning under $100,000 per year, while 20% comes from customers earning between $100,000 and $300,000.   
- 🚀 **Age Distribution:** The majority of customers are under 30 years old, indicating a younger customer base.   
- 🚀 **Employment Duration:** Surprisingly, 11% of the loan amount is from unemployed customers, while 81% comes from customers with less than 1 year of employment.   
- 🚀 **Income:** Interestingly, customers with bad loan grades often have higher average incomes than those with good loan grades. Average income is generally lower for younger customers compared to older customers. Mortgage customers have the highest average income, followed by homeowners, and then renters.   

   
   
### Dashboard 3 Preview

![image](https://github.com/user-attachments/assets/3feef028-433e-4773-87ad-940d447634aa)

-🚀 The overall default rate is high at 21%. Customers aged 41-50 have the lowest default rate at 17%, while other age groups experience default rates ranging from 20% to 23%. Renters represent the majority of defaulting customers (75%), followed by mortgage holders at 23%, with homeowners accounting for only 2%.
- 🚀 Default rates tend to rise with longer loan terms, lower loan grades, and higher loan amounts. They are negatively correlated with employment duration, income, and DTI ratios. Debt consolidation loans show the highest default rate at 30%, while education (16%) and venture loans (14%) have the lowest default rates. Additionally, defaulting customers tend to face higher interest rates.


## 🔎 Final Conclusion & Recommendations 

The bank's lending strategy reveals that a significant portion of its customers are high-risk borrowers, characterized by low income (under $100,000 annually), short employment durations (less than 1 year), and a predominantly younger demographic with little to no homeownership. These factors, combined with limited financial stability, contribute to a higher likelihood of loan defaults. Interestingly, the bank also extends loans to customers with lower credit grades (D and E), as their average income tends to be higher than that of borrowers with better credit scores. 

The overall default rate is notably high at 21%. Default rates are higher for long-term loans, lower loan grades, and larger loan amounts. They are negatively correlated with employment duration, income, and DTI ratios. Debt consolidation loans exhibit the highest default rate (30%), while education loans (16%) and venture loans (14%) show the lowest default rates. Customers aged 41-50 have the lowest default rate at 17%, with default rates for other age groups ranging from 20% to 23%. Renters represent the majority of defaulting customers (75%), followed by mortgage holders at 23%, and homeowners at only 2%.

Despite the high-risk profile of most customers, the bank manages this risk by offering smaller loan amounts to ensure borrowers’ ability to repay. It diversifies its exposure across short, medium, and long-term loans to distribute the risk. The bank focuses on customers with low DTI ratios and prefers to avoid long-term debt. Additionally, interest rates are adjusted according to the risk profile: higher interest rates are applied to loans with larger amounts, longer terms, or lower credit grades, helping to offset the increased risk of default.


**Phan tich lai suat cho homeownership, age, income, emplyment duration.... + recommendation**

## 📂 Dataset Description

### 🌐 Data Source
- The Loan Default dataset originates from Kaggle and can be accessed at:  https://kaggle.com/datasets/prakashraushan/loan-dataset/data
- Size: 32,600 rows, 13 columns
- Format: .csv

### 🔀 Table schema
<details>
<summary>Table: Loan dataset </summary>  

| Number | Variable name       | Definition                                                | Data Type |
| ------ | ------------------- | --------------------------------------------------------- | --------- |
| 1      | customer_id         | Unique identifier for each customer                       | Text      |
| 2      | customer_age        | Age of the customer                                       | Text      |
| 3      | customer_income     | Annual income of the customer                             | Number    |
| 4      | home_ownership      | Annual income of the customer                             | Text      |
| 5      | employment_duration | Duration of employment in months                          | Number    |
| 6      | loan_intent         | Purpose of the loan                                       | Text      |
| 7      | loan_grade          | Grade assigned to the loan                                | Text      |
| 8      | loan_amnt           | Loan amount requested                                     | Number    |
| 9      | loan_int_rate       | Interest rate of the loan                                 | Number    |
| 10     | term_years          | Loan term in years                                        | Number    |
| 11     | historical_default  |  Indicates if the customer has a history of default (Y/N) | Text      |
| 12     | cred_hist_length    |  Length of the customer's credit history in years         | Number    |
| 13     | Current_loan_status | Current status of the loan (DEFAULT, NO DEFAULT)          | Text      |

</details>



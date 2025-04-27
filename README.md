



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
V.[🧠 Design Thinking Process](#-design-thinking-process)  


## 📌 Background & Overview

### 📖 What is this project about?
The objective of this project is to develop a Personal Loan Portfolio Management Dashboard using Power BI to analyze loan performance, customer demographics, and portfolio risk. The analysis focuses on assessing borrower profiles based on attributes such as income, age, home ownership, and employment duration, as well as evaluating loan characteristics like loan grade, amount, interest rate, and duration. By examining current loan status and historical patterns, the dashboard provides insights to optimize lending strategies, enhance risk management, and improve overall loan portfolio performance through data-driven decision-making.

  
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

![image](https://github.com/user-attachments/assets/fbb380ad-45bd-4c05-b9e8-eece967989b8)


-🚀 Scrap rate:



### Dashboard 2 Preview

![image](https://github.com/user-attachments/assets/f5fb094c-ca82-44f5-a081-dfe7c3991be6)

- 🚀 

### Dashboard 3 Preview
![image](https://github.com/user-attachments/assets/258c66be-67bf-48bc-bbef-9912b8517222)

## 🔎 Final Conclusion & Recommendations 

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



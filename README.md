# **Bank Marketing Campaign Analysis**

## **Overview**
This project focuses on cleaning and analyzing data from a bank's marketing campaign. The goal is to explore customer information, clean the dataset, and uncover patterns that explain why some customers choose to subscribe to a term deposit. By analyzing this data, we can provide insights to improve future marketing strategies.

---
## **Business Problem**
Bank marketing campaigns often target a large number of customers, but only a few respond positively. Understanding which customers are likely to subscribe can help banks focus their efforts, reduce costs, and improve success rates.

---
## **Objectives**
1. Clean and prepare the data for analysis by handling missing values, errors, and inconsistencies.
2. Explore the dataset to identify trends, patterns, and relationships between variables.
3. Provide clear insights to help understand customer behavior and improve campaigns
---
## **Dataset Description**
The dataset used in this project is the **Bank Marketing Dataset**, which is publicly available on [Kaggle](https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset). It contains information about 11,162 customers contacted during a bank's marketing campaign. The data includes customer demographics, financial information, and details about the campaign. Below is a description of the key columns:

1. **age**: Customer's age.
2. **job**: Type of job (e.g., blue-collar, technician, management).
3. **marital**: Marital status (e.g., married, single, divorced).
4. **education**: Education level (e.g., primary, secondary, tertiary, unknown).
5. **default**: If the customer has credit in default (yes/no).
6. **balance**: Customer's account balance
7. **housing**: If the customer has a housing loan (yes/no).
8. **loan**: If the customer has a personal loan (yes/no).
9. **contact**: Type of communication used.
10. **day**: Day of the last contact.
11. **month**: Month of the last contact (e.g., May, June).
12. **duration**: Duration of the last contact in seconds.
13. **campaign**: Number of times the customer was contacted during this campaign.
14. **pdays**: Days since the customer was last contacted (-1 means never contacted before).
15. **previous**: Number of times the customer was contacted in previous campaigns.
16. **poutcome**: Outcome of the previous campaign (e.g. success and failure).
17. **deposit**: **Target variable** – whether the customer subscribed to a term deposit (yes/no).
---

## **Steps in the Project**
### 1. **Data Cleaning**
- Handled missing values and placeholder entries (e.g., "unknown").
- Standardized column names for clarity.
- Removed duplicate rows and ensured data consistency.

### 2. **Exploratory Data Analysis (EDA)**
- Analyzed the distribution of the target variable (`term_deposit`).
- Explored numerical features:
  - Identified trends in `age`, `account_balance`, and `last_contact_duration`.
  - Investigated relationships between features and the target variable.
- Explored categorical features:
  - Examined patterns across `job_type`, `marital_status`, `education_level`, and more.
  - Analyzed the impact of `contact_method` and `previous_outcome` on subscriptions.
- Explored time-based trends:
  - Subscription rates by month highlighted the impact of timing on campaign success.

### 3. **Key Insights**
- Higher account balances and longer call durations are associated with higher subscription rates.
- Customers contacted fewer times during a campaign tend to subscribe more.
- Retirees, students, and those with tertiary education have higher subscription rates.
- Mobile contact is more effective than other methods.
- Subscription rates vary by month, with **March** and **December** performing best, and **May** performing poorly despite high contact volume.

---

## **Recommendations**
- Target customers with higher account balances and positive prior campaign outcomes.
- Avoid over-contacting customers to prevent negative responses.
- Prioritize mobile contact for better results.
- Focus campaigns in high-performing months like **March** and **December**.
- Develop tailored messaging for retirees, students, and highly educated customers.

---

## **Technologies Used**
- **Python**: For data cleaning and analysis.
- **Pandas**: Data manipulation and cleaning.
- **Seaborn & Matplotlib**: Data visualization.
- **Jupyter Notebook**: Interactive environment for analysis.



### Credit Card Financial Dashboard
This project is a comprehensive credit card weekly dashboard that provides real-time insights into key performance metrics and trends, enabling stakeholders to monitor and analyze credit card operations effectively.

### Project Overview
The dashboard was developed using Power BI to provide real-time insights by analyzing transaction and customer data from a SQL database. It is designed to streamline data processing and analysis to monitor key performance metrics and trends and share actionable insights with stakeholders to support decision-making processes.

### Data
The dashboard uses two main datasets: cc_detail and cust_detail.

cc_detail
This dataset contains credit card transaction information with the following columns:

Client_Num: Unique client identifier

Card_Category: The type of credit card (e.g., Blue, Silver, Gold, Platinum)

Annual_Fees: Annual fees associated with the card

Activation_30_Days: Indicator for activation within 30 days

Customer_Acq_Cost: Customer acquisition cost

Week_Start_Date: The start date of the week for the transaction

Week_Num: The week number

Qtr: The quarter

current_year: The year

Credit_Limit: The credit limit on the card

Total_Revolving_Bal: The total revolving balance

Total_Trans_Amt: The total transaction amount

Total_Trans_Ct: The total transaction count

Avg_Utilization_Ratio: The average utilization ratio

Use_Chip: Indicates if the transaction used a chip

Exp_Type: The type of expense

Interest_Earned: Interest earned on the balance

Delinquent_Acc: Indicates if the account is delinquent

cust_detail
This dataset provides customer demographic and financial data with the following columns:

Client_Num: Unique client identifier

Customer_Age: The age of the customer

Gender: The gender of the customer

Dependent_Count: The number of dependents

Education_Level: The customer's education level

Marital_Status: The customer's marital status

State_cd: The customer's state code

Zipcode: The customer's zip code

Car_Owner: Indicates if the customer owns a car

House_Owner: Indicates if the customer owns a house

Personal_loan: Indicates if the customer has a personal loan

Contact: The customer's contact method

Customer_Job: The customer's job title

Income: The customer's income

Cust_Satisfaction_Score: The customer's satisfaction score

### Tools Used
Power BI: For creating the interactive financial dashboard.

SQL: For managing and querying the datasets.

### Key Insights from the Dashboard
Overall Financials: The overall revenue is $57M, with total interest at $8M, and a total transaction amount of $46M.

Customer Demographics: Male customers contribute more to revenue ($31M) compared to female customers ($26M).

Card Categories: Blue and Silver credit cards account for 93% of the overall transactions.

Geographic Insights: The states of Texas (TX), New York (NY), and California (CA) are responsible for 68% of the project's transactions.

Key Performance Indicators: The overall activation rate is 57.5%, and the overall delinquent rate is 6.06%.

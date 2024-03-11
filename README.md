# Predictive-Analytics-Project-for-Working-Capital-Optimization-to-maximize-cash-flow

# Overview

Working capital optimization involves strategically managing a company's current assets and liabilities to enhance operational efficiency and financial health. It focuses on finding the right balance between accounts receivable (AR) and accounts payable (AP) to ensure sufficient liquidity while minimizing costs and risks.
AR data refers to money customers owe the company, while AP data represents the money the company owes to suppliers.
This involves predicting the timing of customer payments and supplier payments to ensure cash flow and liquidity in a specific period for the company. By analyzing historical data and using predictive modeling techniques, the project aims to forecast the week customers are likely to pay the company and the week in which the company should pay suppliers.
These predictions enable the company to proactively manage cash flow, ensuring that customer payments are received on time to cover outgoing payments to suppliers. This helps maintain a healthy cash position, enhances liquidity, and allows the company to meet its financial obligations effectively.

# Aim

The project aims to optimize working capital management by leveraging accounts receivable and payable data. Through predictive analysis, the project aims to accurately forecast the timing of customer and supplier payments, enabling the company to ensure cash flow and liquidity within a specified period.

# Data Description

● Customer Data:
○ Customer ID: Unique identifier for each customer.
○ Customer Name: Name of the customer.
○ Customer Payment Terms: Terms and conditions for customer payments.
○ Address: Physical address or location of the customer.
 ○ Credit Limit: Maximum credit amount extended to the customer.

● Receivables Data:
○ Business Code: Code representing the type of business transaction.
○ Customer Number: Unique identifier for each customer.
○ Customer Name: Name of the customer.
○ Payment_Date: Date of payment received.
○ Business Year: Year of the business transaction.
○ Posting_Date: Date of posting the transaction.
○ Due_Date: Date by which the payment is due.
○ Payterm: Payment terms for the invoice.
○ Invoice Currency: Currency in which the invoice is issued.
○ Total Open Amount: Total amount of the invoice.
○ USD_CURRENCY: Currency conversion rate to USD.
○ Total Open Amount_USD: Total amount in USD.
○ Invoice ID: Unique identifier for each invoice.
○ Is Open: Indicates whether the invoice is open or closed.
○ DUNNLEVEL: Dunn level of the invoice. Dunn level refers to the level of
past-due status or aging of an invoice, indicating the severity or length of time the invoice remains unpaid, basically how many times the customer was contacted for payment and the status remained unchanged.
○ Credit_limit: Credit limit assigned to the customer.
○ Baseline_Date: Baseline date for the transaction.
○ Region: Geographic region associated with the transaction.

● Suppliers Data:
○ Supplier ID: Unique identifier for each supplier.
○ Supplier Name: Name of the supplier.
○ Payment Terms: Terms and conditions for supplier payments.
○ Vendor Type: Type or category of the vendor/supplier.
○ Supplier Category: Categorization of the supplier.

● Payables Data:
○ Invoice Number: Unique identifier for each invoice.
○ Posting Date: Date of posting the invoice.
○ Invoice Date: Date of the invoice.
○ Payment Date: Date of payment made.
○ Net Due Date (System Calculated Date): Calculated date for net payment
due.
○ Supplier ID: Unique identifier for each supplier.

 ○ Invoice Amount: Total amount of the invoice.
○ Fiscal Year: Financial year associated with the invoice.
○ Overdue: Indicates if the payment is overdue.
○ Invoice Status: Status of the invoice (e.g., paid, outstanding).
○ Spend Category: Categorization of the expenditure.
○ Total Outstanding Amount: Total amount outstanding for the invoice.
○ Late Payment Fees: Fees charged for late payments.
○ Payterm_n: Payment terms for the invoice.
○ Vendor Type: Type or category of the vendor/supplier.

# Tech Stack

➔ Language: Python
➔ Libraries: pandas, numpy, matplotlib, statsmodels, seaborn, scikit-learn, pyodbc

# Approach

● AR Data:
○ Exploratory Data Analysis (EDA): Analyze the accounts receivable data to
gain insights into the distribution, trends, and patterns.
○ Feature Engineering: Transform and manipulate the AR data to extract
relevant features for the prediction model.
○ Model Building: Utilize various regression models such as
RandomForestRegressor, LinearRegression, KNeighborsRegressor, GradientBoostingRegressor, and SVR to predict the week of customer payments.
● AP Data:
○ EDA: Perform exploratory analysis on the accounts payable data to
understand its characteristics and identify any anomalies.
○ Feature Engineering: Engineer additional features from the AP data that
may be relevant for the analysis and prediction.
○ Model Building: Develop prediction models based on the AP data to
forecast the week of supplier payments.
● Working Capital Optimization (WCO) Calculations:
○ Group and sum the receivables and payables data on a weekly basis.
○ Calculate the working capital by subtracting the sum of payables from the
sum of receivables for each week.

○ Analyze the working capital figures to identify periods of positive or negative cash flow and assess the overall liquidity.

# Project Takeaways

1. Develop strong data analysis skills through exploratory data analysis of accounts receivable and payable data.
2. Gain experience in transforming and manipulating data to create meaningful features for financial predictive modeling.
3. Build regression models using various algorithms such as RandomForestRegressor, LinearRegressor, KNeighborsRegressor, GradientBoostingRegressor, and SVR.
4. Understanding the importance of different features in predicting payment timings.
5. Gain expertise in predicting and forecasting cashflow based on customer
payments and supplier payments.
6. Optimize working capital by analyzing and managing the balance between
accounts receivable and payable.
7. Learn how to communicate the results and insights derived from the predictive
models.
8. Gain practical experience in applying data analysis and predictive modeling
techniques to real-world financial data.
9. Understand financial concepts,working capital management,and its impact on
business performance.

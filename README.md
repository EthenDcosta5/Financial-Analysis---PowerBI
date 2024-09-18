# Financial Analysis using Power BI & DAX

This project focuses on analyzing credit card usage and financial metrics for a banking institution using **Power BI** and **DAX queries**. The goal is to provide key insights into customer behavior, credit utilization, and financial performance by applying advanced DAX functions.

## Project Overview

The analysis covers various aspects of financial data, including:

- Running totals of credit card transactions.
- 4-week moving averages of credit limits for each client.
- Month-over-month and week-over-week growth in transaction amounts.
- Customer Acquisition Cost (CAC) as a ratio of transaction amounts.
- Yearly average of client utilization ratios.
- Top 5 clients by total transaction amount.
- Credit risk scores based on multiple financial metrics.
- Churn indicators for inactive clients.

## Problem Statements and DAX Queries

1. **Running Total of Credit Card Transactions**

    **DAX Query:**
    ```DAX
      running_total = 
CALCULATE(SUM(credit_card[Total_Trans_Amt]), FILTER(ALL('credit_card'), credit_card[Week_Start_Date] <= MAX(credit_card[Week_Start_Date])))
    ```

2. **4-Week Moving Average of the Credit Limit for Each Client**

    **DAX Query:**
    ```DAX
    -- Placeholder for DAX Query: 4-Week Moving Average
    ```

3. **Month-on-Month (MoM%) Growth on Transaction Amount**

    **DAX Query:**
    ```DAX
    -- Placeholder for DAX Query: MoM% Growth
    ```

4. **Customer Acquisition Cost (CAC) as a Ratio of Transaction Amount**

    **DAX Query:**
    ```DAX
    -- Placeholder for DAX Query: CAC Calculation
    ```

5. **Yearly Average of Avg_Utilization_Ratio for All Clients**

    **DAX Query:**
    ```DAX
    -- Placeholder for DAX Query: Yearly Avg Utilization Ratio
    ```

6. **Percentage of Interest Earned Compared to Total Revolving Balance for Each Client**

    **DAX Query:**
    ```DAX
    -- Placeholder for DAX Query: Interest Earned vs Revolving Balance
    ```

7. **Top 5 Clients by Total Transaction Amount**

    **DAX Query:**
    ```DAX
    -- Placeholder for DAX Query: Top 5 Clients by Transaction
    ```

8. **Clients Whose Avg_Utilization_Ratio Exceeds 80%**

    **DAX Query:**
    ```DAX
    -- Placeholder for DAX Query: Utilization Ratio > 80%
    ```

9. **Customer Churn Indicator (Clients with No Transactions in Last 6 Months)**

    **DAX Query:**
    ```DAX
    -- Placeholder for DAX Query: Customer Churn Indicator
    ```

10. **Delinquency Rate (Percentage of Clients with Delinquent Accounts)**

    **DAX Query:**
    ```DAX
    -- Placeholder for DAX Query: Delinquency Rate
    ```

11. **Credit Risk Score (Based on Avg_Utilization_Ratio, Delinquent Accounts, and Total Revolving Balance)**

    **DAX Query:**
    ```DAX
    -- Placeholder for DAX Query: Credit Risk Score
    ```

12. **Income vs Credit Limit Correlation**

    **DAX Query:**
    ```DAX
    -- Placeholder for DAX Query: Income vs Credit Limit Correlation
    ```

13. **Average Customer Satisfaction Score by Credit Card Category**

    **DAX Query:**
    ```DAX
    -- Placeholder for DAX Query: Avg Satisfaction by Card Category
    ```

14. **Loan Approval vs Credit Limit (Analyzing How Credit Limit Affects Loan Approval)**

    **DAX Query:**
    ```DAX
    -- Placeholder for DAX Query: Loan Approval vs Credit Limit
    ```

15. **High Risk Clients Flag (Clients with Revolving Balance > 90% of Credit Limit and High Avg_Utilization_Ratio)**

    **DAX Query:**
    ```DAX
    -- Placeholder for DAX Query: High Risk Clients Flag
    ```

## Tools Used

- **Power BI**: Data visualization and reporting.
- **DAX**: Data Analysis Expressions for financial metrics calculation.

## Getting Started

1. Download the Power BI file containing the financial analysis.
2. Review the visuals, KPIs, and calculated metrics based on DAX queries.
3. Explore customer behavior and financial metrics via interactive dashboards.

## Contact

Feel free to reach out for any queries or collaboration:

- **Email**: ethendcosta5@gmail.com
- **LinkedIn**: [linkedin.com/in/ethendcosta](http://linkedin.com/in/ethendcosta)

# Bank Loan Analysis Dashboard - Power BI

## Project Overview
The **Bank Loan Analysis Dashboard** leverages **Power BI** to provide actionable insights into loan data. This interactive dashboard helps financial institutions analyze key metrics, understand customer behaviors, monitor repayment trends, and make data-driven decisions. By utilizing powerful visualizations and dynamic filters, the dashboard simplifies complex datasets for better strategic planning.

---

## Features
- **Loan Status Overview**: Insights into active, closed, and defaulted loans.
- **Customer Demographics**: Analysis of loan data segmented by employment type, home ownership, and loan purpose.
- **Repayment Trends**: Tracking payments and balances to identify repayment patterns.
- **Credit Risk Assessment**: Categorization of loans as good or bad based on repayment behavior.
- **Dynamic Visualizations**: Interactive filters and slicers for real-time analysis.

---

## Dataset Overview
The dataset consists of **24 columns** and **38,577 rows**, providing a comprehensive view of loan applications, customer details, and payment history.

---

## Key Metrics and Calculations
1. **Total Loan Applications**: `COUNT(id)`
   - Displays the total number of loan records.
2. **Total Funded Amount**: `SUM(loan_amount)`
   - Calculates the total loan amount disbursed.
3. **Total Payments Received**: `SUM(total_payment)`
   - Tracks the total payments received across all loans.
4. **Average Interest Rate**: `AVERAGE(int_rate)`
   - Shows the average interest rate across loans.
5. **Average DTI**: `AVERAGE(dti)`
   - Provides an overview of the average debt-to-income ratio.

---

## Dashboard Visualizations
1. **Home Ownership vs. Loan Amount**  
   - **Visualization**: Bar Chart  
   - **Purpose**: Highlights loan amounts across different homeownership categories.

2. **Total Payments Received by Loan Purpose**  
   - **Visualization**: Waterfall Chart  
   - **Purpose**: Displays payment amounts for various loan purposes.

3. **Average DTI by Home Ownership**  
   - **Visualization**: Stacked Bar Chart  
   - **Purpose**: Compares debt-to-income ratios across homeownership categories.

4. **Average Interest Rate by Grade**  
   - **Visualization**: Column Chart  
   - **Purpose**: Shows interest rate variations by loan grade.

5. **Loan Term Distribution**  
   - **Visualization**: Donut Chart  
   - **Purpose**: Displays the proportion of loan terms (e.g., 36 months vs. 60 months).

6. **Total Payment Breakdown by Loan Status**  
   - **Visualization**: Stacked Bar Chart  
   - **Purpose**: Analyzes payments by loan status (Active, Closed, Defaulted).

7. **Sum of Loan Amount by Purpose**  
   - **Visualization**: Pie Chart  
   - **Purpose**: Identifies loan distribution by purpose.

---

## Advanced Features
### Good and Bad Loans
Loans are classified as:
- **Good Loans**: Timely repayments made.
- **Bad Loans**: Defaulted or delayed repayments.  
This parameter aids in assessing credit risk and improving loan approval strategies.

---

## How to Use the Dashboard
1. **Data Import**: Open the dataset in Power BI Desktop.
2. **Data Transformation**: Use Power Query to clean and preprocess the data.
3. **Visualization Setup**: Build or modify visuals based on provided configurations.
4. **Interactive Analysis**: Apply filters and slicers for customized insights.

---

## Insights and Recommendations
- Loans with higher interest rates are typically assigned lower grades.
- Renters tend to have higher debt-to-income ratios compared to homeowners.
- Debt consolidation emerges as the primary loan purpose, accounting for significant disbursed amounts.

---

## Future Enhancements
- Integrate predictive analytics for forecasting loan defaults.
- Add geographical analysis using Power BI map features.
- Enable real-time data integration for up-to-date insights.

---

## Conclusion
This **Bank Loan Analysis Dashboard** showcases the power of **Power BI** in transforming raw data into meaningful insights. The project emphasizes the importance of visual storytelling in understanding financial metrics and supports better decision-making processes.

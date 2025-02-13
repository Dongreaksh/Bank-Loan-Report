# Bank-Loan-Report
## Overview
A bank loan analysis involves evaluating the terms, risks, and financial viability of a loan from a bank's perspective. It is crucial for both the borrower and the lender to assess various factors before agreeing to the terms of a loan. Below is an overview of the key components involved in bank loan analysis:

## Dashboards
### Dashboard 1: Summary
!['Summary image'](![Screenshot 2025-01-21 110519](https://github.com/user-attachments/assets/398a2c0a-4040-4c6d-9480-6e5d90f6d74a)


The Summary Dashboard captures key loan-related metrics and their changes over time, providing a snapshot of the loan portfolio's health and lending strategy impact. It includes the following KPIs:
- Total Loan Applications (MTD and MoM)
- Total Funded Amount (MTD and MoM)
- Total Amount Received (MTD and MoM)
- Average Interest Rate (MTD and MoM)
- Average Debt-to-Income Ratio (DTI) (MTD and MoM)

Additionally, it distinguishes between 'Good Loans' and 'Bad Loans,' with specific indicators for each category, helping in the assessment of loan portfolio quality.


### Dashboard 2: Overview

!['Overview image'](![Screenshot 2025-01-21 110610](https://github.com/user-attachments/assets/9a0d63a5-f085-4827-850f-6f5c374017fc)


The Overview Dashboard visually represents various loan-related metrics through different chart types:
- Monthly Trends by Issue Date 
- Regional Analysis by State 
- Loan Term Analysis 
- Employment Length Analysis 
- Loan Purpose Breakdown
- Home Ownership Analysis 

These visualizations aid in identifying trends, seasonal patterns, and the distribution of loans across various categories.

### Dashboard 3: Details

!['Details image'](![Screenshot 2025-01-21 110642](https://github.com/user-attachments/assets/566af003-97a8-4e68-81f8-325519abc7df)


The Details Dashboard offers a detailed view of the loan data, providing a comprehensive and user-friendly interface for accessing vital loan metrics, borrower profiles, and performance data.

#### Data Fields and Usage
The data utilized in the dashboards comprise several fields, each serving a specific purpose in loan management and risk assessment:

- Loan ID: Unique identifier for loans.
- Address State: Borrower location for regional analysis.
- Employment Length: Indicates - employment stability.
- Employee Title: Job title for income source verification.
- Grade/Sub Grade: Creditworthiness and risk classification.
- Home Ownership: Housing status for financial stability assessment.
- Issue Date: Loan origination date.
- Loan Status: Current state of the loan for performance tracking.
- Purpose: Loan reason for segmentation and customization.
- Term: Loan duration.
- Verification Status: Status of financial information verification.
- Annual Income: Yearly earnings for creditworthiness.
- DTI: Debt burden relative to income.
- Instalment: Monthly repayment amount.
- Interest Rate: Cost of borrowing.
- Loan Amount: Principal amount borrowed.

Each field plays a crucial role in managing loans, assessing borrower risk, structuring loan terms, and making informed lending decisions.

## Implementation
The project required importing the dataset from Excel into SQL Server for analysis and visualization using Tableau. Dashboards were crafted using Tableau's powerful visualization tools and analytical capabilities, aligning with the specified requirements in the problem statement and utilizing the data dictionary to ensure precise field utilization.

## Data Validation
To ensure the accuracy and integrity of the data reflected in the dashboards, a thorough data validation process was undertaken. After the dataset was loaded into Tableau and from SQL Server database, the following measures were implemented:
- SQL Query Verification: Direct queries were executed against the SQL Server database to retrieve raw data. This dataset served as a benchmark, validating the accuracy and consistency of the information presented in the dashboards.

- Data Consistency Checks: The results from Tableau were compared against the SQL query results to ensure consistency. This step was critical to confirm that the data transformation and logic applied within Tableau did not alter the actual figures.

- KPI Logic Validation: The calculations and logic underlying the Key Performance Indicators (KPIs) were thoroughly reviewed. SQL scripts were employed to independently replicate the KPI calculations, ensuring the accuracy and reliability of the computations performed in Tableau.

- Cross-Verification with Source Data: The transformed data in Tableau was cross-verified with the source data from the SQL Server database. This step was crucial to confirm that all data transformations, including filtering, grouping, and aggregation, were correctly applied.

Through these validation steps, the project ensured that the Tableau dashboards accurately represent the data, and the insights derived are based on truthful and unaltered information. This rigorous validation process enhances the credibility of the dashboards and reinforces confidence in the data-driven decisions made using these tools.

## Conclusion
By incorporating robust data validation techniques, the Bank Loan Dashboard project establishes itself as a reliable and authoritative source for monitoring the bank’s loan activities. The project not only presents critical data through intuitive visualizations but also guarantees the precision of the information displayed, enabling the bank to make informed and assured strategic decisions with confidence.

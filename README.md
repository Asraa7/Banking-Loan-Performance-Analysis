# Banking Loan Performance Analysis

I developed an Excel dashboard analyzing 38,576 loans using Pivot Tables, Slicers, and KPIs, including default rate, recovery rate, branch-wise loan analysis, and monthly trends.


## Dashboard

### 1. KPI Cards
![KPI Cards](screenshots/kpi%20cards.png)

### 2. Slicers
![Slicers](screenshots/slizers.png)

### 3. Charts
![Charts](screenshots/charts.png)

### 4. Complete Dashboard
![Dashboard Overview](screenshots/dashboard-overview.png)


## Objective

To provide management with a clear overview of loan portfolio performance, including total lending, active and closed loans, charged-off loans, and payments received.

## Dataset

- **Total Records:** 38,576 loans
- **Period:** January–December 2021
- **Key Columns:** `id`, `address_state`, `purpose`, `issue_date`, `loan_status`, `loan_amount`, `total_payment`, `grade`
- **Loan Statuses:** Fully Paid, Current, Charged Off
- Personal fields such as employer names and member IDs were removed before publishing.

## Tools & Technologies

- Microsoft Excel
- Pivot Tables and Pivot Charts
- Interactive Slicers
- Excel Formulas: `SUM`, `COUNTIF`, `IF`

## Key Performance Indicators (KPIs)

| KPI | Value |
|---|---:|
| Total Loan Amount | 435,757,075 |
| Current + Fully Paid Loans | 33,243 |
| Active Loans | 1,098 |
| Closed Loans | 32,145 |
| Charged-Off Loans | 5,333 |
| Default Rate | 13.82% |
| Recovery Rate | 108.56% |

## Key Insights

- **Default Rate:** 13.82% of loans were charged off, representing approximately 65.5M in loan amount.
- **Recovery Rate:** 108.56%. This exceeds 100% because total payments include interest in addition to principal.
- **Monthly Lending Trend:** Loan amounts increased from approximately 25M in January to 54M in December.
- **Top States:** California (78.5M), New York (42.1M), and Texas (31.2M) recorded the highest loan amounts.
- **Top Loan Purpose:** Debt consolidation accounted for 18,214 loans, approximately 47% of all loans.

## Recommendations

- Monitor charged-off loans by loan grade to identify higher-risk segments.
- Review regional lending concentration to understand potential geographic risks.
- Monitor repayment performance for debt consolidation loans, the largest loan-purpose category.

## Helper Columns

- `EMI_status`: Categorizes loans as Closed, Active, or Default.
- `Outstanding Amount`: Calculated as loan amount minus total payment.
- `Default Status`: Identifies loans as Default or No Default.

## What I Learned

- Creating Pivot Tables and connecting them to KPI cards.
- Grouping dates by month to analyze lending trends.
- Using slicers to create interactive dashboards.
- Calculating and interpreting financial KPIs.
- Analyzing loan performance using Excel.

## How to Use

1. Download the Excel workbook from this repository.
[Download Banking Loan Performance Analysis (.xlsx)](Banking-Loan-Performance-Analysis.xlsx)

2. Open it in Microsoft Excel.
3. Navigate to the **Dashboard** sheet.
4. Use the slicers to filter data by grade, loan status, and purpose.

## Author

**Asraa Falak**

[GitHub Profile](https://github.com/Asraa7)


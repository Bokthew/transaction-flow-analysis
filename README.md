# Transaction Flow Analysis & Fund Leakage Detection

## Project Overview

This project focuses on analyzing customer transaction flows to understand fund movement patterns, identify potential fund outflows to other banks, and uncover business opportunities across different customer segments.

Using SQL-based data processing, the analysis examines incoming and outgoing transactions, identifies counterparties, evaluates transaction frequency and volume, and highlights potential fund leakage from the banking ecosystem.

## Business Objectives

The main objectives of this project are:

- Analyze customer transaction flows and financial activities.
- Identify incoming and outgoing fund movements.
- Detect potential fund outflows to other banks.
- Identify counterparties receiving or sending customer funds.
- Understand transaction patterns across customer segments.
- Support business teams in identifying potential funding and customer acquisition opportunities.
- Provide insights into industry-specific transaction activities.

## Analytical Scope

The analysis is organized into four main areas:

### 1. Corporate & Commercial Transaction Analysis

Focuses on analyzing transaction activities within the Corporate and Commercial customer segments.

Key activities:
- Extract and prepare transaction data.
- Generate monthly and yearly transaction summaries.
- Analyze customer transaction frequency and volume.
- Identify counterparties based on customer information.
- Perform counterparty name-matching analysis.
- Enrich customer and counterparty profiles with branch and regional information.
- Identify potential fund leakage to other banks.

### 2. Other Segment Transaction Analysis

Extends the analysis to other customer segments, including:

- Islamic Ecosystem
- Institutional Banking
- SME

Key activities:
- Prepare customer profile information.
- Extract detailed transaction records.
- Identify counterparty names and destination banks.
- Summarize transaction frequency and volume by counterparty.

### 3. Consolidated Transaction Analysis

Combines transaction analysis results across customer segments to provide a broader view of fund movements.

Key outputs:
- Consolidated transaction flow reports.
- Overall transaction summaries.
- Top destination banks.
- Top counterparties based on transaction activity.
- Cross-segment transaction insights.

### 4. Industry-Specific Analysis

Provides additional analysis for selected industries to understand their transaction behavior and potential business opportunities.

Industries covered:
- Hajj & Umrah
- Healthcare
- Gold
- Oil & Gas

## Methodology

The project follows a structured analytical workflow:

1. Data extraction and preparation.
2. Customer transaction aggregation.
3. Monthly and yearly transaction analysis.
4. Counterparty identification.
5. Counterparty name-matching.
6. Customer and counterparty profiling.
7. Transaction classification.
8. Fund flow reconciliation.
9. Potential fund leakage identification.
10. Consolidated reporting and industry analysis.

## Key Business Definitions

| Term | Description |
|---|---|
| Principal | The primary customer whose transaction activities are being analyzed. |
| Counterparty | An individual or entity involved in a transaction with the principal. |
| Incoming Transaction | Funds received by the principal. |
| Outgoing Transaction | Funds transferred from the principal. |
| BSI | Transactions associated with the bank's ecosystem. |
| Non-BSI | Transactions associated with other banks. |
| Own Account | Transactions identified as transfers between accounts belonging to the same customer. |
| Third Party | Transactions involving another individual or entity. |
| Fund Leakage | Potential outgoing funds transferred to accounts outside the bank's ecosystem. |
| Frequency | Number of transactions within a specified period. |
| Volume | Total monetary value of transactions. |
| CIF | Customer Information File, used as a customer identifier. |

## Expected Business Insights

The analysis is designed to support several business insights:

- Identification of customers with significant outgoing transactions to other banks.
- Identification of major destination banks receiving customer funds.
- Discovery of high-value counterparties.
- Understanding of customer transaction behavior.
- Identification of potential opportunities to retain customer funds.
- Identification of potential business opportunities across customer segments and industries.

## Technical Skills & Tools

- **SQL:** Data extraction, transformation, aggregation, joins, CTEs, and analytical queries.
- **Data Analysis:** Transaction flow analysis, customer segmentation, and counterparty analysis.
- **Business Intelligence:** Translating transaction data into actionable business insights.
- **Data Processing:** Data preparation, reconciliation, and reporting.

## Repository Structure

```text
transaction-flow-analysis/
│
├── README.md
│
├── sql/
│   ├── 01_base_transaction_extraction.sql
│   ├── 02_monthly_transaction_summary.sql
│   ├── 03_customer_yearly_summary.sql
│   ├── 04_counterparty_identification.sql
│   ├── 05_name_similarity_matching.sql
│   ├── 06_customer_branch_profiling.sql
│   ├── 07_counterparty_profiling.sql
│   ├── 08_leakage_reconciliation.sql
│   ├── 09_other_segment_analysis.sql
│   ├── 10_consolidated_reporting.sql
│   └── 11_sector_analysis.sql
│
└── documentation/
    ├── business-objectives.md
    ├── methodology.md
    └── data-dictionary.md
```

*Note: The repository structure represents a suggested organization of the analytical workflow.*

## Disclaimer

This repository is intended for educational and portfolio demonstration purposes.

All examples should use anonymized or synthetic data. No confidential banking information, customer-identifiable information, internal database structures, or proprietary business rules should be published without proper authorization.

The analytical methodology presented here is a demonstration of SQL-based transaction analysis and should not be interpreted as an official banking report.

## Author

**Rudi Julianto**

Data Analyst | SQL | Data Analytics | Banking Analytics

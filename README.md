# Personal Finance OS | PL-001

**Version:** 1.1 · **Platform:** Microsoft Excel · **Status:** Demonstration edition

An Excel-based personal finance management system that consolidates transactions, budgets, account records and trading journal analytics into one reporting environment.

## Business problem
Financial records can be fragmented across accounts and spreadsheets. Personal Finance OS centralizes records and provides reusable reporting for income, expenses, budget utilization and recorded trading activity.

## Features
- Dashboard with eight financial and trading KPIs.
- Structured transaction ledger with category-based classification and data validation.
- Budget tracking with planned and actual amounts, variance and utilization.
- Account master data and CRC starting-balance reporting.
- Trading journal with completed-trade counts, win/loss statistics and net P/L.
- PivotTable-driven reporting and charts.
- Configurable lookup lists and separate processing layer.

## Technical architecture
9 worksheets, 14 structured Excel tables, 8 PivotTables and 12 charts. Uses structured references, SUMIFS, SUMIF, IFERROR, calculated columns, named ranges, data validation and PivotTables.

| Worksheet | Purpose | Visibility |
|---|---|---|
| Dashboard | Financial and trading KPIs | Visible |
| Reports | Financial and trading visualizations | Visible |
| Transactions | Transaction records | Visible |
| Trading | Trade journal and statistics | Visible |
| Budget | Planned versus actual expenses | Visible |
| Accounts | Account master records | Visible |
| Categories | Category master data | Hidden |
| Processing | PivotTable reporting layer | Hidden |
| Settings | Configuration and lookup lists | Hidden |

## Getting started
1. Download `Personal_Finance_OS_v1.1_Demo.xlsx` from this repository after publication.
2. Open in a recent desktop version of Microsoft Excel.
3. Review the fictional demonstration records. Unhide configuration sheets if you want to inspect or customize the architecture.
4. Use Data > Refresh All after editing source data.
5. Review Dashboard and Reports.

## Demonstration QA

| Metric | Saved demonstration result |
|---|---:|
| Starting CRC balances | ₡370,000 |
| Income | ₡1,010,000 |
| Expenses | ₡489,000 |
| Net cash flow | ₡521,000 |
| Balance | ₡891,000 |
| Budget utilization | 92.26% |
| Completed trades | 6 |
| Win rate | 50% |
| Net trading P/L | $28 |
| Trading capital | $228 |

## Limitations
All financial and trading records are fictional. This workbook is a portfolio demonstration, not financial advice or a production accounting system. Budget actuals are manually maintained. The financial KPIs assume CRC transaction amounts; automatic currency conversion and transaction-level currency filtering are not implemented. The balance is a simplified starting-balance-plus-net-cash-flow calculation, not a reconciled bank balance. Trading capital uses starting capital plus net P/L and does not automatically account for subsequent deposits or withdrawals. The dashboard summarizes entered records rather than enforcing a reporting period. Recalculate and refresh reports after modifying inputs.

## Version history
See [CHANGELOG.md](CHANGELOG.md).

## Author
Sebastian Soto Ruiz — [GitHub profile](https://github.com/sebastiansotoruiz19)

Portfolio Lab — practical solutions, continuous improvement.

## Product Preview

### Dashboard
![Dashboard](Screenshots/dashboard.png)

### Financial Reports
![Financial Reports](Screenshots/financial-reports.png)

### Trading Reports
![Trading Reports](Screenshots/trading-reports.png)

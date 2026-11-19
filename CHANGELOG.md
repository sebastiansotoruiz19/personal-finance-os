# Changelog — PL-001

## v1.1 — 2026-11-18

### Fixed
- Completed-trade counts now use a calculated completion flag instead of counting preallocated IDs or empty-looking formula outputs.
- Repaired budget PivotTable layout and budget utilization KPI.
- Corrected spending-by-category filtering to include expenses only.
- Replaced the trading capital lookup with SUMIF and included net trading P/L.
- Separated net cash flow from starting-balance-based CRC balance calculations.
- Corrected chart scales and filtered starting account balances to CRC.
- Restored data validation lists.

### Improved
- Standardized PivotTable captions and internal names.
- Updated version labels and currency formatting.
- Hid configuration and processing sheets while retaining inspectable workbook architecture.
- Replaced personal records with fictional demonstration data and cleared historical PivotTable items.

### Validation
- Eight dashboard KPI values reconciled against the demonstration dataset.
- Six completed trades, three wins and three losses; net P/L of 28.
- Nine worksheets, fourteen tables, eight PivotTables and twelve charts retained.
- No stored Excel calculation errors found during release-candidate inspection.

## v1.0 — 2026-08-01
- Initial Personal Finance OS release: transactions, budgets, account records, trading journal, dashboards and reporting.

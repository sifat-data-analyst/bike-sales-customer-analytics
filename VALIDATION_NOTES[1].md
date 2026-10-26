# Validation Notes — Bike Sales & Customer Analytics

## Source workbook inspected
`BIKE SALES ANALYTICS DASHBOARD.zip` contained one Excel workbook with these worksheets:
- `RAW DATA`
- `CLEAN DATA`
- `EDA`
- `INFO_FINDER`
- `PIVOT_ANALYSIS`
- `DASHBOARD`

## Verified workbook structure and metrics
- Raw data: 1,026 data records and 13 columns (header plus 1,026 records).
- Clean data: 1,000 data records and 13 columns.
- Difference between raw and clean sheets: 26 records.
- Clean data missing values: 0 across the 13 fields.
- Duplicate IDs in clean data: 0.
- Bike purchase status: 481 `PURCHASED`, 519 `NOT PURCHASED`.
- Purchase rate: 481 / 1,000 = 48.1%.
- Gender counts in clean data: 511 `MALE`, 489 `FEMALE`.
- Region counts: North America 508, Europe 300, Pacific 192.
- Average income: 56,360 in original numeric units.
- Average age: 44.163 years.

## Important caveats
- The cleaned worksheet has a misspelled header `Maritial Status`; this was preserved in the workbook to avoid silently changing the original analysis. Consider correcting it to `Marital Status` in a future workbook revision.
- The workbook does not specify a currency for `Income`, so README uses the dataset's original numeric units without a currency symbol.
- The 26-record difference between raw and cleaned sheets is confirmed, but the precise reason for each exclusion has not been independently established.
- The values and counts above were checked against the workbook contents; dashboard formulas and all pivot-table calculations were not independently audited cell-by-cell.
- Verify the dataset license and public-sharing permission before publishing the workbook in a public repository.

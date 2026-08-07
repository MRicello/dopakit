# Dopakit - Money Tracker (Google Sheets)

## How to set up

Create a new Google Sheet. Create the tabs below. Share as "Anyone with link can view" and include the link in your Notion template.

---

## Tab 1: Income Tracker

### Columns
| A: Date | B: Client/Project | C: Description | D: Amount | E: Status | F: Tax Set-Aside (30%) | G: Notes |
|---------|-------------------|----------------|-----------|-----------|----------------------|-----|

### Formula for F2
```
=D2*0.3
```
(Drag down for all rows)

### Summary row (row 50)
| Total Income | Total Set Aside |
| =SUM(D2:D49) | =SUM(F2:F49) |

### Status options for column E
- Paid
- Invoiced
- Pending

### Tip
Every time you invoice, add a row. Every time you get paid, update to "Paid" and immediately transfer the Tax Set-Aside amount to a separate account. Don't touch that money. It's not yours. It's the tax office's.

---

## Tab 2: Monthly Overview

### Layout
| A: Month | B: Income | C: Expenses | D: Profit | E: Tax Reserve | F: Take-Home |
|-----------|----------|-------------|-----------|----------------|--------------|

### Formula for D2
```
=B2-C2
```

### Formula for E2
```
=B2*0.3
```

### Formula for F2
```
=D2-E2
```

Pre-fill months: January through December.

---

## Tab 3: Expense Log

### Columns
| A: Date | B: Category | C: Description | D: Amount | E: Receipt |

### Categories (pre-fill as dropdown)
- Software & Tools
- Marketing & Ads
- Office & Equipment
- Professional Services
- Education & Courses
- Travel & Meals
- Other

### Tip
Log expenses the same day. Don't batch this at the end of the month. Your ADHD brain will forget half of them.

---

## Tab 4: Tax Estimator

### Quarterly Estimate
For freelancers who pay estimated taxes quarterly.

| Q1 (Jan-Mar) | Q2 (Apr-Jun) | Q3 (Jul-Sep) | Q4 (Oct-Dec) |
|=SUMIF(Income!A:A,">="&DATE(year,1,1),Income!D:D)-SUMIF(Income!A:A,">="&DATE(year,4,1),Income!D:D)| [...same pattern for each quarter] |

### Annual Summary
| Total Income | Total Expenses | Net Income | Est. Tax (30%) | Already Set Aside | Remaining to Pay |
|=SUM(Income!D:D)|=SUM(Expenses!D:D)|=B2-B3|=B4*0.3|=SUM(Income!F:F)|=B5-B6|

---

## Tab 5: Feast or Famine Visualizer

### Monthly bar chart
- Select Monthly Overview tab
- Highlight columns A (Month) and B (Income)
- Insert → Chart → Column chart
- This shows your income pattern across the year

### Why this matters
ADHD brains are bad at seeing patterns over time. The chart tells you: "February was slow last year too. This is normal. Don't panic. It picks up in March."

---

## Color coding
- Green fill: Paid invoices
- Yellow fill: Invoiced, not yet paid
- Red fill: Overdue (past invoice date, not paid)
- Blue fill: Tax set-aside (don't touch this money)

---

That's it. Spend 20 minutes setting this up once. Then spend 5 minutes per week updating it. Your future self (the one filing taxes in April) will thank you.

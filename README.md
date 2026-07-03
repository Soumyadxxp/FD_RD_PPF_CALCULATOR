# Wealth Planner — FD, RD & PPF Calculator

A modern, browser-based financial planning application that enables users to estimate the maturity value and growth of **Fixed Deposits (FD)**, **Recurring Deposits (RD)**, and **Public Provident Fund (PPF)** investments. The application provides detailed investment schedules, interactive visualizations, and report export capabilities within a responsive, single-page interface.

---

## Overview

Wealth Planner is designed to simplify long-term investment planning by providing accurate financial projections using standard compounding formulas. It combines a clean user interface with interactive charts and detailed amortization schedules to help users better understand the growth of their investments.

The application runs entirely in the browser and requires no backend or installation.

---

## Features

### Investment Calculators

#### Fixed Deposit (FD)

- Lump-sum investment calculation
- Custom principal amount
- Adjustable annual interest rate
- Flexible investment tenure
- Multiple compounding frequencies
  - Monthly
  - Quarterly
  - Half-Yearly
  - Yearly
- Senior citizen interest rate adjustment
- Custom investment start date

#### Recurring Deposit (RD)

- Monthly deposit planning
- Adjustable interest rate
- Flexible investment duration
- Multiple compounding options
- Monthly balance schedule
- Maturity value estimation

#### Public Provident Fund (PPF)

- Annual contribution planning
- Configurable interest rate
- 15–30 year investment period
- Annual compounding
- Long-term wealth projection
- Annual contribution schedule

---

## Investment Insights

The application calculates and displays:

- Maturity Value
- Total Investment
- Total Interest Earned
- Effective Annual Rate
- Interest as a Percentage of Investment
- Detailed Deposit Schedule
- Wealth Growth Over Time

---

## Interactive Visualizations

### Growth Chart

- Investment growth timeline
- Responsive line chart
- Interactive tooltips
- Automatic scaling

### Portfolio Distribution

- Principal vs Interest breakdown
- Doughnut chart visualization
- Percentage-based comparison

---

## Export Options

Generate reports in multiple formats.

- PDF Export
- Microsoft Excel Export (.xlsx)
- Print-Friendly Schedule

---

## User Interface

- Modern responsive layout
- Mobile-first design
- Professional financial dashboard
- Interactive sliders
- Live calculations
- Clean typography
- Accessible form controls
- Responsive tables
- Smooth transitions and animations

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| HTML5 | Application structure |
| Tailwind CSS | User interface styling |
| JavaScript (ES6) | Business logic and calculations |
| Chart.js | Interactive charts |
| jsPDF | PDF report generation |
| SheetJS (XLSX) | Excel export |
| Google Fonts | Typography |

---
## Project Structure

```
Wealth-Planner/
│
├── index.html
├── README.md
```

---

## Browser Compatibility

The application supports all modern browsers, including:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox
- Safari
- Opera

---

## Responsive Design

Optimized for:

- Desktop
- Laptop
- Tablet
- Mobile devices

---

## Financial Calculations

### Fixed Deposit

Uses the compound interest formula:

```
A = P(1 + r/n)^(nt)
```

Where:

- A = Maturity Amount
- P = Principal
- r = Annual Interest Rate
- n = Compounding Frequency
- t = Time (Years)

---

### Recurring Deposit

Calculates monthly contributions using compound growth over the selected investment period.

---

### Public Provident Fund

Calculates maturity using the annuity due formula, assuming yearly deposits made at the beginning of each financial year.

---

## Key Features

- Live calculations
- Adjustable investment parameters
- Investment comparison
- Detailed yearly or monthly schedules
- Exportable reports
- Interactive financial charts
- Responsive dashboard
- Professional user interface

---

## Author

**Soumyadeep Basu**

---

## Disclaimer

The calculations provided by this application are intended for educational and planning purposes only. Actual returns may differ based on financial institution policies, applicable taxes, prevailing interest rates, and regulatory changes. Users should consult qualified financial professionals before making investment decisions.

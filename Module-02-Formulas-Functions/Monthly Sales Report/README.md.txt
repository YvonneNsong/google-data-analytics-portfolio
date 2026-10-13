# 📊 Case Study: Monthly Sales Report (Adventure Works)

## 📌 Overview
This project tracks and analyzes the April sales results for one of Adventure Works' most popular products, the **A2Mountain Bike Frame**. The calculations were performed in Microsoft Excel using core statistical and mathematical functions to generate key summary metrics for a monthly sales review meeting.

---

## 🧮 Summary of Calculations & Formulas

The analysis covers daily sales data from April 1st to April 30th (rows 4 to 33). The calculated summary metrics in cell range **C35:C40** are structured as follows:

| Cell | Metric / Description | Excel Formula | Result / Value | Notes |
| :--- | :--- | :--- | :--- | :--- |
| **C35** | **Total Revenue** | `=SUM(E4:E33)` | **$25,570,000** | Sum of daily US dollar amounts accrued in Column E |
| **C36** | **Total Units Sold in Month** | `=SUM(C4:C33)` | **127,850** | Total volume of bike frames sold in Column C |
| **C37** | **Lowest Number of Units Sold** | `=MIN(C4:C33)` | **2,560** | Single-day minimum sales volume |
| **D37** | **Date of Minimum Sales** | *(Manual Entry)* | **2023-04-30** | Date corresponding to the minimum sales day |
| **C38** | **Largest Number of Units Sold** | `=MAX(C4:C33)` | **4,921** | Single-day peak sales volume |
| **D38** | **Date of Peak Sales** | *(Manual Entry)* | **2023-04-16** | Date corresponding to the maximum sales day |
| **C39** | **Days in Month** | `=COUNT(B4:B33)` | **30** | Counts numeric date serial entries in Column B |
| **C40** | **Average Daily Revenue** | `=AVERAGE(E4:E33)` | **$852,333.33** | Mean daily sales revenue (Accounting format) |

---

## 💡 Key Learnings & Technical Takeaways

* **Function Selection & Precision Range:** Ensured accurate cell range selection (`C4:C33`, `E4:E33`, `B4:B33`) rather than accepting default range suggestions from Excel's AutoSum feature.
* **Date Entry Handling:** Applied the `COUNT` function to date serial numbers in Column B to dynamically count total reporting days in the month.
* **Automatic Formatting Inheritance:** Observed how Excel automatically applied the **Accounting ($)** currency format to revenue totals (`C35`) and averages (`C40`) based on source formatting in Column E.
* **Outlier Identification:** Utilized `MIN` and `MAX` functions to quickly isolate minimum and peak demand dates across the reporting period.

---

## 🖼️ Preview
![Monthly Sales Report Screenshot](./screenshots/monthly-sales-report.png)
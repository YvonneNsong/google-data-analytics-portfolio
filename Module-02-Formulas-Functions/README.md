\# Module 2: Advanced Excel Formulas and Functions



\## Overview

This project applies core formulas, financial calculations, and logical functions learned in the \*\*Google Data Analytics Professional Certificate (Preparing Data for Analysis with Microsoft Excel)\*\*. 



\## Project Scenario: Profit and Margin Analysis

In this exercise, a business dataset containing product details, wholesale costs, purchase quantities, and sales metrics was analyzed to determine profitability and overall profit margins.



\## Key Formulas Implemented

\* \*\*Purchase Cost (Cell G4):\*\* 

&#x20; `=F4\*E4` — Calculates total wholesale expenditure by multiplying items purchased by wholesale cost.

\* \*\*Total Shipping Costs (Cell H4):\*\* 

&#x20; `=F4\*$P$1` — Uses an absolute reference to calculate shipping fees based on a constant rate.

\* \*\*Total Costs (Cell I4):\*\* 

&#x20; `=G4+H4` — Combines purchase and shipping costs.

\* \*\*Retail Price (Cell J4):\*\* 

&#x20; `=(E4+$P$1)\*1.5` — Determines individual retail pricing incorporating a 50% markup over base costs.

\* \*\*Revenue \& Profit (Cells L4 \& M4):\*\* 

&#x20; `=K4\*J4` and `=L4-I4` — Computes total revenue from items sold and subtracts total costs to find net profit.

\* \*\*Overall Profit Margin (Cell P3):\*\* 

&#x20; `=(L201-I201)/L201` — Evaluates overall business profitability as a percentage.



\## Tools \& Techniques Used

\* \*\*Functions \& Operators:\*\* Mathematical operators (`\*`, `+`, `-`), cell referencing.

\* \*\*Absolute Cell References:\*\* Utilizing `$P$1` to maintain constant values during autofill operations.

\* \*\*Data Automation:\*\* Applying Autofill and double-click shortcuts across large column ranges.



\---

\*📁 Completed workbook and verification screenshots are available in this directory.\*


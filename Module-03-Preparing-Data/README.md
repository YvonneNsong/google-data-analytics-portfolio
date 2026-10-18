# Module 3: Prepare Data for Exploration - Reseller Information

## 📌 Project Overview
This project focuses on data preparation and text cleaning using Microsoft Excel. In this case study, raw reseller data was processed to fix formatting inconsistencies, eliminate trailing/leading spaces, standardize text capitalization, and combine name or location fields to ensure data integrity before analysis.

## 🎯 Objectives
* Clean and format inconsistent text entries within the reseller dataset.
* Standardize text capitalization (Upper, Lower, Proper case).
* Remove unnecessary spacing and clean raw strings.
* Combine and extract specific text strings using text manipulation functions.

## 🛠️ Functions & Formulas Used

| Function | Description | Example Syntax |
| :--- | :--- | :--- |
| **`TRIM`** | Removes extra spaces from text, leaving only single spaces between words and no leading/trailing spaces. | `=TRIM(D2)` |
| **`UPPER`** | Converts all letters in a text string to uppercase. | `=UPPER(E2)` |
| **`LOWER`** | Converts all letters in a text string to lowercase. | `=LOWER(E2)` |
| **`PROPER`** | Capitalizes the first letter in each word of a text string and converts all other letters to lowercase. | `=PROPER(D10)` |
| **`CONCAT`** | Joins several text strings into one text string (or combines multiple cells). | `=CONCAT(E2, " ", F2)` |
| **`LEFT`** | Extracts a specified number of characters from the start (left) of a text string. | `=LEFT(E2, 3)` |

## 📸 Screenshots & Visuals
* **Data Cleaning & Text Transformation:** Located in the `screenshots/` directory, showing the applied string functions and corrected formatting across columns.

## 🚀 Key Takeaways & Insights
* **Data Consistency:** Text cleaning functions like `TRIM` and `PROPER` are essential for eliminating duplicate categories caused by capitalization discrepancies (e.g., "California" vs. "CALIFORNIA").
* **Efficient Merging:** Using `CONCAT` and string extraction functions (`LEFT`) allows analysts to build custom identifiers or clean up messy records swiftly.

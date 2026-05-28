##  Google Play Store Analysis - Task 6

## Objective

Analyze the trend of app installs over time across different categories using a stacked area chart after applying the required filters.

---

## Filters Applied

App Name should NOT start with X, Y, Z
App Name should NOT contain “S”
Category should start with E, C, or B
Reviews > 500
Installs must be numeric and cleaned properly

---

## Tools & Libraries Used

Python
Pandas
NumPy
Matplotlib

---

## Files Included

TASK-6.ipynb
Task-6 Report.pdf
README.md

---

## Steps Performed

* Loaded the dataset
* Handled missing values and duplicate records
* Converted date column into datetime format
* Cleaned Installs and Reviews columns into numeric format
* Applied all required filters
* Filtered categories starting with E, C, and B
* Grouped data by date and category
* Calculated total installs for each category over time
* Pivoted data for stacked area visualization
* Created stacked area chart using Matplotlib
* Analyzed category-wise contribution to total installs over time

---

## Output

A stacked area chart showing:

* Trend of total installs over time
* Category-wise contribution (E, C, B categories)
* Growth comparison between categories

---

## Author

Prasanthi Velpuri

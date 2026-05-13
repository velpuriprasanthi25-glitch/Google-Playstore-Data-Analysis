#  Task 2 Report: Interactive Choropleth Map of Google Play Store Data

## 1. Introduction

With the increasing global usage of mobile applications, understanding the geographical distribution of app installs is crucial. This task focuses on building an interactive choropleth map to visualize install patterns across different app categories.

---

## 2. Objective

The objectives of this task are:

* To analyze install distribution across categories
* To visualize data using an interactive choropleth map
* To highlight high-performing categories

---

## 3. Dataset Description

The dataset includes app-related information from the Google Play Store.

### Key Attributes:

* **Category** – App classification
* **Installs** – Number of downloads
* **Region/Country** – Geographical mapping (if applicable)

---

## 4. Data Preprocessing

The following preprocessing steps were applied:

* Converted install counts into numeric format
* Removed missing and inconsistent values
* Eliminated duplicate records
* Prepared data for visualization

---

## 5. Filtering Criteria

The dataset was filtered based on:

* Exclusion of categories starting with **A, C, G, S**
* Selection of **Top 5 categories** based on installs

---

## 6. Methodology

The analysis followed these steps:

1. Grouped data by category
2. Calculated total installs per category
3. Selected top-performing categories
4. Created an **interactive choropleth map using Plotly**
5. Highlighted categories exceeding **1 million installs**

---

## 7. Results and Findings

* Successfully visualized install distribution across categories
* Identified high-performing app categories
* Interactive map improved understanding of data patterns
* Categories with installs above 1 million were clearly highlighted

---

## 8. Special Condition

The visualization is programmed to run only between **6 PM and 8 PM IST**.

---

## 9. Tools and Technologies Used

* Python
* Pandas
* Plotly
* Jupyter Notebook

---

## 10. Conclusion

This task demonstrates the use of interactive visualization techniques to present complex data effectively. The choropleth map provides valuable insights into app performance across categories.

---

## 11. Future Scope

* Add real geographical country-wise mapping
* Enhance interactivity with filters
* Integrate with dashboards
* Use real-time data updates

---

## 12. Author

**Velpuri Prasanthi**
B.Sc Data Science

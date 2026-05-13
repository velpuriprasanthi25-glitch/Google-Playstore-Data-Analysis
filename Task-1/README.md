# Task 1 Report: Category-wise Installs Analysis of Google Play Store Data

## 1. Introduction

The rapid growth of mobile applications has led to an increase in the availability of apps across various categories on the Google Play Store. This task focuses on analyzing app data to identify the most popular categories based on install counts. The analysis helps in understanding user preferences and market trends.

---

## 2. Objective

The primary objective of this task is to:

* Analyze the Google Play Store dataset
* Identify top-performing app categories based on installs
* Apply data filtering techniques to refine the dataset
* Visualize the results using a grouped bar chart

---

## 3. Dataset Description

The dataset used for this analysis contains information about various applications available on the Google Play Store.

### Key Attributes:

* **Category** – Type of application
* **Installs** – Number of downloads
* **Rating** – User rating of the app
* **Size** – Application size
* **Last Updated** – Date of last update

---

## 4. Data Preprocessing

To ensure accuracy and consistency, the following preprocessing steps were performed:

* Converted the **Installs** column into numeric format by removing special characters
* Handled missing values in relevant columns
* Removed duplicate records
* Standardized column formats for analysis

---

## 5. Data Filtering Criteria

The dataset was filtered using the following conditions:

* Applications with **Rating ≥ 4.0**
* Applications with **Size ≥ 10 MB**
* Applications updated in the month of **January**

These conditions ensure that only high-quality and relevant applications are included in the analysis.

---

## 6. Methodology

The analysis was carried out using Python and involved the following steps:

1. Grouped the dataset by **Category**
2. Calculated total installs for each category
3. Sorted categories based on install counts
4. Selected the **Top 10 categories**
5. Visualized the results using a **grouped bar chart**

---

## 7. Results and Findings

* The analysis identified the **top 10 categories** with the highest number of installs
* Certain categories dominate the Play Store in terms of user downloads
* High-rated and recently updated apps tend to perform better
* Larger-sized applications (≥10 MB) still attract significant user engagement

---

## 8. Special Condition

The visualization is programmed to execute only between **3 PM and 5 PM IST**, ensuring controlled display of results based on time constraints.

---

## 9. Tools and Technologies Used

* Python
* Pandas
* Matplotlib / Seaborn
* Jupyter Notebook

---

## 10. Conclusion

This task successfully demonstrates the process of data cleaning, filtering, and visualization to extract meaningful insights from a real-world dataset. The findings provide a clear understanding of app category performance and user preferences in the Google Play Store ecosystem.

---

## 11. Future Scope

* Extend analysis to include more time periods
* Incorporate additional features such as reviews and pricing
* Build interactive dashboards for better visualization
* Apply machine learning models for prediction

---

## 12. Author

**Velpuri Prasanthi**
B.Sc Data Science

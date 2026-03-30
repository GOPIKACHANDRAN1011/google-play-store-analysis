# 📊 Google Play Store Data Analysis

## 📌 Project Overview

This project focuses on analyzing the Google Play Store dataset to uncover insights about app performance, user engagement, and market trends. The analysis includes data cleaning, transformation, visualization, and advanced analytics such as time-series trends and sentiment analysis.

---

## 🎯 Objectives

* Analyze app categories based on installs, ratings, and reviews
* Identify top-performing app categories
* Understand the relationship between app size, rating, and installs
* Compare free vs paid app performance
* Perform time-series analysis to detect growth trends
* Combine user sentiment with app data for deeper insights

---

## 🛠️ Tools & Technologies Used

* **Python**
* **Pandas** – Data cleaning and manipulation
* **NumPy** – Numerical operations
* **Plotly** – Interactive data visualization
* **Jupyter Notebook**

---

## 🧹 Data Cleaning & Preprocessing

* Removed missing and duplicate values
* Filtered invalid ratings (>5)
* Converted columns like **Installs, Price, Size** into numeric format
* Handled inconsistent values (e.g., "Varies with device")
* Extracted and formatted date features

---

## 🔧 Feature Engineering

* Created **Estimated Revenue = Installs × Price**
* Extracted **Month/Year** from date
* Converted Android version into numeric format
* Categorized apps for comparison (e.g., GAME vs Other)

---

## 📈 Key Analyses Performed

### 1️⃣ Category-Level Analysis

* Identified top categories based on installs and reviews
* Compared average ratings and engagement

### 2️⃣ Free vs Paid App Comparison

* Analyzed installs and revenue differences
* Evaluated which model performs better across categories

### 3️⃣ Time-Series Analysis

* Monthly aggregation of installs
* Calculated **Month-over-Month (MoM) growth**
* Highlighted significant growth (>20%)

### 4️⃣ Sentiment Analysis

* Merged app data with user reviews
* Filtered apps based on sentiment subjectivity
* Analyzed user perception along with performance

### 5️⃣ Advanced Filtering & Insights

* Applied multiple real-world filters (installs, size, rating, etc.)
* Focused on high-performing and relevant apps

---

## 📊 Visualizations

* 📌 Bar + Line charts (Reviews vs Ratings)
* 📌 Choropleth map (Category distribution – simulated)
* 📌 Bubble chart (Size vs Rating vs Installs)
* 📌 Time-series line charts (growth trends)
* 📌 Area charts (category-wise install trends)

---

## 🔍 Key Insights

* Some categories have **high installs but lower ratings**, indicating quality issues
* Free apps generally have higher installs, but **paid apps generate revenue differently**
* Certain categories show **sudden growth spikes**, indicating trends or seasonal demand
* User sentiment plays a key role in **app success and engagement**

---

## ⚠️ Limitations

* Revenue is **estimated**, not actual
* Geographic visualization uses **simulated mapping** due to lack of location data

---

## 🚀 Conclusion

This project demonstrates how raw app data can be transformed into meaningful insights using data analysis techniques. It highlights trends, user behavior, and business opportunities in the mobile app market.

---

## 💼 Author

**Gopika Chandran**
Aspiring Data Analyst

---

## ⭐ Future Improvements

* Add real-time dashboards (Power BI / Tableau)
* Use machine learning for prediction
* Integrate real geographic data for accurate mapping

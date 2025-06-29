# Swiggy Restaurants Analysis Dashboard 🛵🍽️

## 📊 Project Overview

This project is a comprehensive dashboard built using **Power BI** to analyze restaurant data from **Swiggy**, one of India’s largest food delivery platforms. The aim is to uncover insights about restaurant performance, food category popularity, order trends, revenue generation, and delivery logistics across different Indian cities.

The dataset used for this analysis was sourced from **Kaggle**.

---

## 🛠️ Tools Used

- **Jupyter Notebook (Python):** For initial data exploration and cleaning.
- **Power Query (Power BI):** For additional transformation, data shaping, and merging.
- **Power BI Desktop:** For designing and visualizing the interactive dashboard.

---

## 📁 Data Preprocessing Steps

1. **Initial Data Checks**:  
   - Checked for missing values and anomalies using Python in Jupyter Notebook.
   - Removed rows with missing or zero prices, ratings, and other invalid entries.

2. **Data Cleaning & Transformation**:
   - Cleaned column names for readability.
   - Grouped and formatted columns like `restaurant`, `area`, and `city` for better clarity.

3. **Power Query Work**:
   - Performed final merges based on **food category** and **food type**.
   - Ensured consistency in data types and categorical labels before visualization.

---

## 📌 Key Features in the Dashboard

### 📈 Overview KPIs
- **Average Delivery Time**
- **Total Number of Orders**
- **Total Number of Restaurants**
- **Total Revenue**
- **Average Rating**
- **Average Order Price**

### 🍽️ Category Analysis
- Most popular food categories by count.
- Average pricing across food categories.
- Number of restaurants by category.

### 🏙️ City-Level Insights
- Average restaurant ratings per city.
- City-wise restaurant distribution.
- Average delivery time by city.

### 🏆 Top Rankings
- Top 10 restaurants by total ratings.
- Areas generating the highest revenue.
- High-value order areas.

---

## 💡 Insights Derived

- Identified top 5 cities contributing to over *65%* of total revenue
- Revealed that **Indian cuisine** accounted for *58%* of total restaurant listings
- Uncovered *35%* higher pricing in **continental food** compared to average order prices
- Discovered that **Chembur** (Mumbai) and **Ashok Nagar** (Bangalore) generated *20%* higher revenue than the city average
- Found **Kolkata's** delivery time to be *40%* longer than the national average, while **Ahmedabad** was *25%* faster
- Ranked **The Bowl Company** as the #1 restaurant by ratings, receiving *15%* more reviews than the next best

---

## 📚 Dataset Source

The original dataset was downloaded from **[Kaggle – Swiggy Restaurants Dataset](https://www.kaggle.com/datasets/abhijitdahatonde/swiggy-restuarant-dataset)**.  
It includes data about:
- Restaurant names, locations, and food types
- Ratings and review counts
- Delivery time and Price information

---


## 🚀 How to Run

1. Download or clone the repository.
2. Open the `.pbix` file using **Power BI Desktop**.
3. Explore the visuals and filter by city or food category using the slicers.
4. Use the dashboard interactively to dive deeper into any segment.

---

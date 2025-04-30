# 🏠 Airbnb Data Analysis

This project explores Airbnb listing data with the goal of understanding **host activity**, **regional trends**, **pricing patterns**, and **customer behavior** in various neighborhoods.

---

## 📊 Objectives

- Identify the **top 20 most active hosts** by listing count
- Analyze the **distribution of price**, **availability**, and **room type**
- Segment listings by **neighbourhood group** and **room category**
- Visualize **host dominance**, **revenue potential**, and **guest access patterns**
- Perform **statistical aggregation** using `groupby()` and `.agg()` to reveal insights
- Use **matplotlib** and **seaborn** to create compelling visualizations

---

## 📁 Files Included

- `Airbnb_Exercise_Student_Facing_0423 (3)-Copy1 (1).ipynb` – main Jupyter Notebook with data exploration, cleaning, and visualization

---

## 🔍 Key Insights

### 🎯 Top Host Analysis
- Identified hosts with the highest number of listings using `.value_counts()` and `groupby()`
- Created a **bar chart** showing property count by host

### 💰 Price Behavior
- Mean, count, and standard deviation of price were calculated by **neighbourhood group**
- Bar charts revealed pricing variability across locations like Manhattan, Brooklyn, and Queens

### 🛏️ Room Type Trends
- Most listings are **entire home/apt**, but **private rooms** remain common in budget districts
- Room type influences both **price** and **availability**

### 📅 Availability Distribution
- Certain neighborhoods show higher **365-day availability**, indicating business-driven listings

---

## 🛠 Tools & Libraries Used

- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📈 Sample Visuals

- `Top 20 Hosts by Number of Listings`  
- `Price Distribution by Neighborhood Group`  
- `Boxplot of Price vs Room Type`  
- `Mean Price by Neighbourhood Group (Bar Chart)`

---

## 🧼 Data Cleaning Highlights

- Removed nulls and duplicates
- Converted `host_id` and `price` to appropriate types
- Aggregated listing counts, availability, and mean pricing per host

---


---





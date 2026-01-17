# Data Aggregation in Data Mining (Time & Spatial Aggregation)

## 📌 Project Description
This project demonstrates the concept of **Data Aggregation in Data Mining** using **Python and Pandas**.  
It explains how raw data can be summarized and analyzed using different aggregation techniques, including **basic aggregation**, **time-based aggregation**, and **spatial aggregation**.

This project is created as part of **MSc Big Data Analytics practical work** and is useful for both **practical exams and interviews**.

---

## 🎯 Objectives
- To understand the concept of **data aggregation**
- To perform aggregation using Pandas
- To implement **time aggregation** (monthly, quarterly, yearly)
- To implement **spatial aggregation** (region-wise, city-wise)
- To analyze summarized data for decision-making

---

## 🛠 Tools & Technologies
- Python
- Pandas
- Jupyter Notebook / Python Script

---

## 📂 Dataset Overview
The dataset used in this project contains the following columns:

- **Region** – Geographical region (North, South, East, West)
- **City** – City name
- **Product** – Product category
- **Sales** – Sales amount
- **Quantity** – Quantity sold
- **Date** – Date of transaction

The dataset is manually created for learning and demonstration purposes.

---

## 🔹 Types of Aggregation Implemented

### 1️⃣ Basic Data Aggregation
- Sum of sales by region
- Average sales and quantity by product
- Count of sales records
- Minimum and maximum sales values

### 2️⃣ Time Aggregation
Time-based aggregation is performed using the **Date** column:
- Monthly sales aggregation
- Quarterly sales aggregation
- Yearly sales aggregation

### 3️⃣ Spatial Aggregation
Spatial aggregation is performed using location-based attributes:
- Sales aggregated by region
- Sales aggregated by city
- Sales aggregated by region and city

---

## 📊 Key Pandas Functions Used
- `groupby()`
- `sum()`
- `mean()`
- `count()`
- `agg()`
- `set_index()`
- `resample()`
- `reset_index()`

---

## 🧠 Learning Outcomes
After completing this project, you will be able to:
- Perform aggregation operations on datasets
- Analyze data based on time and location
- Understand real-world data mining aggregation techniques
- Apply Pandas for data analysis tasks

---

## 📌 Use Cases
- Sales analysis and reporting
- Business performance analysis
- Regional and city-wise comparisons
- Time-series trend analysis

---

## ▶️ How to Run the Project
1. Clone the repository
2. Install Pandas if not already installed:
   ```bash
   pip install pandas

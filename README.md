# 🍔 Food Delivery Orders Analysis

An end-to-end **Food Delivery Data Analysis project** using **Python, Pandas, NumPy, Matplotlib, Seaborn, and Power BI** to explore customer orders, delivery performance, food categories, payment methods, ratings, promotional usage, and geographic sales patterns.

---

## 📌 Project Overview

This project analyzes **1,200 food delivery orders** to identify patterns in customer behavior, order value, delivery performance, food preferences, and area-wise sales.

The analysis was performed using **Python for Exploratory Data Analysis (EDA)** and **Power BI for interactive business intelligence and visualization**.

---

## 🎯 Project Objectives

The main objectives of this project are to:

- Analyze overall food delivery order patterns
- Understand customer and order behavior
- Analyze delivery time and delivery performance
- Identify high-performing food categories
- Analyze sales across different areas
- Explore payment method usage
- Examine customer ratings
- Analyze promotional usage
- Identify daily order trends
- Build an interactive Power BI dashboard

---

## 📊 Dataset Overview

The dataset contains **1,200 orders** with the following columns:

| Column | Description |
|---|---|
| `Order_ID` | Unique order identifier |
| `Customer_ID` | Customer identifier |
| `Order_Date` | Date of the order |
| `City` | Customer city |
| `Area` | Customer area |
| `Food_Category` | Category of food ordered |
| `Restaurant_Type` | Type of restaurant |
| `Payment_Method` | Payment method used |
| `Order_Amount` | Total order amount |
| `Delivery_Minutes` | Delivery time in minutes |
| `Rating` | Customer rating |
| `Promo_Used` | Whether a promotional offer was used |

---

## 🔍 Exploratory Data Analysis

The Python notebook performs multiple stages of exploratory analysis, including:

### 📦 Dataset Inspection
- Dataset shape and structure
- Column information
- Data types
- Descriptive statistics

### 🧹 Data Quality Checks
- Missing value analysis
- Duplicate record detection
- Data consistency checks
- Payment method standardization

### 📈 Business Analysis
- Order amount analysis
- Delivery time analysis
- Customer analysis
- Food category analysis
- Area-wise order amount analysis
- Payment method analysis
- Customer rating analysis
- Promotional usage analysis
- Daily order trends

---

## 🚚 Delivery Performance

Delivery time was analyzed using the `Delivery_Minutes` column.

### Average Delivery Time

**38.91 minutes**

The project also creates a **Delivery Speed** classification based on delivery time:

- ⚡ **Fast**
- 🕐 **Normal**
- 🐢 **Delayed**

This classification is used to explore delivery performance across the dataset.

---

## 👥 Customer Analysis

The dataset contains:

**420 unique customers**

Customer-related analysis helps understand order behavior and overall activity within the dataset.

---

## 💰 Area-wise Sales Analysis

The analysis identifies the areas with the highest total order amounts.

### Top 5 Areas by Order Amount

| Rank | Area | Total Order Amount |
|---|---|---:|
| 1 | Gulshan-e-Iqbal | 164,300 |
| 2 | DHA | 122,700 |
| 3 | North Nazimabad | 113,010 |
| 4 | Clifton | 101,570 |
| 5 | PECHS | 99,440 |

---

## 🍕 Food Category Analysis

The project analyzes total order amounts across different food categories.

| Food Category | Total Order Amount |
|---|---:|
| Desi | 346,500 |
| Pizza | 310,000 |
| Chinese | 262,700 |
| Burgers | 209,720 |
| Healthy | 99,300 |
| Beverages | 74,680 |
| Bakery | 70,160 |

---

## 📅 Daily Order Trends

Daily order activity was analyzed using the `Order_Date` column to understand how order volume changes over time.

A line chart was created in Python to visualize the daily order trend.

---

## 📊 Power BI Dashboard

The project also includes an interactive **Power BI dashboard** built from the food delivery dataset.

The Power BI component provides a business-focused view of the analyzed data and allows users to explore the dataset through interactive visualizations.

📁 Power BI File:

`Food_Delivery_Orders.pbix`

---

## 🛠️ Tools & Technologies

### Programming & Data Analysis
- 🐍 Python
- 🐼 Pandas
- 🔢 NumPy

### Data Visualization
- 📊 Matplotlib
- 📈 Seaborn

### Business Intelligence
- 📊 Microsoft Power BI

### Development Environment
- Jupyter Notebook
- Git
- GitHub

---

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Loading
     ↓
Data Inspection
     ↓
Data Quality Checks
     ↓
Data Cleaning & Transformation
     ↓
Exploratory Data Analysis
     ↓
Business Insights
     ↓
Power BI Visualization
     ↓
Interactive Dashboard

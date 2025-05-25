# 📊 Comcast Telecom Complaints Data Analysis

This project analyzes customer complaints received by Comcast Corporation, aiming to uncover trends, identify service issues, and deliver actionable insights by processing and visualizing complaint data submitted across various channels and U.S. states.

## 📌 Objectives

1. Data Cleaning  
2. ETL (Extract, Transform, Load)  
3. Exploratory Data Analysis (EDA)  
4. Data Visualization  
5. State-wise and Time-based Complaint Insights  

---

## 🛠️ Python Libraries Used

- **Pandas** – Data manipulation  
- **NumPy** – Numerical operations  
- **Matplotlib** – Data visualization   

---

## 📁 Dataset

The dataset used is: `Comcast_telecom_complaints_data.csv`

It contains the following key columns:

- Ticket #
- Customer Complaint
- Date, Time
- Received Via (e.g., Customer Care Call, Internet)
- State, City, Zip code
- Status (Closed, Solved, Pending, Open)
- Filing on Behalf of Someone

---

## 📊 Key Analysis Performed

### ✅ Data Preprocessing

- Converted date columns to datetime objects
- Converted zip codes to string to prevent formatting errors
- Simplified complaint status into a new column: `new_status` (`Closed` vs `Open`)

### 📈 Exploratory Analysis & Visualizations

- Top 10 complaint-receiving states 
- Daily complaint volume
- State-wise complaint status (Closed/Open)
- Monthly complaint trends
- Stacked bar chart of complaints by state and status
---
## 📸 Sample Visualizations

- 📅 Daily complaints trend  
- 🏆 Top 10 complaint-receiving states  
- 📊 Stacked bar: State-wise Closed vs Open  
- 📈 Monthly trend of complaints

### Example 1: Monthly Complaint Trend  
[🔍 View Monthly Trend Chart](sample_images/monthly_trend.png)

### Example 2: State-wise Complaints (Closed vs Open)  
[🔍 View State-wise Complaints Chart](sample_images/statewise_stacked_bar.png)

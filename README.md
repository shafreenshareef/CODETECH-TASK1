## BIG-DATA-ANALYSIS

COMPANY: CODETECH IT SOLUTIONS

NAME: SHAIK SHAFREEN SHAREEF

INTERN ID : CT08DM215

DOMAIN: DATA ANALYTICS

TASK: BIG DATA ANALYSIS

DURATION: 8 WEEKS

MENTOR: NEELA SANTOSH

  # DESCRIPTION

## 🔍 Objective

The objective of this project is to demonstrate **scalability in big data processing** using **PySpark**. We analyze a real-world transportation dataset — NYC Yellow Taxi trip records — to uncover key business and operational insights such as peak ride hours, revenue trends, passenger behavior, and geographic patterns.



## 📂 Dataset

- **Name:** NYC Yellow Taxi Trip Records – January 2025  
- **File:** `yellow_tripdata_2025-01.parquet`  
- **Format:** Parquet (columnar, efficient for big data)  
- **Source:** [NYC TLC Official Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)  
- **Size:** ~200 MB  
- **Records:** Over 7 million taxi trips in New York City



## 🧰 Tools & Technologies Used

| Tool / Library | Purpose |
|----------------|---------|
| **Google Colab** | Cloud-based development and execution |
| **PySpark** | Distributed processing of large-scale trip data |
| **Python** | Core scripting and analysis language |
| **Spark SQL Functions** | For data aggregation, transformation, and filtering |
| **OS Library** | To check dataset size in megabytes |



## 💻 Platform

- **Notebook Platform:** Google Colab  
- **Execution Engine:** Apache Spark via PySpark  
- **Version Control & Hosting:** GitHub



## 🔑 Key Steps in the Project

### 1. Library Installation & Spark Initialization
- Installed PySpark in Colab
- Created Spark session for analysis

### 2. Dataset Loading
- Loaded `yellow_tripdata_2025-01.parquet` using `spark.read.parquet()`

### 3. Data Cleaning
- Removed rows with:
  - Invalid fare amounts or trip distances (≤ 0)
  - Passenger count ≤ 0 or > 6
  - Null timestamps
  - Dropoff time earlier than pickup time

### 4. Feature Engineering
- Calculated **trip duration in minutes**
- Extracted **pickup hour** and **day of week**
- Derived additional business indicators

### 5. Core Analysis
- 🚕 Top 10 busiest pickup and dropoff zones
- 📅 Trip count by hour and day of week
- 👥 Average fare by passenger count
- 💵 Total revenue generated
- 💳 Payment method distribution
- 💰 Average tip on credit card rides
- 📉 Percentage of zero-tip credit card rides

### 6. Advanced Analysis
- ⏱️ Trip duration statistics (avg, min, max)
- 📈 Revenue trends by hour of day
- 💸 Top revenue-generating pickup zones
- 💡 High tip behavior analysis (> $5)
- 🚨 Detection of unusually long trips (outliers)

### 7. Dataset Size Estimation
- File size retrieved programmatically: ~200 MB

### 8. Spark Session Termination
- `spark.stop()` used to gracefully shut down the Spark context



## 🌐 Application & Use Cases

This project demonstrates how big data tools like PySpark can be used to generate actionable insights from transportation datasets. Applicable use cases include:

| Use Case | Description |
|----------|-------------|
| 🚖 Fleet Optimization | Identify busiest zones and times for taxi allocation |
| 📈 Revenue Analysis | Track hourly or daily earnings trends |
| 👥 Customer Behavior | Understand tipping habits and payment preferences |
| 🧼 Data Quality & Cleaning | Learn to clean and filter real-world data |
| 🎓 Big Data Education | Hands-on project for students & analysts learning PySpark |



## 📌 Conclusion

This project shows how **PySpark and Google Colab** can be combined to:
- Efficiently process millions of records  
- Derive time-based, location-based, and value-based insights  
- Demonstrate real-world scalability with a high-volume dataset

Key outcomes include:
- Cleaned and structured taxi trip data
- Hourly trip volume trends and revenue breakdown
- Tip behavior and payment type statistics
- Duration-based and distance-based outlier detection

  # OUTPUT
![Image](https://github.com/user-attachments/assets/2aa26513-6d9d-40e1-883b-607c7f0f8e0f)
![Image](https://github.com/user-attachments/assets/5eea03d3-3a67-4732-a860-b31c5b2f50f1)
![Image](https://github.com/user-attachments/assets/49676aa6-c4f4-45bf-8fe4-599b41fac066)
![Image](https://github.com/user-attachments/assets/fcefa0de-951c-42af-9f6a-b6d46eb304a7)
![Image](https://github.com/user-attachments/assets/218ef49d-1d4e-4fc4-a92f-b4d4dffbeb74)
![Image](https://github.com/user-attachments/assets/6b8ad643-eba0-4947-8576-45d5f951534b)
![Image](https://github.com/user-attachments/assets/131a0088-1817-4535-bac9-c5f1f163dcf0)
![Image](https://github.com/user-attachments/assets/47038ab9-1c82-4172-9d87-c54ca5f4747c)
![Image](https://github.com/user-attachments/assets/e6ba1fbf-5954-414d-aa89-aa8c629aefea)
  



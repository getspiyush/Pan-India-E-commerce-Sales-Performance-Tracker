# Pan-India-E-commerce-Sales-Performance-Tracker
This project focuses on building a dynamic Power BI Dashboard which transform raw e-commerce sales data into actionable business intelligence. The primary goal is to provide the owner with a single, comprehensive view of their national online sales performance, enabling data-driven decision-making.
# e-commerce Sales Analysis Dashboard

## Project Overview

This Power BI project delivers a comprehensive **Online Sales Analysis Dashboard** for an e-commerce business, to monitor and analyze its sales performance across India. The objective is to convert complex sales data into clear, intuitive visualizations that empower the owner to track key metrics, understand geographical sales distribution, and identify growth opportunities.

## 🎯 Project Objective

The owner  requires a dashboard to:
1.  **Track and monitor** their online sales performance in real-time or near-real-time.
2.  **Analyze sales trends** across various dimensions (time, geography, product, etc.).
3.  **Gain a pan-India view** of their e-commerce operations.

## ✨ Dashboard Features & Key Insights

The final Power BI dashboard provides the following critical insights:

* **Key Performance Indicators (KPIs):** Total Revenue, Total Orders, Average Order Value (AOV), and Profit Margin.
* **Geographic Sales Map:** A visual breakdown of sales performance by State and City across India.
* **Product/Category Performance:** Analysis of the best-selling categories and products to inform inventory and marketing strategy.
* **Slicer Functionality:** Interactive filters for  States and Product Category to enable deep-dive analysis.

## 🛠️ Tools and Technologies

| Category | Tool / Language | Purpose |
| :--- | :--- | :--- |
| **Data Visualization** | Microsoft Power BI Desktop | Primary tool for modeling, analysis, and report creation. |
| **Data Cleaning & Transformation** | Power Query (M) | Merging and cleaning the raw sales data files (`Orders.csv`, `Details.csv`). |
| **Data Modeling & Calculation** | DAX (Data Analysis Expressions) | Creating custom measures like Total Revenue, Profit %, and AOV. |
| **Data Source** | CSV Files | The initial dataset used for the project. |

## 📁 Data Model

The project utilizes two primary data files:
1.  **`Orders.csv`:** Contains order-level details (Order ID, Date, Customer info).
2.  **`Details.csv`:** Contains line-item details for each order (Order ID, Product ID, Sales, Quantity, Profit).

These two tables were connected using the common key **Order ID**

## 🚀 How to View the Project

1.  **Clone the repository:**
    ```bash
    git clone [Your Repository URL Here]
    ```
2.  **Download Power BI:** Ensure you have **Microsoft Power BI Desktop** installed.
3.  **Open the Report:** Locate and open the `.pbix` file .
4.  **Interact:** Use the slicers and filters on the report pages to explore the data dynamically.


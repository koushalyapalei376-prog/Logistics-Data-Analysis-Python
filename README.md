# Logistics Data Analysis Using Python

## Project Overview

This project analyzes logistics shipment data using Python to understand delivery performance, shipment delays, carrier performance, warehouse performance, destination performance, transportation costs, and transit time.

The analysis provides operational insights that can help identify areas requiring further investigation.

## Business Objectives

* Measure overall shipment and delivery performance.
* Analyze shipment delays.
* Compare carrier performance.
* Compare warehouse performance.
* Analyze destination-level performance.
* Understand shipping cost and shipment weight.
* Analyze the relationship between distance and transit time.
* Identify operational areas for further investigation.

## Dataset

The dataset contains **2,000 shipment records** and **11 columns**, including:

* Shipment ID
* Origin Warehouse
* Destination
* Carrier
* Shipment Date
* Delivery Date
* Weight
* Cost
* Status
* Distance
* Transit Days

## Tools & Technologies

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Analysis Performed

### Data Analysis

* Data loading and exploration
* Data type validation
* Missing-value checks
* Duplicate checks
* Data-quality validation

### KPI Analysis

* Total shipments
* Delivered shipments
* Delayed shipments
* Delivery rate
* Delay rate
* Average transit time
* Average shipping cost
* Average shipment weight
* Average cost per mile

### Operational Analysis

* Carrier performance
* Warehouse performance
* Destination performance
* Monthly shipment trends
* Highest-cost shipments
* Longest-transit shipments
* Shipment status analysis

### Relationship Analysis

* Weight vs. shipping cost
* Distance vs. transit time
* Correlation analysis

## Key Findings

* Total shipments analyzed: **2,000**
* Delivered shipments: **1,648**
* Delivery rate: **82.40%**
* Delayed shipments: **199**
* Delay rate: **9.95%**
* Average transit time: **4.18 days**
* Average shipping cost: **205.16**
* Average shipment weight: **30.18 kg**
* Average cost per mile: **0.1783**

### Carrier Findings

* USPS recorded the lowest observed delay rate at **7.19%**.
* DHL recorded the highest observed delay rate at **13.88%**.

### Warehouse Findings

* Warehouse_NYC recorded the lowest observed delay rate at **5.88%**.
* Warehouse_HOU recorded the highest observed delay rate at **11.79%**.

### Destination Findings

* Miami recorded the lowest observed delay rate at **6.50%**.
* Boston recorded the highest observed delay rate at **16.81%**.

### Correlation Findings

* Weight vs. Cost correlation: **0.02**
* Distance vs. Transit Days correlation: **0.76**

The distance and transit-time correlation indicates a relatively strong positive linear relationship in this dataset. Correlation represents association and does not by itself establish causation.

## Business Recommendations

* Investigate the reasons for differences in carrier delay rates.
* Review warehouse processes associated with higher delay rates.
* Investigate routes and operational conditions for destinations with higher delay rates.
* Monitor long-distance shipments and transit-time performance.
* Track cost per mile across carriers, routes, warehouses, and destinations.
* Analyze additional factors that may influence shipping costs because shipment weight alone has a very weak linear relationship with cost.
* Develop a regular logistics dashboard for ongoing performance monitoring.

## Project Files

| File                                             | Description                            |
| ------------------------------------------------ | -------------------------------------- |
| `logistics_analysis.ipynb`                       | Complete Python data analysis notebook |
| `logistics_shipments_dataset.csv`                | Shipment dataset                       |
| `Week1_Logistics_Strategic_Planning_Report.docx` | Strategic planning report              |
| `requirements.txt`                               | Python dependencies                    |
| `.gitignore`                                     | Git ignored files                      |

## Project Status

**Completed:** Data analysis, KPI calculation, operational analysis, visualization, correlation analysis, business insights, and recommendations.

## Author

**Koushalya Palei**

MCA | Data Analytics


# Hospital Data Analysis Dashboard (Excel BI)


<img src="./images/Dashboard New.png">

## Project Overview
This repository contains an advanced **Excel-based Business Intelligence** dashboard built to analyze patient care efficiency. The primary objective is to equip healthcare executives with data-driven visibility into **number of patients**, **average age patients**,  **average patient lengths of stay (LOS)**, **avearge ratings for services offered**, and **resource utilization**. 

By transforming raw medical logs into an automated spreadsheet solution, this project demonstrates the use of Power Query, Pivot tables, and interactive dashboard design using native Excel features.

## Business Problem & Objectives
Hospital administrators frequently struggle with fragmented data, making it difficult to understand their patient and balance bed capacity limits against the need to maximize healthcare service revenue. 

This Excel solution solves these issues by delivering:

* **Operational Efficiency Tracking:** Monitoring Average Length of Stay (LOS) of patients to uncover discharge bottlenecks.

* **Conditional Disease Mapping:** Isolating top conditions affecting patients.

* **Patient Demographics Analysis:** Correlating patient ages and medical diagnoses to forecast emergency room workloads and routine clinical demands.

## Tech Stack & Features

* **Core Engine:** Microsoft Excel (Advanced PivotTables, PivotCharts).

* **Data Transformation Engine:** Power Query / Get & Transform (ETL process, data type corrections, and conditional column generation).

* **Formula Architecture:** Advanced Excel formulas (`XLOOKUP`, and nested logical functions) for data validation.

* **Interactivity:** Dynamic Slicers, Timelines, and conditional formatting rules for a true application-like user experience.


## Actionable Business Insights* 

* **Heart attack and Fractured legs are the most common conditions.** Fractured legs & Heart attack.

- Fractured legs;  

This can be because with the average age being 54, most people especially females experience a decline in bone density during the post menopausal phase.

- Heart attack;

Sedentary lifestyle, unhealthy diet, metabolic issues could be a cause for why heart attack is prominent, among older adults, plaque build up on the walls of the arteries over time.

**Segmentation by Admision Period:** The hospital handles a lot of cases that require the patient to stay for a long time indicating a need for close monitoring of patient's health condition. 

Here is the updated, tailored README template designed specifically to showcase high-level Excel Business Intelligence and data modeling skills.

## Strategic Recommendations
1.**Discharge Protocol Standardization:** Implement early clinical assessment tracks for department groups experiencing high average lengths of stay to free up beds faster.

2. **Resource Allocation Shifts:** Reallocate idle nursing and administrative staff from lower-volume regional branches over to high-demand emergency departments.3. 

**Payer-Mix Optimization:** Launch an auditing strategy within high-cost care channels to reduce operational costs and stabilize fading profit margins.

## How to Interact with the Workbook
1. Clone this repository to your desktop machine:
   ```bash
   git clone https://github.com
   ```
2. Open the `.xlsx` file using **Microsoft Excel 2019 or newer** (for full Power Query compatibility).

3. Ensure macros/data connections are enabled if prompted.

4. Use the visual **Slicers** (e.g., City, Diagnosis, or Year) on the dashboard sheet to filter the entire workbook instantly.5. Click **Data > Refresh All** to automatically re-run the Power Query script if the underlying source data is updated.





 

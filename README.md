# Optimizing UberEats Delivery Times  

This repository contains a class project for **BUS 127 – Introduction to Quality Control (UC Riverside)**. Our team (Daniel Rojas, Ryan Huang, Riley Menter, Tyler Pak) simulated and analyzed UberEats delivery times in Southern California to explore how factors such as **distance, weather, traffic, and time of day** impact delivery efficiency.  

## Project Overview  
- **Goal**: Analyze UberEats delivery efficiency and identify patterns/inefficiencies in delivery times.  
- **Methodology**:  
  - Simulated 50 delivery observations in **R** using probability-based distributions for distance, time, weather, and traffic.  
  - Exported results to an `.xlsx` for further analysis.  
  - Performed exploratory analysis, regression modeling, and control charts to assess process stability.  
- **Key Findings**:  
  - Delivery distance and time show a moderately strong correlation (R² ≈ 0.59).  
  - Control charts indicate an **out-of-control process**, highlighting inefficiencies in delivery times.  
  - Weather and traffic introduce subtle but measurable effects on delivery efficiency.  

## Repository Contents  
- `Simulated_Delivery_Data.Rmd` - R Markdown file used to generate and analyze the simulated dataset.  
- `Uber_Delivery_Wb.xlsx` - Excel workbook used for EDA and control charts  
- `BUS127_Written_Report.pdf` - Final written report summarizing methodology, analysis, and recommendations.  

## Reproducibility Note  
The Excel file reflects an earlier simulation run before we fixed the random seed (slightly different data). The CSV and RMarkdown are now reproducible with `set.seed(42)`, ensuring consistency going forward.  

## Project Takeaways  
This project demonstrates how **simulation, reproducibility, and statistical quality control tools** can be applied to real-world problems like last-mile delivery. It also highlights the importance of fixing random seeds to ensure reproducibility across multiple analysis tools (R, Excel, etc.).  

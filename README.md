# Excel-Based Data Analysis Dashboard: Job Titles, Skills & Salaries

## Overview

This project is a comprehensive data analysis dashboard created entirely using **Microsoft Excel**. It explores how different **job titles**, **skills**, and **countries** (India vs. Non-India) impact **median salaries**. 

With dynamic filtering options and interactive visualizations, this dashboard helps users explore:
- The most in-demand job roles
- Top 10 skills required for each job
- How location affects salary
- Which skills lead to better-paying roles

---

## Data Cleaning & Preprocessing

All cleaning and transformation were done within Excel, using manual and built-in features:

- Removed **null values** and **irrelevant columns** to ensure clean and focused data.
- **Standardized entries** like job titles and country names for consistency.
- Extracted **skills** from text fields to create individual records for analysis.
- Ensured **salary values** were formatted uniformly for accurate aggregation.
- Categorized the data into **India** and **Non-India** groups for country-level comparisons.

---

## Features & Visualizations

### 1. Median Salary by Job Title
- Calculated **median salary** for each job role.
- Found the skills per job. 
- Displayed using a **scatter plot** for visual clarity.
- Gives quick insight into which roles pay higher.

### 2. Country-Based Salary Analysis
- Split data into **India** and **Non-India** categories.
- Used a **slicer** to filter country data interactively.
- Helped in understanding location-based salary differences.

### 3. Top 10 Skills for Each Job Title
- Identified and displayed the **top 10 most in-demand skills** per selected job title and country.
- Used **Pivot tables** for dynamic updates.
- Helps users discover what skills are needed for specific roles.
- Found the Skill Likelihood for each skill. 

### 4. Skill-Based Salary & Likelihood
- Calculated **median salary per skill** for the top 10 skills under a job title.
- Computed **likelihood** of each skill (how often it appears).
- Column graph displays both **median salary** and **likelihood** side by side.
- Controlled by a **Job-Title slicer** that updates everything in real-time.

---

## Interactivity

All components in the dashboard are **connected and interactive**:
- Selecting a country updates, skills, likelihood data and salary visuals.
- Selecting a job title updates related skills, salaries, and likelihood data.
- Users can explore the data by mixing and matching filters without any coding.

---

## Tools Used

- **Microsoft Excel**
  - Power Query (for cleaning and shaping data)
  - Pivot Tables (for grouping and aggregating)
  - Slicers (for filters)
  - Charts: Scatter Plot and Bar Graph

---

## Folder Structure

ob-Skills-Salary-Dashboard
- Dataset.xlsx # Cleaned and formatted dataset
- Dashboard_Final.xlsx # Interactive Excel dashboard
- README.md # Project documentation (this file)

  
---

## Purpose of the Project

The goal was to build a **fully functional, no-code data analysis dashboard** using Excel alone, proving that meaningful insights can be created without programming languages or BI tools.

This project is useful for:
- Students and beginners in data analytics
- Job seekers exploring in-demand skills
- HR professionals for salary benchmarking
- Anyone curious about how geography and skills affect pay

---

## Outcomes

- Built a real-time, fully interactive dashboard in Excel.
- Identified patterns between job roles, required skills, and salary trends.
- Demonstrated how Excel can be a powerful tool for data analysis without writing a single line of code.

---

## Acknowledgements

Special thanks to everyone who provided feedback and supported this Excel-based project. This analysis was done solely using built-in features of Excel, emphasizing the power and accessibility of spreadsheet tools for real-world insights.

---

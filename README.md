# Crime-Analysis-Report

# Crime Analysis Using Microsoft Excel

## Project Overview

**Crime Analysis** is a data analytics project developed using **Microsoft Excel** to analyze crime incidents, identify crime patterns, understand geographical and temporal trends, and generate meaningful business insights from a large crime dataset.

The project demonstrates an end-to-end data analysis workflow in Excel, starting from **raw data importation and data cleaning**, followed by **data transformation, Pivot Table analysis, chart creation, and dashboard development**.

The primary objective of this project is to transform raw and inconsistent crime records into a structured analytical dataset and present the results through an interactive and visually understandable Excel dashboard.

Although tools such as Power BI can provide more advanced interactivity and visualization capabilities, this project demonstrates that **Microsoft Excel alone can be effectively used to perform complete data analysis and create professional dashboards** when the data is properly cleaned, transformed, summarized, and visualized.

---

## Project Objectives

The major objectives of this project are:

* Analyze crime incidents across different cities, districts, and states.
* Identify the most frequently occurring crime types.
* Analyze crime severity levels.
* Understand crime distribution across different geographical locations.
* Identify crime trends across years and months.
* Analyze crime occurrence by time of day.
* Examine the types of weapons associated with incidents.
* Analyze case status and case resolutions.
* Understand arrest patterns.
* Analyze property loss caused by criminal incidents.
* Identify important patterns and trends through Pivot Tables.
* Create meaningful charts and graphs for visual analysis.
* Develop an Excel dashboard to present key findings in a simple and understandable format.
* Demonstrate the complete data analytics workflow using Excel.

---

## Dataset Overview

The original dataset contains **5,250 crime records** and **33 columns** in the raw-data stage.

After data cleaning and transformation, the final analytical dataset contains **5,050 records** and **43 columns**.

The dataset contains information related to:

* Crime incidents
* Crime types
* Districts
* Cities
* States
* Incident dates and times
* Police officers
* Suspects
* Victims
* Weapons
* Crime severity
* Case status
* Case resolution
* Number of arrests
* Property loss
* Online reporting

---

## Project Structure

The Excel workbook is organized into four major sections:

### 1. RAW DATA

The **RAW DATA** sheet contains the original dataset before performing any major cleaning or transformation.

It contains:

* 5,250 records
* 33 original columns
* Crime information
* Location information
* Officer information
* Suspect information
* Victim information
* Case information
* Financial/property-loss information

Keeping the raw data separately makes it possible to preserve the original dataset and compare it with the cleaned version.

---

### 2. CLEANED DATA

The **CLEANED DATA** sheet contains the processed dataset used for analysis.

The cleaning process included:

* Removing duplicate/unwanted records.
* Handling missing and blank values.
* Standardizing inconsistent values.
* Cleaning categorical fields.
* Correcting inconsistent date and time information.
* Separating date and time components.
* Creating Year, Month, Day, and Hour fields.
* Creating calculated/helper columns for analysis.
* Standardizing officer, suspect, and victim names.
* Cleaning phone-number-related fields.
* Standardizing severity values.
* Cleaning case-related information.
* Preparing numerical fields for analysis.
* Creating a structured dataset suitable for Pivot Tables and visualization.

The cleaned dataset contains **5,050 records and 43 analytical columns**.

---

## Data Transformation

To make the dataset easier to analyze, additional columns were created from the original data.

Examples include:

* `Date`
* `Year`
* `Month_Num`
* `Month`
* `Day_Num`
* `Time`
* `HOUR`
* `Crime_count`
* `Officer_Name`
* `Suspect_name`
* `Victim_name`
* `Victim_Ph_No`

These transformations made it easier to perform time-based and categorical analysis using Excel Pivot Tables.

---

# Pivot Table Analysis

Pivot Tables were used as the main analytical tool for summarizing the cleaned crime dataset.

Different dimensions were analyzed, including:

### Crime Type Analysis

Determined which types of crime occur most frequently.

### District Analysis

Compared the number of reported crimes across different districts.

### City Analysis

Analyzed crime distribution across different cities.

### State Analysis

Compared crime incidents across states.

### Severity Analysis

Examined the distribution of:

* Low
* Medium
* High
* Critical
* Unknown

severity levels.

### Monthly Analysis

Analyzed crime incidents across different months to identify periods with higher crime activity.

### Yearly Analysis

Compared crime activity across different years.

### Time Analysis

Used the extracted hour field to understand when crime incidents were most frequently reported.

### Weapon Analysis

Analyzed the weapons associated with crime incidents.

### Case Status Analysis

Examined cases based on their status, such as:

* Open
* Closed
* Pending
* Under Investigation
* Resolved
* Unknown

### Resolution Analysis

Analyzed outcomes such as:

* Arrest Made
* Warning Issued
* Case Dismissed
* No Arrest
* Unknown

### Property Loss Analysis

Analyzed the financial impact associated with crime incidents.

### Arrest Analysis

Examined the number of arrests associated with reported incidents.

---

# 📊 Dashboard

The final **Excel Dashboard** presents the major findings from the Pivot Table analysis through charts and visual summaries.

The dashboard was designed to provide a quick overview of crime patterns without requiring the user to manually inspect the underlying dataset.

The dashboard includes visual analysis of areas such as:

* Total Crime Incidents
* Crime by Type
* Crime by District
* Crime by City
* Crime by State
* Crime Severity
* Crime by Month
* Crime by Year
* Crime by Time
* Case Status
* Case Resolution
* Weapon Usage
* Arrest Analysis
* Property Loss

The use of charts and graphical elements makes it easier to identify patterns, comparisons, and trends.

---

# Key Findings

Based on the cleaned dataset, several meaningful patterns were identified.

### 1. Crime Distribution by District

**North** recorded the highest number of incidents among the districts in the dataset, followed by **South** and **Central**.

This indicates that crime activity is not evenly distributed geographically and that some districts may require greater attention when allocating law-enforcement resources.

### 2. Crime Distribution by City

**Riverside** had the highest number of recorded incidents among the cities, followed by **Centerville** and **Lakewood**.

This provides an important geographical perspective for identifying locations with comparatively higher crime activity.

### 3. Most Common Crime Type

**Drunk & Driving** was the most frequently recorded crime type in the cleaned dataset, followed by **Sexual Assault** and **Trespassing**.

This helps identify the crime categories contributing most significantly to the overall incident volume.

### 4. Crime Severity

**Medium** severity incidents represented the largest severity category, followed closely by **Critical** incidents.

This shows that a significant portion of reported incidents falls into moderate-to-serious severity categories.

### 5. Case Resolution

**Arrest Made** was the most common resolution recorded in the dataset.

However, the presence of categories such as **Unknown**, **Case Dismissed**, and **No Arrest** indicates that case outcomes are diverse and may require additional investigation when evaluating overall resolution effectiveness.

### 6. Property Loss

The cleaned dataset contains approximately **$107.29 million in recorded property loss** among the available property-loss values.

This demonstrates that crime analysis can provide insights not only into incident frequency but also into the potential financial impact associated with crime.

---

# Business / Analytical Insights

Although crime analysis is not traditionally a commercial business problem, the same analytical techniques used in business intelligence can be applied to law-enforcement and public-safety data.

This project can help decision-makers:

* Identify high-crime districts and cities.
* Prioritize law-enforcement resources.
* Understand common crime categories.
* Identify periods of increased crime activity.
* Monitor case resolution patterns.
* Analyze arrest trends.
* Understand the financial impact of crime.
* Support data-driven public-safety planning.
* Identify areas requiring further investigation.
* Improve reporting and operational decision-making.

---

# Tools & Technologies

### Microsoft Excel

Excel was the primary tool used throughout the project.

Key Excel features used:

* Data Import
* Data Cleaning
* Data Transformation
* Excel Tables
* Sorting and Filtering
* Formulas
* Data Validation
* Date & Time Transformation
* Pivot Tables
* Pivot Charts
* Charts & Graphs
* Dashboard Development
* Data Analysis

---

# Project Workflow

```text
Raw Crime Dataset
       ↓
Data Importation
       ↓
Data Cleaning
       ↓
Data Transformation
       ↓
Missing / Inconsistent Value Handling
       ↓
Date & Time Extraction
       ↓
Creation of Analytical Columns
       ↓
Pivot Table Analysis
       ↓
Charts & Graphs
       ↓
Excel Dashboard
       ↓
Crime Insights & Findings
```

---

# Why Excel?

This project intentionally uses **Microsoft Excel as the primary analytics and visualization tool**.

Excel is widely used in organizations for:

* Data cleaning
* Reporting
* Business analysis
* Ad-hoc analysis
* KPI reporting
* Pivot Table analysis
* Dashboard creation

The project demonstrates that a well-structured Excel workflow can transform thousands of raw records into meaningful insights and an easy-to-understand dashboard without requiring Power BI.

---

# Future Enhancement – Power BI

The current project was completed using Excel.

A future version of this project can be developed using **Microsoft Power BI** to provide additional interactive capabilities such as:

* Drill-through analysis
* Cross-filtering
* Dynamic DAX measures
* Interactive maps
* Advanced KPI cards
* Hierarchical drill-down
* Automated data refresh
* More advanced data modeling
* Interactive geographic analysis

Therefore, the project can be extended from an **Excel-based static/interactive dashboard** into a more advanced **Power BI crime analytics solution**.

---

# Skills Demonstrated

Through this project, I demonstrated practical knowledge of:

* Data Cleaning
* Data Transformation
* Data Analysis
* Exploratory Data Analysis
* Excel
* Pivot Tables
* Pivot Charts
* Dashboard Development
* Data Visualization
* Date & Time Analysis
* Categorical Analysis
* KPI Development
* Trend Analysis
* Geographic Analysis
* Business/Operational Insights
* Data Storytelling

---

# Project Outcome

The project successfully transformed a large and initially inconsistent crime dataset into a structured analytical dataset and Excel dashboard.

The analysis provides a clear view of **where crimes occur, which crimes are most common, when incidents occur, how severe they are, how cases are resolved, and what financial impact they may have**.

This project demonstrates my ability to take a raw dataset through the complete data analytics lifecycle and convert it into meaningful information that can support data-driven decision-making.

---

## Author

**Pradeep Reddy**

# 📊 Website Performance Dashboard - Power BI Project

## 🚀 Introduction
In the digital age, analyzing website performance is essential for improving user experience and increasing conversion rates. This project presents an interactive Power BI dashboard that visualizes website performance metrics, helping stakeholders make data-driven decisions.

## 📂 Dataset Description
The dataset `website_performance_analytics.csv` contains the following variables:
- **Visitor_ID**: Unique visitor identifier
- **Page_Views**: Number of pages viewed per session
- **Session_Duration**: Duration of the session (in seconds)
- **Bounce_Rate**: % of visitors who left after one page
- **Conversion_Rate**: % of visitors who completed desired action
- **Traffic_Source**: Source of the visitor (Direct, Organic, Paid, etc.)
- **Exit_Pages**: Page where the visitor exited
- **Load_Time**: Page load time
- **Visitor_Type**: New or Returning visitor
- **Location**: Visitor's geographic location

## 🎯 Project Objectives
✅ Design an interactive Power BI dashboard titled **"Website Performance Dashboard"**  
✅ Visualize website metrics to:
- Understand visitor behavior
- Identify conversion drivers
- Analyze performance by traffic source and location

## 📈 Dashboard Features
- **KPI Cards**: Average Page Views, Session Duration, Bounce Rate, and Conversion Rate
- **Donut Charts**: 
  - Average Bounce Rate by Visitor Type
  - Average Conversion Rate by Visitor Type
- **Bar Chart**: Average Conversion Rate by Traffic Source
- **Map Chart**: Average Conversion Rate by Location
- **Table**: Top 100 Visitors sorted by Conversion Rate (includes Visitor_ID, Page_Views, Session_Duration, Conversion_Rate)
- **Filter**: Exit Page filter for interactive analysis

## 🛠 Tools Used
- Power BI Desktop
- CSV Dataset
- Data Modeling & Visualization Techniques

## 📌 Data Formatting & Preparation
- Converted Bounce Rate and Conversion Rate to percentage format (0 decimal points)
- Set Location field as "City" data category
- Summarized KPI values as averages
- Sorted the visitor table by Conversion Rate (Descending)

## 📂 Project Structure

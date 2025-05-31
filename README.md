# 📊 Work Absenteeism Analytics Dashboard

A comprehensive HR analytics project analyzing employee absenteeism patterns using SQL Server Management Studio (SSMS) for data processing and Power BI for visualization.

## 🎯 Project Overview

This project provides deep insights into workplace absenteeism through interactive dashboards and data analysis. The system tracks absenteeism patterns across various dimensions including time, employee categories, health conditions, and work-related factors to help HR teams make data-driven decisions.

## ✨ Key Features

### **📅 Time and Trends Analysis**
- **Monthly Patterns**: Tracks absenteeism hours across 12 months, revealing seasonal trends with notable peaks in month 3 (765 hours) and month 7 (720 hours)
- **Weekly Distribution**: Analyzes absenteeism by day of the week, showing Monday having the highest absenteeism (1490 hours) and Friday the lowest (553 hours)
- **Seasonal Filtering**: Interactive filters for Fall, Spring, Summer, Winter, and Unknown periods

### **🏥 Comprehensive Reason Tracking**
The system categorizes absenteeism into multiple health and work-related reasons:
- Medical consultation (148 cases)
- Dental consultation (112 cases)
- Physiotherapy (79 cases)
- Diseases of the musculoskeletal system and connective tissue (55 cases)
- Various other medical and administrative reasons
- Total of 740 tracked incidents across all categories

### **👥 Employee Demographics and Categories**
- **BMI Categories**: Analysis across Healthy Weight (294 cases), Obese (204 cases), Overweight (272 cases), and The 54 (7.3%) categories
- **Social Factors**: Breakdown by social drinking habits (False: 688 cases, True: 420 cases) and smoking patterns (False: 700 cases, True: 40 cases)
- **Work Load Analysis**: Correlation between transportation expenses and average daily work load with scatter plot visualization

## 🛠️ Technical Implementation

### **🗄️ Backend (SQL Server)**
- Data storage and processing using SQL Server Management Studio (SSMS)
- Complex queries for aggregating absenteeism data across multiple dimensions
- Data transformation and cleaning procedures
- Efficient data modeling for optimal dashboard performance

### **📈 Frontend (Power BI)**
- Interactive dashboard with multiple visualization types
- Real-time filtering capabilities with seasonal controls
- Cross-filtering between different chart components
- Professional dark theme design for better readability
- Responsive layout optimized for different screen sizes

## 📋 Key Metrics

- **Average Absenteeism**: 6.92 hours per incident
- **Total Absenteeism Hours**: 5,124 hours tracked
- **Peak Day**: Monday (1,490 hours)
- **Lowest Day**: Friday (553 hours)
- **Most Common Reason**: Medical consultation (148 cases)
- **Highest Monthly Peak**: Month 3 with 765 hours (14.93% of total)
- **BMI Distribution**: Healthy Weight employees show highest absenteeism (294 cases)

## 🎨 Dashboard Components

### **⏰ Time Analysis Section**
- **Monthly Trend Line Chart**: Shows absenteeism patterns throughout the year with clear peaks and valleys
- **Weekly Pattern Analysis**: Line chart displaying day-of-week breakdown with Monday showing highest absence
- **Interactive Season Filter**: Dropdown menu for filtering data by Fall, Spring, Summer, Winter, and Unknown periods

### **🔍 Reasons and Patterns Section**
- **Comprehensive Reason Bar Chart**: Horizontal bar chart displaying all 15+ absenteeism categories
- **Medical Focus**: Clear categorization of health-related vs administrative absences
- **Transportation vs Work Load Scatter Plot**: Correlation analysis with trend line showing relationship between commuting expenses and daily work load

### **👤 Employee Analytics Section**
- **BMI Distribution Pie Charts**: Visual breakdown of employee health categories
- **Social Habits Analysis**: Pie charts for drinking and smoking patterns
- **Key Performance Indicators**: Large metric displays for average absenteeism time and total hours

### **📊 Summary Statistics Panel**
- **HR Analytics Header**: Professional branding with HR icon
- **Key Insights Text**: Automated insights showing highest and lowest performing periods
- **Percentage Breakdowns**: Clear statistical summaries of major findings

## 💡 Data Insights

The analysis reveals several important patterns:
- **🔴 Monday Effect**: Significantly higher absenteeism at the beginning of the work week (1,490 hours)
- **🟢 Friday Recovery**: Lowest absenteeism on Fridays (553 hours), suggesting end-of-week motivation
- **🏥 Health Focus**: Medical-related absences dominate the reasons, indicating the importance of employee health programs
- **📈 Seasonal Variations**: Clear seasonal patterns with month 3 showing highest absenteeism (765 hours)
- **⚖️ BMI Correlation**: Healthy weight employees paradoxically show highest absenteeism rates

## 🔧 Technologies Used

![SQL Server](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

- **Database**: Microsoft SQL Server
- **Development Environment**: SQL Server Management Studio (SSMS)
- **Visualization**: Microsoft Power BI Desktop
- **Data Processing**: SQL queries and stored procedures
- **Dashboard Design**: Power BI with custom dark theme

## 🚀 Installation and Setup

### **Prerequisites**
- Microsoft SQL Server (2016 or later)
- SQL Server Management Studio (SSMS)
- Microsoft Power BI Desktop
- Sample HR dataset (included in repository)

## 📈 Business Impact

This dashboard enables HR teams to:
- **Reduce Absenteeism**: Identify patterns and implement targeted interventions
- **Improve Planning**: Better workforce planning based on historical trends
- **Health Programs**: Design wellness initiatives based on absence reasons
- **Cost Optimization**: Calculate financial impact of absenteeism patterns
- **Policy Development**: Create data-driven attendance policies


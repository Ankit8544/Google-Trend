# **Google Trends Dashboard** 📈🌐

An insightful Power BI dashboard developed to visualize and analyze search trends from Google Trends using the SerpAPI. This dashboard focuses on trending keywords, their regional breakdowns, and performance over time, providing actionable insights for market analysis and strategy.

---

### **Live Link** 🔗  
[View the Dashboard](https://app.powerbi.com/reportEmbed?reportId=8c49c5e8-b4bd-40bf-90bd-297218b4417d&autoAuth=true&ctid=5eafb13a-8bcd-462a-9e16-58810b6f2460)

---

## **Table of Contents**

- [Project Overview](#project-overview)  
- [Features](#features)  
- [Dashboard Components](#dashboard-components)  
- [Key Metrics & Insights](#key-metrics--insights)  
- [Setup Guide](#setup-guide)  
- [Technologies Used](#technologies-used)  
- [Future Enhancements](#future-enhancements)  

---

## **Project Overview**

The **Google Trends Dashboard** integrates data from Google Trends through the SerpAPI to analyze keyword performance across time and regions. It serves as a powerful tool for marketers, data analysts, and strategists to understand search behavior and act on emerging trends.

---

## **Features**

- **Keyword Trends**: Track search volume and popularity of keywords over the past five years.  
- **Regional Insights**: View keyword performance segmented by region.  
- **Top and Rising Keywords**: Highlight the most searched and fastest-growing terms.  
- **Dynamic Parameters**: Customize keywords, date ranges, and regions for analysis.  

---

## **Dashboard Components**

1. **Regional Breakdown**:  
   - Display keyword performance across geographic locations.  
   - Compare trends across regions for a deeper understanding of market interest.  

2. **Keyword Analysis**:  
   - Daily and monthly search trend analysis.  
   - Comparative insights for top keywords.  

3. **Interactive Filters**:  
   - Adjust parameters such as keywords, date range, and time zones dynamically.

---

## **Key Metrics & Insights**

- **Top Keywords**:  
  - *Data Analyst*: 3,173 searches  
  - *India Jobs*: 12,896 searches  

- **Regional Insights**:  
  - *India*: High interest in technical roles like "Data Engineer" and "Web Developer".  
  - *Global Trends*: Emerging demand for "Microsoft Jobs" with 180,250 searches.

This dashboard reveals significant opportunities in specific regions and growing global interest in technical careers.

---

## **Setup Guide**

### **Requirements**  
- Power BI Desktop  
- Access to SerpAPI with a valid API key.  

### **Steps to Use the Dashboard**  

1. **Clone the Repository**:  
   ```bash  
   git clone https://github.com/yourusername/google-trends-dashboard.git  
   ```  

2. **Set Up API Integration**:  
   - Define your SerpAPI key and the keywords in the Power Query code:  
     ```m
     Key = "YOUR_API_KEY",
     Keywords = "YOUR_KEYWORD"
     ```  

3. **Load Dataset**:  
   - Run the Power Query code to fetch data directly from SerpAPI.  

4. **Customize Parameters**:  
   - Adjust date range (`date`), timezone (`tz`), and data type (`data_type`) as needed.  

5. **Refresh Data**:  
   - Refresh the dataset in Power BI to update trends dynamically.  

6. **Publish Dashboard**:  
   - Upload the dashboard to Power BI Service for sharing.  

---

## **Technologies Used**

- **API Integration**: SerpAPI (Google Trends Engine)  
- **Data Visualization**: Power BI  
- **Data Processing**: Power Query  
- **Scripting**: M Language for API calls  

---

## **Future Enhancements**

1. **Live Data Updates**: Automate real-time trend fetching using scheduled refreshes.  
2. **Predictive Analysis**: Integrate machine learning to forecast future search trends.  
3. **Enhanced Filters**: Add detailed geographic and category-specific insights.  
4. **Mobile Optimization**: Create a mobile-friendly version of the dashboard for on-the-go analysis.  

---

*Disclaimer: This dashboard uses data fetched via SerpAPI and is for demonstration purposes. Ensure compliance with API usage limits and terms.*  
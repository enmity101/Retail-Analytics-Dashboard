# Retail Analytics Dashboard - Executive Insights Report

A comprehensive business intelligence project delivering visual analytics for strategic decision-making by C-suite executives.

## 📊 Project Overview

This project presents four distinct visual analyses created for CEO and CMO strategic review, focusing on revenue trends, market performance, customer insights, and global expansion opportunities using retail transaction data.

## 🎯 Business Objectives

The dashboard addresses four key executive questions:

1. **Revenue Time Series Analysis** - Seasonal revenue patterns for 2011 to support forecasting
2. **Top Markets Performance** - Top 10 revenue-generating countries (excluding UK)
3. **High-Value Customer Identification** - Top 10 customers by revenue for retention strategies
4. **Global Demand Mapping** - Worldwide product demand visualization for expansion planning

## 🧹 Data Preparation

### Data Cleaning Requirements

Before analysis, the raw retail dataset undergoes mandatory preprocessing to ensure accuracy:

- **Quantity Validation**: Excludes records with quantity < 1 unit (removes return entries)
- **Price Validation**: Excludes records with Unit Price < $0 (removes pricing errors)
- **Implementation**: Conditional formulas and data transformation methods

### Dataset Characteristics

- **Time Period**: Focus on 2011 data for temporal analysis
- **Geography**: Multiple countries with UK excluded from comparative analyses
- **Metrics**: Revenue, Quantity Sold, Customer ID, Unit Price

## 📈 Visualizations

### Question 1: Revenue Time Series (CEO)
- **Type**: Line chart/time series
- **Period**: 2011 monthly granularity
- **Purpose**: Identify seasonal peaks and troughs for next-year forecasting

### Question 2: Top 10 Countries by Revenue (CMO)
- **Type**: Dual-axis chart
- **Metrics**: Revenue and Quantity Sold
- **Filter**: UK excluded
- **Purpose**: Identify high-performing international markets

### Question 3: Top 10 Customers by Revenue (CMO)
- **Type**: Sorted bar chart
- **Order**: Descending (highest to lowest revenue)
- **Purpose**: Support customer retention and satisfaction strategies

### Question 4: Global Demand Map (CEO)
- **Type**: Geographic heat map
- **Scope**: All countries except UK
- **Design**: Single-view, no scrolling required
- **Purpose**: Identify expansion opportunities by region

## 🛠️ Tools & Technologies

**Visualization Platforms** (choose one):
- Tableau (Packaged Workbook - `.twbx`)
- Power BI (Desktop File - `.pbix`)

**Data Processing**:
- Conditional formulas for data validation
- Power Query / Tableau Data Source filters for transformation

## 📁 Project Structure

```
├── Question 1 - Revenue Time Series
├── Question 2 - Top 10 Countries
├── Question 3 - Top 10 Customers
└── Question 4 - Global Demand Map
```

Each visualization is organized on a separate tab labeled by question number.

## 🚀 Getting Started

### Prerequisites
- Tableau Public/Desktop (free trial available) OR
- Power BI Desktop (free trial available)

### Installation & Setup

1. Clone this repository
```bash
git clone [https://github.com/enmity101/Retail-Analytics-Dashboard.git]
```

2. Download and install your preferred BI tool:
   - [Tableau Free Trial](https://www.tableau.com/products/trial)
   - [Power BI Desktop](https://powerbi.microsoft.com/desktop/)

3. Open the workbook file:
   - For Tableau: Open the `.twbx` file
   - For Power BI: Open the `.pbix` file

## 📊 Key Insights

The dashboard enables executives to:
- Forecast revenue based on historical seasonal patterns
- Prioritize international markets for resource allocation
- Implement targeted retention programs for high-value customers
- Develop data-driven expansion strategies for high-demand regions

## 📝 Methodology

1. **Data Validation**: Applied quality checks to remove erroneous records
2. **Data Transformation**: Filtered and aggregated data per business requirements
3. **Visual Design**: Created intuitive, actionable visualizations for executive consumption
4. **Quality Assurance**: Verified accuracy against cleaned dataset

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👤 Author

**Your Name**
- GitHub: [@enmity101](https://github.com/enmity101/)
- LinkedIn: [Harsh Pratap Singh](https://www.linkedin.com/in/harshsingh94/)

## 🙏 Acknowledgments

- Data Analytics Team for requirements specification
- Executive leadership for strategic guidance
- © Tata Data Visualisation: Empowering Business
- with Effective Insights for project framework

---

**Note**: This project demonstrates business intelligence capabilities including data cleaning, transformation, visualization, and strategic analysis skills applicable to real-world retail analytics scenarios.

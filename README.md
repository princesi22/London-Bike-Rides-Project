<div align="center">

# 🚲 London Bike Rides Analysis & Visualization

### *Uncovering Urban Mobility Patterns Through Data-Driven Insights*

[![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)](https://github.com/princesi22/London-Bike-Rides)
[![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge)](https://github.com/princesi22/London-Bike-Rides)
[![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://github.com/princesi22/London-Bike-Rides)
[![Data Visualization](https://img.shields.io/badge/Data-Visualization-blue?style=for-the-badge)](https://github.com/princesi22/London-Bike-Rides)

![London Bike Ride Dashboard](London%20Bike%20Ride%20Dashboard.png)

*Interactive dashboard revealing seasonal trends, weather impacts, and demand patterns in London's bike-sharing system*

</div>

---

## 📋 Table of Contents

- [Project Overview](#-project-overview)
- [Objectives](#-objectives)
- [Tools & Technologies](#-tools--technologies)
- [Key Features & Visualizations](#-key-features--visualizations)
- [Key Insights](#-key-insights)
- [Dataset Information](#-dataset-information)
- [Project Structure](#-project-structure)
- [Getting Started](#-getting-started)
- [Business Value](#-business-value)
- [Skills Demonstrated](#-skills-demonstrated)
- [Dashboard Preview](#-dashboard-preview)
- [Author](#-author)

---

## 📌 Project Overview

The **London Bike Rides Analysis** project provides a comprehensive examination of London's bike-sharing system, analyzing ride patterns, seasonal variations, and weather impacts. This end-to-end analytics project combines:

- 📊 **Tableau visualization** for interactive dashboard creation
- 🔢 **DAX calculations** for advanced metrics and measures
- 📈 **Time-series analysis** including moving averages
- 🌡️ **Weather correlation analysis** for demand forecasting
- 🎨 **Professional dashboard design** with dynamic filtering

### **Project Highlights:**

- ✅ Real-world dataset from London's bike-sharing system
- ✅ Advanced DAX formulas for calculated measures
- ✅ Interactive dashboard with dynamic filtering
- ✅ Moving average calculations for trend smoothing
- ✅ Business-focused insights for urban planning

---

## 🎯 Objectives

This project aims to answer critical questions about urban bike-sharing systems:

<div align="center">

| Objective | Description | Business Impact |
|-----------|-------------|-----------------|
| **📊 Demand Analysis** | Analyze bike ride demand over time | Capacity planning |
| **🌦️ Weather Patterns** | Understand seasonal and weather impacts | Operational optimization |
| **📈 Trend Smoothing** | Use DAX for moving averages to reduce noise | Strategic forecasting |
| **🌡️ Temperature Correlation** | Visualize temp/wind vs. ride count | Resource allocation |
| **💼 Dashboard Creation** | Build interactive Tableau dashboard | Stakeholder communication |

</div>

---

## 🛠️ Tools & Technologies

### **Technology Stack:**

<div align="center">

| Category | Technology | Purpose |
|----------|-----------|---------|
| **Visualization** | ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white) | Interactive dashboard development |
| **Calculations** | ![DAX](https://img.shields.io/badge/DAX-0078D4?style=flat-square) | Advanced measures and calculated fields |
| **Data Management** | ![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white) | Data cleaning and preparation |
| **Version Control** | ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) | Project documentation |

</div>

### **Detailed Implementation:**

- **🎨 Tableau Desktop** - Primary platform for dashboard creation and visualization
- **🔢 DAX (Data Analysis Expressions)** - Custom calculations for moving averages, aggregations, and metrics
- **📊 Tableau Calculated Fields** - Dynamic measures using DAX-like formulas
- **📈 Excel** - Initial data cleaning, validation, and preparation
- **🎯 Tableau Parameters** - Interactive controls for moving average periods
- **🔗 GitHub** - Version control and project documentation

---

## 📊 Key Features & Visualizations

### 1️⃣ **Time-Series Analysis**

**📈 Daily Ride Trends with Moving Averages**

- **Daily bike ride counts** tracked over entire dataset period
- **20-day moving average** calculated using DAX formulas to smooth short-term fluctuations
- **Interactive date range selection** for focused period analysis
- **Trend identification** to spot growth or decline patterns

**DAX Implementation:**
- Custom moving average calculations using DAX window functions
- Dynamic period selection via Tableau parameters
- Aggregated measures for daily, weekly, and monthly trends
- Calculated fields for year-over-year comparisons

**Why Moving Averages?**
- Reduces daily noise and volatility
- Highlights underlying trends
- Essential for forecasting and planning
- Makes seasonal patterns more visible

---

### 2️⃣ **Seasonal Insights**

**🌸🌞🍂❄️ Demand Variations Across Seasons**

| Season | Characteristics | Business Implications |
|--------|----------------|----------------------|
| **🌸 Spring** | Rising demand | Prepare for summer surge |
| **🌞 Summer** | Peak usage period | Maximum capacity required |
| **🍂 Autumn** | Declining trend | Optimize maintenance schedule |
| **❄️ Winter** | Minimum usage | Cost reduction opportunities |

**Analysis Includes:**
- Clear demand variations across all four seasons
- Identification of minimum and peak usage periods
- Year-over-year seasonal comparisons
- Planning recommendations for each season

---

### 3️⃣ **Weather Impact Analysis**

**🌦️ Weather Condition Categorization**

The project maps weather codes to human-readable labels for better understanding:

| Weather Code | Label | Impact on Rides |
|--------------|-------|----------------|
| 1 | ☀️ **Clear** | Highest demand |
| 2 | 🌤️ **Scattered Clouds** | High demand |
| 3 | ☁️ **Broken Clouds** | Moderate demand |
| 4 | 🌧️ **Rain** | Reduced demand |
| 7 | ❄️ **Snowfall** | Minimum demand |

**Key Findings:**
- Clear weather drives maximum bike usage
- Rain significantly reduces ridership
- Snowfall nearly eliminates demand
- Cloud cover has moderate negative impact

---

### 4️⃣ **Temperature vs Wind Speed Heatmap**

**🌡️💨 Optimal Weather Conditions Analysis**

**Heatmap Dimensions:**
- **X-axis:** Temperature (°C) ranging from cold to hot
- **Y-axis:** Wind speed (kph) from calm to windy
- **Color intensity:** Total ride volume

**Insights Revealed:**
- Sweet spot for bike rides: **15-25°C with low wind**
- High wind speeds deter riders regardless of temperature
- Extreme cold (<5°C) significantly reduces usage
- Hot temperatures (>30°C) see moderate decline

**Business Application:**
- Predict demand based on weather forecast
- Optimize bike distribution ahead of optimal conditions
- Plan maintenance during poor weather windows

---

## 🧠 Key Insights

### **📊 Data-Driven Discoveries:**

<div align="center">

| Finding | Detail | Actionable Recommendation |
|---------|--------|---------------------------|
| **🌡️ Temperature Impact** | Rides increase significantly in moderate temps (15-25°C) | Focus marketing during optimal weather |
| **💨 Wind Sensitivity** | Extreme cold and high winds reduce usage dramatically | Plan maintenance during windy periods |
| **☀️ Seasonal Peak** | Summer and clear-weather days show peak demand | Ensure maximum capacity Apr-Sep |
| **📈 Long-term Trends** | Moving averages reveal growth beyond daily noise | Use for annual planning and forecasting |
| **🌧️ Weather Dependency** | Clear correlation between good weather and high usage | Weather-based dynamic pricing opportunity |

</div>

### **Strategic Insights:**

1. **Capacity Planning** - Summer months require 2-3x winter capacity
2. **Maintenance Windows** - Schedule during winter and poor weather
3. **Marketing Opportunities** - Promote heavily during spring shoulder season
4. **Dynamic Pricing** - Consider weather-based pricing models
5. **Infrastructure Investment** - Prioritize stations in high-demand areas

---

## 📁 Dataset Information

### **Source & Characteristics:**

- **Dataset Name:** London Bike-Sharing System Data
- **Coverage Period:** Multiple years of historical data
- **Data Points:** Daily ride counts with weather variables
- **Processing:** Cleaned and transformed using Excel

### **Key Variables:**

| Variable | Type | Description |
|----------|------|-------------|
| **Date** | DateTime | Ride date |
| **Bike Count** | Integer | Number of rides |
| **Temperature** | Float | Temperature in °C |
| **Wind Speed** | Float | Wind speed in kph |
| **Weather Code** | Integer | Weather condition category |
| **Season** | Categorical | Spring/Summer/Autumn/Winter |
| **Holiday** | Boolean | Whether date is a holiday |

### **Data Quality:**

- ✅ Missing values handled in Excel
- ✅ Outliers identified and addressed
- ✅ Data transformation applied in Tableau
- ✅ DAX calculations for derived metrics
- ✅ Data validated against source

### **Output Files:**

```
📄 london_bike_final.xlsx
   ├── Cleaned dataset
   ├── Structured for Tableau import
   ├── Weather codes mapped
   └── Ready for visualization
```

---

## 📂 Project Structure

```
london-bike-rides/
│
├── 📁 data/
│   ├── raw/
│   │   └── london_bikes_raw.csv          # Original dataset
│   └── processed/
│       └── london_bike_final.xlsx        # Cleaned & processed data
│
├── 📁 tableau/
│   ├── london_bike_dashboard.twb         # Tableau workbook
│   └── london_bike_dashboard.twbx        # Packaged workbook (with data)
│
├── 📁 images/
│   ├── dashboard_preview.png             # Main dashboard screenshot
│   ├── heatmap_example.png               # Heatmap visualization
│   └── time_series.png                   # Time series chart
│
├── 📁 documentation/
│   ├── DAX_formulas.md                   # DAX calculations documentation
│   └── data_dictionary.md                # Variable descriptions
│
├── 📄 README.md                          # Project documentation
└── 📄 .gitignore                         # Git ignore file
```

---

## 🚀 Getting Started

### **Prerequisites:**

- Tableau Desktop or Tableau Public (Version 2020.1 or later recommended)
- Microsoft Excel (for viewing source data)
- Basic understanding of Tableau and data visualization

### **Installation:**

**Step 1: Clone the Repository**
```bash
git clone https://github.com/princesi22/London-Bike-Rides.git
cd London-Bike-Rides
```

**Step 2: Open the Tableau Dashboard**
```bash
# Option 1: Open packaged workbook (includes data)
# Double-click: tableau/london_bike_dashboard.twbx

# Option 2: Open workbook (requires data connection)
# Open Tableau Desktop
# File -> Open -> london_bike_dashboard.twb
# Connect to: data/processed/london_bike_final.xlsx
```

**Step 3: Explore the Dashboard**
- Use date range filter to customize time period
- Adjust moving average parameter (7, 14, 20, 30 days)
- Click on charts for drill-down details
- Hover over data points for detailed tooltips
- Export visualizations or data as needed

### **Quick Start Guide:**

1. **📊 View Dashboard** - Open `tableau/london_bike_dashboard.twbx`
2. **🔍 Explore Data** - Check `data/processed/london_bike_final.xlsx`
3. **🎯 Adjust Filters** - Customize date range and parameters
4. **📈 Analyze Trends** - Use moving average selector
5. **🌡️ Check Correlations** - Explore temperature-wind heatmap

---

## 💼 Business Value

### **Stakeholder Benefits:**

<div align="center">

| Stakeholder | Key Benefits | Use Cases |
|-------------|--------------|-----------|
| **🏛️ Urban Planners** | Understand mobility patterns | Infrastructure planning |
| **🚲 Transport Authorities** | Demand forecasting | Capacity optimization |
| **💰 Operations Teams** | Weather impact analysis | Resource allocation |
| **📊 Data Teams** | Methodology reference | Best practice implementation |
| **🎯 Strategy Teams** | Long-term trend analysis | Investment decisions |

</div>

### **Business Applications:**

1. **📈 Demand Forecasting**
   - Predict daily/weekly/monthly demand
   - Weather-based capacity planning
   - Seasonal resource allocation

2. **⚙️ Operational Optimization**
   - Bike distribution optimization
   - Maintenance scheduling
   - Staff allocation planning

3. **💵 Revenue Management**
   - Dynamic pricing strategies
   - Promotional campaign timing
   - Investment ROI analysis

4. **📍 Strategic Planning**
   - New station location planning
   - Service expansion decisions
   - Infrastructure investment priorities

---

## 🎓 Skills Demonstrated

This project showcases proficiency across the data analytics spectrum:

<div align="center">

| Skill Domain | Specific Competencies | Tools Used |
|--------------|----------------------|------------|
| **📊 Data Visualization** | Interactive dashboards, heatmaps, time-series charts | Tableau |
| **🔢 Advanced Analytics** | DAX formulas, calculated fields, moving averages | Tableau, DAX |
| **🧹 Data Preparation** | Data cleaning, validation, transformation | Excel |
| **📈 Statistical Analysis** | Trend analysis, correlation, seasonality detection | Tableau |
| **🎨 Dashboard Design** | UI/UX principles, color theory, layout optimization | Tableau |
| **📖 Data Storytelling** | Insight generation, narrative building, presentation | Tableau |
| **💼 Business Intelligence** | KPI definition, metric creation, stakeholder focus | Tableau, DAX |
| **🗄️ Data Modeling** | Data relationships, aggregations, hierarchies | Tableau |

</div>

---

## 📷 Dashboard Preview

<div align="center">

![London Bike Ride Dashboard](London%20Bike%20Ride%20Dashboard.png)

*Interactive dashboard featuring time-series analysis with moving averages and temperature-wind heatmap*

</div>

### **Dashboard Features:**

- 📅 **Date Range Filter** - Select specific time periods for analysis
- 📊 **Moving Average Parameter** - Adjust smoothing period (7, 14, 20, 30 days) using DAX calculations
- 🌡️ **Temperature-Wind Heatmap** - Visual correlation analysis using aggregated measures
- 📈 **Trend Line** - Clear visualization of long-term patterns with calculated fields
- 🎨 **Color-Coded Weather** - Intuitive weather condition display with custom formatting
- 🔄 **Interactive Tooltips** - Detailed information on hover with DAX-driven metrics
- 🎯 **Dynamic Calculations** - Real-time metric updates based on filter selections

---

## 👤 Author

<div align="center">

### **Prince Kumar Singh**

*Aspiring Data Analyst | Tableau Developer | DAX Specialist*

**Core Competencies:**
- 📊 Tableau Desktop & Tableau Public (Dashboard Development)
- 🔢 DAX (Data Analysis Expressions) for Advanced Calculations
- 💼 Power BI & Business Intelligence Tools
- 📈 Data Visualization & Interactive Dashboard Design
- 🧹 Data Cleaning & Transformation (Excel)
- 📉 Statistical Analysis & Trend Identification
- 💡 Business Intelligence & Analytics

**Career Goals:** Actively seeking **Data Analyst** or **Business Analyst** opportunities

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/princesi22)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](#)
[![Tableau Public](https://img.shields.io/badge/Tableau-Public-E97627?style=for-the-badge&logo=tableau&logoColor=white)](#)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your.email@example.com)

</div>

---

## 🤝 Contributing

Contributions and suggestions are welcome!

### **How to Contribute:**

1. 🍴 Fork the repository
2. 🌿 Create feature branch (`git checkout -b feature/Enhancement`)
3. 💾 Commit changes (`git commit -m 'Add Enhancement'`)
4. 📤 Push to branch (`git push origin feature/Enhancement`)
5. 🔃 Open Pull Request

### **Contribution Ideas:**

- 📊 Additional visualizations or chart types
- 🔍 More detailed weather analysis
- 🔢 Advanced DAX calculations and measures
- 📱 Mobile-optimized dashboard version
- 🌍 Comparison with other cities' bike-sharing data
- 📈 Predictive analytics using Tableau forecasting

---

## 📄 License

This project is available for educational and portfolio purposes. Please provide appropriate credit when using or referencing this work.

---

## 📚 Additional Resources

- **📖 Documentation:** [Tableau Help](https://help.tableau.com/) | [DAX Guide](https://dax.guide/)
- **🎓 Learning:** [Tableau Training](https://www.tableau.com/learn/training) | [DAX Patterns](https://www.daxpatterns.com/)
- **📊 Datasets:** [London Data Store](https://data.london.gov.uk/) | [TfL Open Data](https://tfl.gov.uk/info-for/open-data-users/)

---

## ⭐ Acknowledgments

- 🚲 Transport for London for providing bike-sharing data
- 📊 Tableau community for visualization inspiration and best practices
- 🔢 DAX community for calculation techniques and optimization tips
- 🌐 Open data initiatives enabling this analysis

---

<div align="center">

### **⭐ Found this project helpful? Please give it a star!**

### **🚲 Pedaling through data, one insight at a time**

**Made with ❤️ and 📊 by Prince Kumar Singh**

*"Transforming data into visual stories, one dashboard at a time."*

---

![GitHub last commit](https://img.shields.io/github/last-commit/princesi22/London-Bike-Rides?style=flat-square)
![GitHub repo size](https://img.shields.io/github/repo-size/princesi22/London-Bike-Rides?style=flat-square)
![GitHub stars](https://img.shields.io/github/stars/princesi22/London-Bike-Rides?style=social)

</div>

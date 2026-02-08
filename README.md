<div align="center">

# 🚲 London Bike Rides Analysis & Visualization

### *Uncovering Urban Mobility Patterns Through Data-Driven Insights*

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://github.com/princesi22/London-Bike-Rides)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://github.com/princesi22/London-Bike-Rides)
[![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)](https://github.com/princesi22/London-Bike-Rides)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://github.com/princesi22/London-Bike-Rides)

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

- 🐍 **Python data processing** for cleaning and transformation
- 📊 **Statistical analysis** to uncover trends and patterns
- 🎨 **Interactive visualizations** using Tableau
- 📈 **Time-series techniques** including moving averages
- 🌡️ **Weather correlation analysis** for demand forecasting

### **Project Highlights:**

- ✅ Real-world dataset from London's bike-sharing system
- ✅ Complete data pipeline from raw data to dashboard
- ✅ Advanced feature engineering and data transformation
- ✅ Interactive dashboard with dynamic filtering
- ✅ Business-focused insights for urban planning

---

## 🎯 Objectives

This project aims to answer critical questions about urban bike-sharing systems:

<div align="center">

| Objective | Description | Business Impact |
|-----------|-------------|-----------------|
| **📊 Demand Analysis** | Analyze bike ride demand over time | Capacity planning |
| **🌦️ Weather Patterns** | Understand seasonal and weather impacts | Operational optimization |
| **📈 Trend Smoothing** | Use moving averages to reduce noise | Strategic forecasting |
| **🌡️ Temperature Correlation** | Visualize temp/wind vs. ride count | Resource allocation |
| **💼 Dashboard Creation** | Build interactive business tool | Stakeholder communication |

</div>

---

## 🛠️ Tools & Technologies

### **Technology Stack:**

<div align="center">

| Category | Technology | Purpose |
|----------|-----------|---------|
| **Programming** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) | Data processing and analysis |
| **Data Analysis** | ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) | Data manipulation and cleaning |
| **Numerical Computing** | ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) | Mathematical operations |
| **Visualization** | ![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white) | Interactive dashboard |
| **Development** | ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) | Notebook-based analysis |
| **Data Export** | ![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white) | Data validation and export |
| **Version Control** | ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) | Code management |

</div>

### **Detailed Implementation:**

- **🐍 Python** - Core language for data processing pipeline
- **📊 Pandas** - Data manipulation, cleaning, and transformation
- **🔢 NumPy** - Numerical operations and array processing
- **📈 Excel** - Data export, validation, and stakeholder sharing
- **🎨 Tableau** - Interactive dashboard with filters and parameters
- **📓 Jupyter Notebook** - Exploratory data analysis and documentation
- **🔗 GitHub** - Version control, collaboration, and project documentation

---

## 📊 Key Features & Visualizations

### 1️⃣ **Time-Series Analysis**

**📈 Daily Ride Trends with Moving Averages**

- **Daily bike ride counts** tracked over entire dataset period
- **20-day moving average** to smooth short-term fluctuations and reveal long-term trends
- **Interactive date range selection** for focused period analysis
- **Trend identification** to spot growth or decline patterns

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
- **Processing:** Cleaned and transformed using Python

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

- ✅ Missing values handled
- ✅ Outliers identified and addressed
- ✅ Feature engineering applied
- ✅ Data validated against source

### **Output Files:**

```
📄 london_bike_final.xlsx
   ├── Cleaned dataset
   ├── Engineered features
   ├── Moving averages calculated
   └── Ready for Tableau import
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
├── 📁 notebooks/
│   ├── 01_data_exploration.ipynb         # Initial EDA
│   ├── 02_data_cleaning.ipynb            # Data cleaning steps
│   └── 03_feature_engineering.ipynb      # Feature creation
│
├── 📁 tableau/
│   ├── london_bike_dashboard.twb         # Tableau workbook
│   └── london_bike_dashboard.twbx        # Packaged workbook
│
├── 📁 images/
│   ├── dashboard_preview.png             # Main dashboard
│   ├── heatmap_example.png               # Heatmap visual
│   └── time_series.png                   # Time series chart
│
├── 📁 scripts/
│   ├── data_processing.py                # Python processing scripts
│   └── utils.py                          # Helper functions
│
├── 📄 README.md                          # Project documentation
├── 📄 requirements.txt                   # Python dependencies
└── 📄 .gitignore                         # Git ignore file
```

---

## 🚀 Getting Started

### **Prerequisites:**

```bash
# Python 3.8 or higher
# Tableau Desktop or Tableau Public
# Jupyter Notebook or JupyterLab
```

### **Installation:**

**Step 1: Clone the Repository**
```bash
git clone https://github.com/princesi22/London-Bike-Rides.git
cd London-Bike-Rides
```

**Step 2: Set Up Python Environment**
```bash
# Create virtual environment
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

**Step 3: Launch Jupyter Notebook**
```bash
jupyter notebook
# Navigate to notebooks/ folder and open analysis files
```

**Step 4: Explore the Dashboard**
```bash
# Open Tableau Desktop
# File -> Open -> london_bike_dashboard.twbx
# Interact with filters and parameters
```

### **Quick Start Guide:**

1. **🔍 Explore Data Cleaning** - Open `notebooks/02_data_cleaning.ipynb`
2. **📊 Review Analysis** - Check `notebooks/03_feature_engineering.ipynb`
3. **🎨 View Dashboard** - Open `tableau/london_bike_dashboard.twbx`
4. **🎯 Adjust Filters** - Customize date range and moving average period
5. **📈 Extract Insights** - Use interactive features to explore patterns

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
| **🐍 Python Programming** | Data manipulation, automation, scripting | Python, Pandas, NumPy |
| **🧹 Data Cleaning** | Missing value handling, outlier detection, validation | Pandas |
| **🔧 Feature Engineering** | Moving averages, date features, categorization | Pandas, NumPy |
| **📊 Data Visualization** | Interactive dashboards, heatmaps, time-series | Tableau |
| **📈 Statistical Analysis** | Trend analysis, correlation, seasonality | Pandas, NumPy |
| **📖 Data Storytelling** | Insight generation, narrative building | Tableau, Markdown |
| **🗄️ Data Management** | ETL pipeline, data export, validation | Python, Excel |
| **💼 Business Acumen** | KPI definition, stakeholder focus, recommendations | Cross-functional |

</div>

---

## 📷 Dashboard Preview

<div align="center">

![London Bike Ride Dashboard](London%20Bike%20Ride%20Dashboard.png)

*Interactive dashboard featuring time-series analysis with moving averages and temperature-wind heatmap*

</div>

### **Dashboard Features:**

- 📅 **Date Range Filter** - Select specific time periods
- 📊 **Moving Average Selector** - Adjust smoothing period (7, 14, 20, 30 days)
- 🌡️ **Temperature-Wind Heatmap** - Visual correlation analysis
- 📈 **Trend Line** - Clear visualization of long-term patterns
- 🎨 **Color-Coded Weather** - Intuitive weather condition display
- 🔄 **Interactive Tooltips** - Detailed information on hover

---

## 👤 Author

<div align="center">

### **Prince Kumar Singh**

*Aspiring Data Analyst | Python Developer | Visualization Specialist*

**Core Competencies:**
- 📊 Tableau & Power BI Dashboard Development
- 🐍 Python (Pandas, NumPy, Data Analysis)
- 💾 SQL (Database Querying & Analysis)
- 📈 Data Visualization & Storytelling
- 🧹 Data Cleaning & Transformation
- 💼 Business Intelligence & Analytics

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

- 📊 Additional visualizations
- 🔍 More detailed weather analysis
- 🤖 Machine learning predictions
- 📱 Mobile dashboard version
- 🌍 Comparison with other cities

---

## 📄 License

This project is available for educational and portfolio purposes. Please provide appropriate credit when using or referencing this work.

---

## 📚 Additional Resources

- **📖 Documentation:** [Pandas Docs](https://pandas.pydata.org/docs/) | [Tableau Docs](https://help.tableau.com/)
- **🎓 Learning:** [Python for Data Analysis](https://wesmckinney.com/book/) | [Tableau Training](https://www.tableau.com/learn/training)
- **📊 Datasets:** [London Data Store](https://data.london.gov.uk/)

---

## ⭐ Acknowledgments

- 🚲 Transport for London for providing bike-sharing data
- 🐍 Python and Pandas community for excellent tools
- 📊 Tableau community for visualization inspiration
- 🌐 Open data initiatives enabling this analysis

---

<div align="center">

### **⭐ Found this project helpful? Please give it a star!**

### **🚲 Pedaling through data, one insight at a time**

**Made with ❤️ and 🐍 by Prince Kumar Singh**

*"Data is the new oil, but analytics is the combustion engine."*

---

![GitHub last commit](https://img.shields.io/github/last-commit/princesi22/London-Bike-Rides?style=flat-square)
![GitHub repo size](https://img.shields.io/github/repo-size/princesi22/London-Bike-Rides?style=flat-square)
![GitHub stars](https://img.shields.io/github/stars/princesi22/London-Bike-Rides?style=social)

</div>

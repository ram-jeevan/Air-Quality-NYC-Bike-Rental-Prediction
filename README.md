# Air Quality & NYC Bike Rental Prediction

A data analytics project exploring the relationship between weather conditions, air quality, and bike rental demand across US cities, with predictive modeling for NYC bike rental operations.

---

## 🎯 Project Overview

This project demonstrates end-to-end data analytics skills by combining API data collection, exploratory data analysis, correlation studies, and predictive modeling to answer a business question: **How do weather conditions affect bike rental demand?**

Using real-time data from OpenWeatherMap and OpenAQ APIs, I analyzed air quality and weather patterns across 10 major US cities, then built a linear regression model to forecast NYC bike rental demand based on temperature data.

---

## 💼 Business Context

**Scenario**: A bike rental company is considering expanding operations to New York City and needs to understand how weather conditions might impact rental demand.

**Key Questions**:
- How does temperature correlate with bike rental patterns?
- What air quality conditions exist across major US cities?
- Can we predict rental demand based on NYC weather forecasts?

---

## 🛠️ Technologies Used

- **Python** - Core programming language
- **pandas & numpy** - Data manipulation and analysis
- **matplotlib & seaborn** - Data visualization
- **scikit-learn** - Machine learning (Linear Regression)
- **requests** - API data collection
- **Jupyter Notebook** - Development environment

---

## 📊 Data Sources

### APIs Used:
1. **OpenWeatherMap API** - Real-time weather data including:
   - Temperature (actual, feels-like, min/max)
   - Humidity, pressure, sea level
   - Wind speed and cloud coverage

2. **OpenAQ API** - Air quality measurements including:
   - PM2.5 and PM10 (particulate matter)
   - CO, NO, NO2, O3, SO2, NH3 (pollutants)
   - Air Quality Index (AQI)

### Cities Analyzed:
Chicago, Boston, Austin, New York City, Atlanta, Los Angeles, Seattle, Minneapolis, Denver, Washington DC

---

## 🔍 Key Analyses

### 1. Multi-City Weather & Air Quality Collection
- Automated API calls for 10 US cities
- Combined weather and air quality data into unified dataset
- Geocoding with latitude/longitude coordinates

### 2. Air Quality Analysis
- **PM2.5 vs Temperature Correlation**: Explored relationship between particulate matter and temperature
- **Average PM2.5 by Location**: Comparative analysis across cities
- Visualization with scatter plots and bar charts

### 3. Predictive Modeling
- **Model**: Linear Regression
- **Target**: NYC bike rental demand
- **Features**: Temperature data
- **Approach**: Train-test split for model validation
- **Output**: Rental forecasts based on NYC weather predictions

---

## 📈 Key Findings

### Air Quality Insights:
- Identified correlation between temperature and PM2.5 levels
- PM2.5 tends to decrease as temperature increases
- Significant variation in air quality across US cities

### Predictive Model:
- Successfully built regression model linking temperature to rental demand
- Model provides rental forecasts for NYC expansion planning
- Temperature emerges as a key driver of rental patterns

---

## 📁 Project Structure

```
Airquality_NYC_Bike_Rental.ipynb    # Main analysis notebook
├── Data Collection
│   ├── OpenWeatherMap API integration
│   ├── OpenAQ API integration
│   └── Multi-city data scraping
├── Data Analysis
│   ├── Air quality correlation analysis
│   ├── PM2.5 vs Temperature study
│   └── City-by-city comparisons
└── Predictive Modeling
    ├── NYC weather forecasting
    ├── Linear regression model
    └── Bike rental predictions
```

---

## 🚀 How to Run This Project

### Prerequisites:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn requests jupyter
```

### API Keys Required:
- **OpenWeatherMap API key** - Get from [openweathermap.org/api](https://openweathermap.org/api)

### Steps:
1. Clone this repository
2. Add your OpenWeatherMap API key to the notebook
3. Run the Jupyter notebook cells sequentially
4. Review visualizations and model outputs

---

## 📊 Visualizations

The project includes:
- **Scatter plots** with trend lines showing PM2.5 vs Temperature correlation
- **Bar charts** comparing average PM2.5 levels across cities
- **Multi-panel visualizations** for comprehensive air quality analysis

---

## 🎓 Skills Demonstrated

### Technical Skills:
- API integration and data extraction
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Statistical correlation analysis
- Machine learning with scikit-learn
- Data visualization with matplotlib/seaborn
- Pandas for data manipulation

### Analytical Skills:
- Business problem formulation
- Feature engineering
- Model selection and validation
- Data-driven decision making
- Insight communication

---

## 🔮 Future Enhancements

- [ ] Add more weather features (humidity, wind speed) to improve model accuracy
- [ ] Implement time-series forecasting with ARIMA or Prophet
- [ ] Include seasonal patterns and trends
- [ ] Create interactive dashboards with Plotly or Tableau
- [ ] Expand to multiple cities for comparative modeling
- [ ] Add Random Forest or XGBoost for better predictions

---

## 📫 Contact

**Ram** - Brand & Communications Executive | Aspiring Data Analyst

---

## 📝 License

This project is open source and available for educational purposes.

---

## 🙏 Acknowledgments

- OpenWeatherMap for comprehensive weather data API
- OpenAQ for open-source air quality measurements
- General Assembly Data Analytics Bootcamp for foundational skills

---

*Built with 📊 by Ram | January 2025*

# 🚛 Data-Driven Logistics & Fleet Performance Optimization

> **Python-based Analytics Project | Data Exploration | Predictive Modeling | Business Insights**

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-yellow)

---  

## 📋 Quick Overview

A comprehensive data analytics project analyzing **14 interconnected logistics tables** (85,410+ trips) to understand fleet performance, optimize operations, and predict trip duration using machine learning.

---

## ❗ Problem Statement

Logistics company facing operational challenges:
- **55.67%** on-time delivery rate (concerning)
- **91.54 minutes** average detention time (inefficient)
- Unclear fleet efficiency and fuel consumption patterns
- Lack of data-driven resource allocation strategies

**Goal**: Leverage data analytics to identify operational bottlenecks and optimize fleet performance.

---

## 💡 Solution Approach

### 4-Week Structured Analysis

| Week | Focus | Outcome |
|------|-------|---------|
| **Week 1** | Strategic planning & data exploration | Established baseline KPIs |
| **Week 2** | Data cleaning & preprocessing | 100% data validation passed |
| **Week 3** | EDA & advanced analysis | Identified performance patterns |
| **Week 4** | Predictive modeling & optimization | Built trip-duration predictor |

---

## 📊 Key Deliverables

### Week 1: Baseline KPIs
- On-Time Delivery Rate: **55.67%**
- Average Detention Time: **91.54 min**
- Average Fuel Efficiency: **6.50 MPG**
- Total Distance: **122.16M miles**
- Total Fuel Used: **18.95M gallons**

### Week 2: Data Quality
✅ Zero negative values (distance, duration, fuel)  
✅ Zero invalid MPG records  
✅ IQR-based outlier detection completed  
✅ Feature normalization applied  
✅ Missing values handled appropriately

### Week 3: Business Insights
📍 **Geographic Analysis** - TX leads with 17,542 delivery events  
🕐 **Detention Hotspots** - IN, CA, CO average 100+ minutes  
📈 **Correlation Found** - Distance↔Duration (0.99), Distance↔Fuel (0.98)  
👤 **Top Performers** - Driver DRV00105 & Truck TRK00049 ranked by efficiency  
📅 **Monthly Stability** - Fleet MPG consistent (6.47-6.53 range)

### Week 4: Predictive Model
**Best Model**: Linear Regression
- **MAE**: 1.63 hours
- **RMSE**: 2.16 hours
- **R² Score**: 0.9768 (97.68% variance explained)
- **Key Feature**: Distance (96.98% importance)

---

## 📈 Dataset Overview

| Table | Records | Purpose |
|-------|---------|---------|
| Trips | 85,410 | Trip performance data |
| Delivery Events | 170,820 | Pickup/delivery records |
| Fuel Purchases | 196,442 | Fuel consumption |
| Maintenance | 2,920 | Vehicle maintenance |
| Safety Incidents | 170 | Safety records |

**Total Scale**: 14 relational tables, 500k+ records

---

## 🛠️ Technologies & Tools

**Data Analysis**
- Python | Pandas | NumPy

**Visualization**
- Matplotlib | Seaborn

**Machine Learning**
- Scikit-learn (Linear Regression, Random Forest)

**Development**
- Jupyter Notebook | Git | GitHub | VS Code

---

## 📂 Repository Structure

```
logistics-data-analytics/
├── data/                          # 14 CSV files
├── notebooks/
│   ├── 01_database_exploration.ipynb
│   ├── 02_data_cleaning_preprocessing.ipynb
│   ├── 03_advanced_eda_visualization.ipynb
│   └── 04_predictive_modeling_optimization.ipynb
├── reports/                       # Weekly analysis reports
├── visualizations/                # Charts & graphs
├── requirements.txt
└── README.md
```

---

## 🎯 Key Findings & Recommendations

### Operational Insights
1. **Improve On-Time Delivery** - 44.33% late deliveries indicate scheduling issues
2. **Reduce Detention Time** - Focus on high-detention states (IN, CA, CO)
3. **Fleet Optimization** - TRK00049 efficiency model for best performers
4. **Driver Performance** - Top drivers maintain 6.56 MPG consistency

### Data-Driven Actions
- ✅ Use predictive trip-duration for better scheduling
- ✅ Add buffers for long-distance predictions
- ✅ Investigate facility delays (detention hotspots)
- ✅ Reduce idle time (avg 7.01 hours per trip)
- ✅ Monitor underperforming trucks (TRK00072: 6.45 MPG)

---

## 📊 Model Performance

### Regression Models Comparison
```
Linear Regression vs Random Forest

Linear Regression:
✓ MAE:  1.6317 hours (better)
✓ RMSE: 2.1631 hours (better)
✓ R²:   0.9768 (better)
→ Selected as best model

Random Forest:
• MAE:  1.6983 hours
• RMSE: 2.2937 hours
• R²:   0.9739
```

### Feature Importance
- **Distance**: 96.98% (dominant predictor)
- **Fuel Used**: 1.85%
- **Idle Time**: 0.69%
- **Average MPG**: 0.48%

---

## 🚀 Future Enhancements

- 🤖 Advanced ML (XGBoost, LSTM)
- 🛣️ Route optimization algorithms
- 📍 Vehicle Routing Problem (VRP) solver
- 🔮 Demand forecasting
- ⚠️ Maintenance/safety prediction
- 📊 Power BI/Tableau dashboards
- 📡 Real-time GPS/IoT integration

---

## 🚀 Getting Started

### Prerequisites
```bash
Python 3.8+
Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
Jupyter Notebook
```

### Setup
```bash
# Clone repository
git clone https://github.com/Saisnehan/logistics-data-analytics.git
cd logistics-data-analytics

# Install dependencies
pip install -r requirements.txt

# Run notebooks in sequence
jupyter notebook notebooks/
```

---

## 📈 Project Status

| Phase | Status |
|-------|--------|
| Week 1 - Strategic Planning | ✅ Complete |
| Week 2 - Data Cleaning | ✅ Complete |
| Week 3 - EDA & Analysis | ✅ Complete |
| Week 4 - Predictive Modeling | ✅ Complete |
| Week 5 - Advanced Analytics | 🔄 Planned |

---

## 🎓 Skills Demonstrated

✅ **Data Analysis** - Pandas, exploratory analysis, statistics  
✅ **Data Cleaning** - Missing values, outlier detection, normalization  
✅ **Visualization** - Matplotlib, Seaborn, insights communication  
✅ **Machine Learning** - Regression models, feature importance, evaluation  
✅ **Business Acumen** - KPI identification, recommendations, optimization  
✅ **Project Management** - Structured 4-week delivery  

---

## 📝 Reports & Documentation

Weekly detailed reports included in `/reports/`:
- Week 1: Strategic planning & baseline metrics
- Week 2: Data quality assessment
- Week 3: EDA findings & correlations
- Week 4: Model results & recommendations

---

## 🤝 Contributing

Found insights or improvements?
1. Fork the repository
2. Create feature branch
3. Commit changes
4. Push and open Pull Request

---

## 📄 License

MIT License - see LICENSE file for details

---

## 👨‍💻 Author

**K Sai Snehan**

Data Analytics | Machine Learning | Python | Logistics Optimization

- 📧 Email: saisnehank@gmail.com
- 🔗 LinkedIn: [linkedin.com/in/k-saisnehan](https://linkedin.com/in/k-saisnehan)
- 🐙 GitHub: [github.com/Saisnehan](https://github.com/Saisnehan)

---

**Last Updated**: August 2026

Built with 📊 Python | 🐼 Pandas | 🤖 Scikit-learn

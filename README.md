# Data-Driven Logistics and Fleet Performance Optimization

## Week 1 – Strategic Planning and Data Exploration

### Project Overview

This project analyzes logistics and fleet operations using historical transportation, delivery, fuel, driver, truck, route, maintenance, and safety data.

The objective is to identify operational patterns and develop data-driven insights that can help improve delivery reliability, fuel efficiency, fleet utilization, and overall logistics performance.

### Business Problem

A logistics company wants to improve its operational efficiency while maintaining reliable customer deliveries.

The project investigates:

- Delivery performance
- Fleet efficiency
- Fuel consumption
- Driver performance
- Route performance
- Vehicle utilization
- Maintenance
- Safety performance

### Dataset

The project uses a relational logistics dataset containing 14 related tables:

- Customers
- Drivers
- Trucks
- Trailers
- Facilities
- Routes
- Loads
- Trips
- Fuel Purchases
- Maintenance Records
- Delivery Events
- Safety Incidents
- Driver Monthly Metrics
- Truck Utilization Metrics

The database contains more than 85,000 trips and more than 170,000 delivery events.

### Key Performance Indicators

The initial analysis focuses on:

1. On-Time Delivery Rate
2. Average Detention Time
3. Average Fuel Efficiency (MPG)
4. Average Idle Time
5. Average Trip Duration
6. Total Distance
7. Total Fuel Consumption

### Week 1 Initial Findings

- On-Time Delivery Rate: 55.67%
- Average Detention Time: 91.54 minutes
- Total Distance: 122,159,201 miles
- Total Fuel Used: 18,946,280.10 gallons
- Average Fuel Efficiency: 6.50 MPG
- Average Idle Time: 7.01 hours
- Average Trip Duration: 25.01 hours

### Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

### Project Roadmap

1. Strategic Planning
2. Database Exploration
3. Data Cleaning
4. Exploratory Data Analysis
5. KPI Analysis
6. Driver and Fleet Analysis
7. Route Performance Analysis
8. Predictive Analytics
9. Clustering
10. Optimization
11. Business Recommendations

### Repository Structure

```text
logistics-data-analytics-project/
│
├── data/
├── notebooks/
│   └── 01_database_exploration.ipynb
├── reports/
├── src/
├── visualizations/
├── README.md
├── requirements.txt
└── .gitignore


## Project Status

### Week 1 – Strategic Planning and Data Exploration
Completed

### Week 2 – Data Collection, Cleaning and Preprocessing
Completed

Week 2 included:
- Data quality assessment
- Missing value analysis
- Duplicate detection
- Data type conversion
- Invalid value detection
- IQR-based outlier analysis
- Numerical feature normalization
- Clean dataset preparation

### Next Phase

Week 3 will focus on exploratory data analysis, relationships between logistics variables, and deeper KPI analysis.
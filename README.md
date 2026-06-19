# Hotel Booking Demand Analysis

## Project Overview

This project performs an end-to-end Exploratory Data Analysis (EDA) on the Hotel Booking Demand dataset. The objective is to understand customer booking behavior, hotel demand patterns, pricing trends, cancellation behavior, and operational characteristics through data cleaning, visualization, statistical testing, time-based analysis, and feature engineering.

---

## Dataset Information

* Dataset: Hotel Booking Demand Dataset
* Original Records: 119,390
* Original Features: 32
* Final Records After Cleaning: 87,370
* Data Types:

  * Numerical Variables
  * Categorical Variables
  * Date Variables

The dataset contains information related to hotel reservations, customer demographics, booking channels, room allocation, pricing, cancellations, and reservation outcomes.

---

## Project Objectives

* Understand hotel booking behavior.
* Identify demand patterns and seasonal trends.
* Analyze pricing behavior using ADR.
* Study cancellation patterns.
* Perform statistical hypothesis testing.
* Create meaningful engineered features.
* Generate business-oriented insights from hotel booking data.

---

## Project Workflow

### Day 1: Data Understanding

* Dataset exploration
* Variable identification
* Missing value assessment
* Initial business understanding

### Day 2: Data Cleaning & Preprocessing

* Missing value treatment
* Duplicate removal
* Data type correction
* Category standardization
* Outlier detection

### Day 3: Exploratory Data Analysis

* Univariate analysis
* Bivariate analysis
* Customer behavior analysis
* Market segment analysis
* Hotel segment analysis

### Day 4: Statistical Analysis & Feature Engineering

* Independent T-Tests
* ANOVA
* Chi-Square Test
* Time-Based Analysis
* Feature Engineering

### Day 5: Project Summary & Documentation

* Top insights
* Segment findings
* Data quality summary
* Final conclusions

---

## Key Insights

1. City Hotels generated the majority of bookings.
2. Online Travel Agencies (Online TA) dominated reservation channels.
3. Customers generally booked well in advance.
4. Most bookings consisted of one or two adults.
5. ADR varied significantly across market segments.
6. Hotel type significantly influenced room pricing.
7. Lead time was significantly associated with cancellation behavior.
8. Hotel demand showed strong seasonality.
9. ADR increased during peak-demand periods.
10. Feature engineering revealed valuable customer and revenue segments.

---

## Feature Engineering

The following features were created:

* total_guests
* total_nights
* total_previous_bookings
* total_booking_value
* room_changed
* family_booking
* long_stay

These features enhanced customer segmentation, revenue analysis, and operational insights.

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Jupyter Notebook
* Git & GitHub

---

## Repository Structure

```text
hotel-booking-eda-project/
│
├── data/
│   ├── raw/
│   ├── interim/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_overview.ipynb
│   ├── 02_cleaning_preprocessing.ipynb
│   ├── 03_univariate_bivariate_eda.ipynb
│   ├── 04_stats_time_features_final_insights.ipynb
│   └── 05_project_summary_and_documentation.ipynb
│
└── README.md
```

---

## Conclusion

The project successfully transformed raw hotel booking data into actionable business insights. Through systematic cleaning, exploration, statistical testing, and feature engineering, meaningful patterns related to customer behavior, pricing, demand seasonality, and hotel operations were identified.

The resulting dataset and findings provide a strong foundation for future predictive analytics and machine learning applications.

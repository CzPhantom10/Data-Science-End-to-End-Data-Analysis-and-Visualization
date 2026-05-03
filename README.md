# Smart Home Device Data Analysis

## Overview

This project focuses on analyzing smart home IoT device data using Data Science techniques. Smart homes generate large amounts of sensor data from devices such as air conditioners, lights, fans, heaters, televisions, and refrigerators. Proper analysis of this data helps in understanding device behavior, identifying energy usage trends, and improving overall efficiency.

The project demonstrates the complete data analysis pipeline including:

- Data Collection
- Data Cleaning and Wrangling
- Data Preparation and Analysis
- Data Visualization using Matplotlib
- Data Visualization using Seaborn
- Insights and Conclusion

---

# Problem Statement

Smart homes consist of multiple IoT devices such as air conditioners, lights, fans, and appliances that continuously generate sensor data.

These devices operate based on environmental conditions and user interactions, but:

- Data collected is often inconsistent and unstructured
- Energy usage patterns are not clearly understood
- Lack of analysis leads to inefficient energy consumption

This creates challenges in:

- Understanding device usage behavior
- Identifying high energy-consuming devices
- Detecting patterns over time (peak usage hours)
- Making data-driven decisions for optimization

---

# Objective

The objective of this project is to analyze smart home device data using Data Science techniques in order to:

- Clean and preprocess raw IoT data
- Extract meaningful insights from device behavior
- Identify energy usage patterns
- Improve overall efficiency through data-driven analysis

---

# Dataset Information

The dataset contains smart home IoT device data with the following columns:

| Column Name | Description |
|---|---|
| timestamp | Date and time of device activity |
| device_id | Unique identifier for each device |
| device_type | Type of device |
| temperature | Recorded temperature |
| humidity | Recorded humidity |
| motion | Motion detection status |
| energy_usage | Energy consumed by the device |
| status | Device state (ON/OFF) |

---

# Tables Created

## 1. Device Table
Contains unique device information.

Columns:
- device_id
- device_type

## 2. Sensor Table
Contains environmental and motion sensor data.

Columns:
- timestamp
- device_id
- temperature
- humidity
- motion

## 3. Energy Table
Contains device energy usage information.

Columns:
- device_id
- energy_usage
- status

---

# Data Cleaning Operations

The following preprocessing operations were performed:

- Handling missing values
- Removing duplicates
- Data type conversion
- Standardizing categorical values
- Filtering and sorting data

---

# Data Analysis Techniques

The project includes:

- Statistical summarization
- Group-based analysis
- Feature scaling using Standardization
- Outlier detection using IQR method

---

# Visualizations

Visualization techniques used in the project include:

## Matplotlib
- Line Plot
- Bar Plot
- Scatter Plot
- Histogram

## Seaborn
- Countplot
- Boxplot
- Violin Plot
- Barplot
- Heatmap

---

# Key Insights

- Energy usage varies significantly across different device types
- Some devices consume more energy compared to others
- Temperature affects device energy consumption
- Data cleaning improves analysis accuracy
- Usage patterns help identify peak activity hours

---

# Future Scope

Possible future improvements include:

- Energy consumption prediction using Machine Learning
- Real-time IoT monitoring systems
- Smart automation based on usage patterns
- Anomaly detection for unusual energy consumption

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# Conclusion

This project demonstrates how Data Science techniques can be applied to smart home IoT data in order to improve understanding of device behavior and optimize energy usage. Through preprocessing, analysis, and visualization, meaningful insights were extracted from raw sensor data.
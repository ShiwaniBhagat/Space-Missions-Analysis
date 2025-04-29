# Space-Missions-Analysis
Welcome to the **Space Missions Launch Analysis Project**! This project presents a comprehensive exploration of a synthetic dataset simulating historical space launches from various countries and companies. Using Python data science libraries, we investigate mission trends, success rates, launch costs, and more through visualizations and statistical summaries.
# Project Description
The Space Missions Launch Analysis project is a data analysis and visualization exploration of a synthetic dataset that simulates global space missions. It investigates how space exploration has evolved over time, which countries and companies dominate launches, and how factors such as cost, rocket types, and mission outcomes influence the success of launches.

Using Python libraries like pandas, matplotlib, seaborn, and scipy, this project dives deep into understanding trends, distributions, and correlations in space mission data. It includes visual insights through bar charts, pie charts, violin plots, and scatter plots, covering everything from launch frequency and mission success rates to cost analysis and rocket usage.

The aim is to gain insights into the operational patterns of the space industry, simulate real-world data science workflows, and create an engaging, educational analytical project suitable for academic or portfolio use.


---

## 📊 Key Objectives

- Understand **historical trends** in space mission launches.
- Identify **mission success rates** by country and company.
- Explore **geographical patterns** in launch activity.
- Analyze **mission costs**, detect anomalies, and evaluate spending trends.
- Compare **performance of companies** in terms of mission volume and success.
- Visualize **rocket usage** and **temporal growth** of the space industry.

---

## 🔍 Data Description

Since no real dataset is used, a **synthetic dataset** is generated using Python to simulate realistic space mission data. Each record contains:

- **Date**: Launch date of the mission
- **Country**: Country responsible for the launch
- **Company**: Launch organization (e.g., NASA, SpaceX)
- **Mission_Status**: One of "Success", "Failure", "Partial Failure", or "Prelaunch Failure"
- **Cost**: Cost of mission (in millions USD), with some missing values
- **Rocket**: Rocket name/identifier

---

## 📌 Analysis Overview

### 1. 🧹 Data Quality Check
- Identify missing values (especially in cost).
- Visualize data completeness with bar plots.

### 2. ✅ Mission Status Analysis
- Distribution of mission outcomes.
- Trends of mission outcomes over different decades.

### 3. 🌍 Geographic Analysis
- Number of missions by country.
- Mission **success rates by country** using bar plots.

### 4. 🏢 Company Analysis
- Top companies by launch volume.
- Correlation between total launches and success rate.
- Visualize using scatter plots with mission volume as size.

### 5. 💰 Cost Analysis
- Cost distribution using histograms with log scale.
- Scatter plots of cost vs. year, colored by mission outcome.
- Analyze whether high-cost missions tend to succeed more.

### 6. 📆 Temporal Trends
- Plot number of missions per year.
- Fit a regression trend line to highlight growth.

### 7. 🚀 Rocket Usage
- Bar plot of most frequently used rockets.

---

## 📈 Visualizations

This project uses:
- **Matplotlib** and **Seaborn** for plotting
- **CountPlots**, **Pie Charts**, **Violin Plots**, **Histograms**, and **Scatter Plots**
- **Log scaling** and **trend lines** for improved interpretability

Each plot is designed to be:
- Colorful and readable
- Sized appropriately for Jupyter
- Accompanied by meaningful titles and axes

---

## 🔧 Tools & Technologies

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy (for basic descriptive statistics)

---


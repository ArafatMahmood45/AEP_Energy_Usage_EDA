# ⚡ Hourly Energy Consumption EDA

This project explores hourly electricity usage data over multiple years to uncover trends, patterns, and insights. It was completed using Python libraries such as **Pandas**, **NumPy**, and **Matplotlib**, and is part of my learning portfolio in **data analysis** and **AI in engineering**.

---

## 📁 Dataset

- **Name:** AEP_hourly.csv  
- **Source:** [AEP Hourly Energy Consumption – PJM](https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption)  
- **Description:** Hourly electricity usage (in MW) for the AEP service area from 2004 to 2018.

---

## 🎯 Objectives

- Clean and prepare time-series energy data
- Aggregate and analyze usage across different time periods
- Engineer useful time-based features
- Visualize patterns and extract actionable insights

---

## 🧹 Data Cleaning

- Converted the `Datetime` column to datetime format
- Set it as the DataFrame index for time-series analysis
- Removed duplicate rows
- Handled and removed missing values

---

## 📊 Data Aggregation

- Resampled the time series data to get:
  - **Daily average**
  - **Monthly average**
  - **Yearly average**

---

## ⚙️ Feature Engineering

Created additional columns from the datetime index for grouped analysis:

- Hour of the day
- Day of the week
- Month
- Year

---

## 📈 Visualizations & Insights

### 📊 Distribution of Hourly Usage

- Most energy usage values are between **12,000–20,000 MW**
- Right-skewed distribution indicates occasional **high-demand spikes** (up to 25,000+ MW)

### 🕒 Average Usage by Hour of Day

- Energy usage **peaks between 17:00–18:00**
- Usage is **lowest between midnight and 6:00 AM**

### 📅 Average Usage by Day of the Week

- **Tuesday** has the **highest average usage**
- **Sunday** shows the **lowest**, revealing a **workday–weekend pattern**

### 📆 Average Monthly Usage

- **Winter months (Jan–Feb)** and **Summer (Jul–Aug)** show **peak usage**
- **Spring and early fall** months have **lower usage**

### 📈 Average Yearly Usage

- Demand **increased steadily** until around **2011**, followed by a **decline until 2017**
- **2018** shows a **strong recovery**, possibly due to external factors

---

## 🧠 Conclusion & Takeaways

- Energy consumption follows **strong daily, weekly, and seasonal patterns**
- **Afternoon peaks** and **weekday surges** highlight times for load management
- **Winter and summer months** consistently demand more energy
- Sudden dips in some years (e.g., 2009, 2013, 2017) may require further investigation

This analysis builds a foundation for future work such as **energy forecasting**, **anomaly detection**, or integrating **external factors like weather or policy** for advanced modeling.

---

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 👤 About Me

I am **Mahmood Arafat**, a Mechanical Engineer transitioning into **AI and Data Science** for Engineering Systems.  
This project is part of my learning portfolio to demonstrate proficiency in exploratory data analysis and time-series visualization.

🔗 [Connect on LinkedIn](https://www.linkedin.com/in/arafat-mahmood-3b0208213/)  



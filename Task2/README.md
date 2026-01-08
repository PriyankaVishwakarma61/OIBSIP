# 📊 Unemployment Rate Analysis in India During Covid-19

## 📌 Project Overview
Unemployment is measured by the **unemployment rate**, which is the percentage of unemployed people in the total labour force.  
During the Covid-19 pandemic, India witnessed a **sharp increase in unemployment** due to nationwide lockdowns and economic slowdown.

This project uses **data science techniques** to analyze the **impact of Covid-19 on unemployment in India** using real-world data.

---

## 🎯 Objectives
- Analyze unemployment trends before and during Covid-19
- Perform proper data preprocessing
- Visualize changes in unemployment rate over time
- Compare **Pre-Covid** and **Covid** periods

---

## 📂 Dataset
- **Source:** Unemployment in India dataset  
- **Format:** CSV  
- **Attributes include:**
  - Region
  - Date
  - Estimated Unemployment Rate (%)
  - Estimated Employed
  - Labour Participation Rate (%)
  - Area (Urban/Rural)

---

## 🛠 Tools & Technologies
- Python 🐍
- Pandas
- Matplotlib
- Google Colab / Jupyter Notebook

---

## 🧹 Data Preprocessing Steps
The dataset was preprocessed using the following steps:
1. Removed extra spaces from column names
2. Handled missing values
3. Converted date column to datetime format
4. Renamed columns for clarity
5. Feature engineering:
   - Extracted **Year**
   - Extracted **Month**
   - Created **Covid_Period** feature (Pre-Covid / Covid)

---

## 📊 Analysis & Visualization
- Calculated average unemployment rate over time
- Visualized unemployment trends using line plots
- Compared unemployment rates between Pre-Covid and Covid periods

---

## 📈 Key Insights
- Unemployment rate increased sharply during Covid-19
- Lockdown months showed the highest unemployment levels
- Gradual recovery observed after restrictions were lifted

---

## 🧪 How to Run the Project
1. Clone the repository
   ```bash
   git clone https://github.com/your-username/unemployment-analysis.git


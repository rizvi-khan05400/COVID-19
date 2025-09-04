# 🦠 COVID-19 Data Analysis

This project analyzes COVID-19 cases across different regions using Python, Pandas, Matplotlib, and Seaborn.  
The dataset includes information on **Confirmed, Deaths, and Recovered cases**.

---

## 📊 Steps Performed

1. **Data Cleaning**
   - Checked for missing values
   - Removed columns with only null values
   - Filtered records with Confirmed cases > 10

2. **Exploratory Data Analysis**
   - Heatmap to visualize missing values
   - Grouped data by Region for case summaries
   - Identified worst-affected regions

3. **Visualizations**
   - Bar charts for Confirmed, Deaths, and Recovered cases
   - Top 10 regions with maximum cases
   - Bottom 50 records with lowest confirmed cases
   - Time-series trend analysis (for India till 29 April 2020)

4. **Insights**
   - COVID-19 impact was uneven across regions
   - Some regions showed extremely high confirmed cases
   - Recovery and death patterns closely followed confirmed cases
   - Sorting trends highlighted most & least affected regions

---

## 📌 Conclusion
- COVID-19 cases varied widely across regions  
- Certain areas were hit harder, requiring focused healthcare strategies  
- Recovery and death rates correlated with confirmed cases  
- Data-driven insights help in **better decision-making & future preparedness**  

---

## ⚙️ Requirements
- Python 3.x  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

Run the notebook using:
```bash
jupyter lab

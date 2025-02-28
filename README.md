# 📊 Student Performance Data Analysis

This project explores student performance data to uncover meaningful insights and trends. The analysis focuses on identifying the relationships between various factors—such as study habits, parental education, family income, stress levels, and extracurricular activities—and academic outcomes.  

## 🚀 Key Features

- **Data Cleaning and Preprocessing:**  
  - Handled missing values using median (for numerical columns) and mode (for categorical columns).  
  - Corrected inaccurate grade data by reassigning grades based on total scores.  
  - Detected and visualized outliers using Z-scores.  
  - Dropped irrelevant columns and standardized column names.  

- **Exploratory Data Analysis (EDA):**  
  - Analyzed student distribution by department, age, and gender.  
  - Investigated correlations between attendance, study hours, and scores.  
  - Explored the impact of stress levels, sleep patterns, and internet access on performance.  
  - Visualized data using heatmaps, scatter plots, and histograms.  

- **Feature Engineering:**  
  - Introduced new metrics like **Score Consistency**, **Participation-Project Ratio**, and **Improvement Score**.  
  - Binned study hours and analyzed their relationship with academic performance.  
  - Created a **Weighted Score** combining assessment components to measure overall effort.  

## 📈 Insights and Findings

- **Balanced Effort Matters:** Consistent performance across all assessments leads to better scores.  
- **Study Habits:** The optimal range for study hours is **20–25 hours/week**—beyond this, returns diminish.  
- **Project-Based Learning:** High-achieving students emphasized hands-on project work over classroom participation.  
- **Stress and Sleep:** No strong correlation was found between stress-to-sleep balance and final grades.  
- **Parental Education and Income:** These factors showed minimal direct impact on academic success.  

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Plotly  
- **Data Source:** Custom student performance dataset (5,000 records)  

## 📚 Conclusion

This project highlights the complex interplay of academic and behavioral factors influencing student performance. While consistent study habits and project-based learning show clear benefits, external factors like stress, income, and parental education appear to play a smaller role in determining outcomes.  


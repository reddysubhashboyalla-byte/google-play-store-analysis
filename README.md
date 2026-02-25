#  Google Play Store Data Analysis

##  Project Overview
This project performs end-to-end exploratory data analysis (EDA) on the Google Play Store dataset to identify key factors influencing app ratings, installs, and pricing behavior.

##  Objectives
- Clean and preprocess raw Play Store data  
- Analyze factors affecting app installs  
- Compare Free vs Paid app performance  
- Visualize rating distributions and trends  

##  Tools & Technologies
- Python  
- Pandas  
- Matplotlib  
- Jupyter Notebook  

##  Data Cleaning
- Handled missing and inconsistent values  
- Converted `Installs` to numeric format  
- Standardized `Size` column to MB  
- Removed invalid and outlier ratings  

## 📊 Key Insights
- Paid apps show a slightly higher median rating than free apps  
- App size has a weak positive correlation with installs (r ≈ 0.16)  
- The majority of apps on the Play Store are free  
- Rating distributions for free and paid apps largely overlap  

## Project Structure
```
Google-Play-Store-Analysis/
│
├── data/
├── notebooks/
└── README.md
```

##  Future Improvements
- Build interactive dashboard (Power BI / Streamlit)  
- Perform statistical significance testing  
- Develop predictive model for app success  
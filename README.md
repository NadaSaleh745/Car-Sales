# Car-Sales
🚗 Car Purchase Data Analysis

## 📚 Table of Contents

1. [📊 Project Overview](#-car-purchase-data-analysis)  
2. [🎯 Key Objectives](#-key-objectives)  
3. [🛠️ Tools & Technologies](#-tools--technologies)  
4. [🔍 Data Analysis Workflow](#-data-analysis-workflow)  
   - [1️⃣ Data Cleaning](#1️⃣-data-cleaning)  
   - [2️⃣ Exploratory Data Analysis (EDA)](#2️⃣-exploratory-data-analysis-eda)  
   - [3️⃣ Geospatial Mapping](#3️⃣-geospatial-mapping)  
   - [4️⃣ Correlation Analysis](#4️⃣-correlation-analysis)  
   - [5️⃣ Outlier Detection & Removal](#5️⃣-outlier-detection--removal)  
   - [6️⃣ Machine Learning](#6️⃣-machine-learning)  
5. [💡 Key Insights](#-key-insights)  
6. [🚀 Conclusion](#-conclusion)  
7. [⭐ Support](#-if-you-found-this-project-useful-feel-free-to-give-it-a-star-)  


📊 Project Overview
This project presents a comprehensive Exploratory Data Analysis (EDA) on a car purchase dataset to uncover valuable insights into customer demographics, purchasing behavior, and financial attributes.
________________________________________
🎯 Key Objectives
•	Understand Relationships: Explore how factors like age, annual salary, and net worth influence car purchase amounts.
•	Demographic Insights: Analyze gender distribution and country-wise customer segmentation.
•	Global Sales Visualization: Map car sales globally using interactive geospatial mapping.
•	Outlier Detection: Identify and eliminate data outliers to enhance analytical accuracy.
•	Predictive Modeling: Build models to forecast car purchase amounts using machine learning.
________________________________________
🛠️ Tools & Technologies
•	Python: Core language for data analysis.
•	Pandas & NumPy: Efficient data manipulation and numerical operations.
•	Matplotlib & Seaborn: Stunning data visualizations and correlation heatmaps.
•	Folium & Geopy: Interactive geospatial analysis and mapping.
•	Scikit-learn: Machine learning for predictive modeling.
________________________________________
🔍 Data Analysis Workflow
1️⃣ Data Cleaning
•	Corrected inconsistent country names.
•	Handled missing and null data for reliable analysis.
2️⃣ Exploratory Data Analysis (EDA)
•	Box Plots: Detected outliers in car purchase amounts.
•	Scatter Plots: Analyzed relationships between purchase amounts, age, salary, and net worth.
•	Pie Charts: Visualized gender distribution among car buyers.
3️⃣ Geospatial Mapping
•	Mapped global car sales using latitude & longitude.
•	Created interactive world maps highlighting country-wise sales with Folium.
4️⃣ Correlation Analysis
•	Generated heatmaps to visualize relationships between Age, Credit Card Debt, Annual Salary, Net Worth, and Car Purchase Amount
5️⃣ Outlier Detection & Removal
•	Applied the Interquartile Range (IQR) method to identify and eliminate outliers, enhancing data integrity.
6️⃣ Machine Learning
•	Data Preparation: Selected key features - Age, Annual Salary, Net Worth - and target variable Car Purchase Amount.
•	Model Training: Implemented Linear Regression using Scikit-learn.
•	Evaluation Metrics: 
o	R-squared (R²)
o	Mean Squared Error (MSE)
•	Visualization: Created scatter plots comparing actual vs. predicted purchase amounts for both training and testing sets.
________________________________________
💡 Key Insights
•	Strong Correlations between annual salary, net worth, and car purchase amounts.
•	Geographic Trends: Certain countries exhibited higher car purchase activity.
•	Predictive Modeling: The linear regression model showcased good predictive capabilities, identifying key financial indicators influencing purchase decisions.
________________________________________
🚀 Conclusion
This project demonstrates a holistic approach to data analysis, blending:
•	Traditional EDA Techniques
•	Advanced Geospatial Mapping
•	Statistical Correlation Analysis
•	Predictive Modeling with Machine Learning
It serves as a robust framework for analyzing consumer behavior and making data-driven decisions in the automotive sector.
________________________________________
⭐ If you found this project useful, feel free to give it a star! ⭐


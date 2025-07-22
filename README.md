**🚗 Vehicle Sales EDA Project**

<img width="318" height="159" alt="image" src="https://github.com/user-attachments/assets/4cd5eb53-35c6-451c-81f3-b17fdffc68fc" />



**📊 Exploratory Data Analysis on Used Car Sales Data**



**📝 Table of Contents**

*  Overview

*  Business Objective

*  Dataset Description

*  EDA Process

*  Visual Insights

*  Key Findings

*  Conclusion

*  Technologies Used

*  Author




**📌 Overview**

This repository contains a detailed Exploratory Data Analysis (EDA) of a used vehicle sales dataset. The objective is to uncover pricing patterns, identify key predictors of price, detect outliers, and prepare the data for future predictive modeling.

**🎯 Business Objective**

*  Identify which factors influence used vehicle selling prices.

*  Detect trends and hidden patterns using visualization techniques.

* Support pricing decisions using data-driven insights.

*  Prepare the dataset for machine learning applications.

**📂 Dataset Description**

Column Name	Description

*  year	Year the vehicle was manufactured
*  condition	Condition score (categorical/ordinal)
*  odometer	Total kilometers/miles driven
*  mmr	Manheim Market Report (Market Reference Price)
*  sellingprice	Final sale price of the vehicle
*  sale_month_num	Numeric month of sale (1–12)

**🔍 EDA Process**

*  Loading & Cleaning

*  Dropped duplicates and nulls

*  Handled outliers

*  Checked datatypes

**Univariate & Bivariate Analysis**

Distribution plots

Correlation matrix

Pairwise relationships using pairplot

**Feature Insights**

*  Detecting multicollinearity

*  Highlighting relationships affecting price

**🖼️ Visual Insights**

📌 Correlation Heatmap

Shows the correlation between numerical features.

<img width="1034" height="689" alt="image" src="https://github.com/user-attachments/assets/3b3383c8-f999-42e3-82f4-9efb2035f5b2" />

**📌 Pairplot of Numerical Features** 

Helps visualize relationships and distributions between all numerical features.

<img width="1473" height="1526" alt="image" src="https://github.com/user-attachments/assets/8a273c6b-17e5-42b2-9d4e-3492468518e9" />

**📈 Key Findings**

*  MMR (market price) has a very strong positive correlation with sellingprice (+0.98).

*  Odometer reading is strongly negatively correlated with selling price — higher mileage = lower value.

*  Newer cars (higher year) tend to have higher selling prices.

*  Vehicle condition plays a role but needs standardization or binning.

*  Sale month does not significantly impact price, so no strong seasonality pattern detected.

**✅ Conclusion**

*  Key features influencing price: year, odometer, condition, and mmr.

*  mmr can be used as a benchmark, but avoid including it with sellingprice in the same regression due to high collinearity.

*  Outliers should be capped/removed to improve model performance.

**Final dataset is EDA-ready and model-friendly.**

**🛠️ Tools Used**

*  Python

*  Pandas & NumPy

*  Matplotlib & Seaborn

*   Google Colab


**👤 Author**

**Sagar Jain**

🎓 Master's in Data Science | 💼 Business + Trading Background
LinkedIn | GitHub


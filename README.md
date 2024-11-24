# Python for Analyzing Purchase Behavior on Black Friday – Walmart Inc.

## Overview

This project investigates customer purchasing behavior at Walmart Inc., focusing on gender, age, and marital status. By analyzing a dataset of over 550,000 transactions, we explore spending patterns and trends to provide actionable insights for Walmart's strategic decision-making.

## Key Objectives

1. **Understand demographic-based purchasing behavior:** Explore variations in spending across gender, age groups, and marital status.
2. **Analyze key trends:** Identify high-spending demographics and popular products.
3. **Provide actionable insights:** Assist Walmart in improving marketing strategies, inventory planning, and customer experience.

---

## Dataset Information

- **Size:** 550,068 rows, 10 attributes.
- **Key Attributes:**  
  - **Customer Demographics:** Gender, Age, Marital Status, City Category.  
  - **Purchase Data:** Purchase Amount, Product Codes.

---

## Methodology

### 1. **Preprocessing**
   - **Data Cleaning:** Removal of null values and duplicates.
   - **Outlier Detection:** Utilized Interquartile Range (IQR) for identifying and addressing outliers.
   - **Feature Encoding:** Encoded categorical variables for analysis.
   - **Exploratory Data Analysis (EDA):** Basic statistics and distribution checks.

### 2. **Univariate Analysis**
   - **Techniques:** Bar plots, pie charts, count plots.
   - **Focus:** 
     - Gender distribution.
     - Age demographics.
     - Marital status proportions.
     - Popular products by gender.

### 3. **Bivariate Analysis**
   - **Techniques:** Box plots, line graphs.
   - **Focus:** 
     - Spending trends based on gender and age.
     - Impact of marital status on spending patterns.
   - **Correlation Analysis:** Assessed relationships between categorical and numerical attributes.

### 4. **Statistical Analysis - Central Limit Theorem (CLT)**
   - **Bootstrap Sampling:** Enhanced reliability by constructing confidence intervals.
   - **Confidence Intervals:** Estimated population mean for spending patterns.

---

## Key Findings

### **1. Gender-Based Insights**
   - Men constitute **75%** of the customer base and spend more on average than women.
   - Confidence Interval (95%):  
     - Male Spending: **$9,407 to $9,469**.  
     - Female Spending: **$8,705 to $8,764**.

### **2. Age-Based Insights**
   - Highest spending group: **50-55 years.**  
   - Lowest spending group: **0-17 years.**

### **3. Marital Status-Based Insights**
   - Unmarried customers spend slightly more than married customers.
   - Spending gap is minimal, indicating marriage is not a significant factor.

### **4. Popular Products**
   - Certain product categories show distinct preferences by gender and age group, influencing inventory planning.

---

## Visualizations

### Univariate Analysis
- **Bar and Pie Charts:** Gender, age, and marital status distributions.

### Bivariate Analysis
- **Box Plots:** Spending trends across demographics.
- **Line Graphs:** Average spending trends by age.

### Statistical Analysis
- Confidence intervals to validate findings and highlight spending disparities.

---

## Tools and Technologies

- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn.  
- **Statistical Techniques:** Central Limit Theorem, Bootstrap Resampling.

---

## Conclusion

This project reveals significant insights into Walmart's customer purchasing patterns:
- **Gender:** Men spend more consistently than women.  
- **Age:** The **50+ age group** spends the most.  
- **Marital Status:** Differences between married and unmarried customers are minimal.  

These findings empower Walmart to develop data-driven strategies to improve marketing campaigns, personalize customer experiences, and optimize inventory management.


---

## References

1. Tengli, A., Srinivasan, S. H. (2022). [Gender-Based Purchase Behavior Study on Natural Cosmetics](https://doi.org/10.3390/cosmetics9050101).  
2. Pakasi, A., Tumiwa, J. (2016). Comparison Analysis of Male and Female Consumer Purchase Behavior.  
3. Ronaghi, M., Danae, H., & Haghtalab, H. (2013). Effects of Gender on Consumer Behavior.  
4. Abir Smiti (2020). [Outlier Detection Methods in Data Analysis](https://www.sciencedirect.com/science/article/pii/S1574013720304068).  

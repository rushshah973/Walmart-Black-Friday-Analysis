# Black Friday Customer Purchase Analysis

## 📋 Overview  
This project analyzes customer purchase data from Walmart's Black Friday sales. The goal is to understand spending habits across various demographics, including gender, age, marital status, city category, and product preferences, to provide actionable insights for strategic decision-making.

---

## 🔍 Problem Statement  
Walmart's management wants to analyze spending patterns to answer:  
- Do women spend more than men on Black Friday?  
- How do factors like age, marital status, and city category affect spending?  
- Which product categories are most frequently purchased?

---

## 📊 Dataset Description  
The dataset (`walmart_data.csv`) includes:  
- **User_ID, Product_ID**: Unique identifiers for customers and products.  
- **Gender**: Customer's gender (`Male`, `Female`).  
- **Age**: Age group (`18-25`, `26-35`, etc.).  
- **Occupation**: Profession (masked).  
- **City_Category**: Purchase city category (`A`, `B`, `C`).  
- **Stay_In_Current_City_Years**: Number of years in the current city.  
- **Marital_Status**: `0` = Single, `1` = Married.  
- **Product_Category**: Masked product type.  
- **Purchase**: Purchase amount.

---

## 🔑 Key Insights  

### Gender & Age  
- **Males** contribute **75%** of purchases with an average spend of **$925,408.28**, compared to **$712,217.18** by females (**25%** of purchases).  
- **Age Group 25-40** accounts for ~80% of total spending.  

### Marital Status  
- **Single customers** (60%) spend more than married customers (40%).  

### City Trends  
- **City B** has the highest sales, but **City C** drives demand for specific products.  
- Customers living **1 year** in their city spend the most.  

### Product Preferences  
- **Product Categories 1, 5, 8, and 11** have the highest purchase frequency.  

---

## ✅ Recommendations  
1. **Target Marketing**: Focus on acquiring and retaining **female customers** and younger demographics.  
2. **City Expansion**: Open more stores in **tier-1 (City A)** and **tier-3 (City C)** cities.  
3. **Product Strategy**: Prioritize top-selling categories; promote underperforming ones through discounts or bundles.  
4. **Customer Offers**: Design offers tailored for **married customers** to increase spending.  

---

## 📁 Project Structure  
- `walmart_data.csv`: Dataset.  
- `BlackFridayAnalysis.ipynb`: Jupyter Notebook containing analysis.  
- `Visualizations/`: Folder with generated charts and graphs.  

---

## 🛠 Tools and Technologies  
- **Python**: pandas, numpy, matplotlib, seaborn.  
- **Jupyter Notebook**: Data analysis and visualization.  

---

## 📞 Contact  
**Name**: Rushabh Shah  
**Email**: [shahrushabh973@gmail.com]  


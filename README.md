# 🧹 Data Cleaning & Preprocessing – Customer Personality Analysis

## 📌 Project Overview
This task is part of my **Data Analytics Internship (Task 1)**, focusing on **data cleaning and preprocessing**.  

The dataset used is the **Customer Personality Analysis dataset** from Kaggle, which contains demographic and spending behavior details of customers.  

The objective was to **clean and prepare raw data** by handling missing values, removing duplicates, standardizing formats, and ensuring consistency across all fields.

---

## 📂 Dataset

- **Source:** [Kaggle – Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)  

---

## 🛠️ Tools Used

- **Excel** → for data cleaning, missing value imputation, formatting.

---

## 🔑 Data Cleaning Steps

1. **Imported dataset** using correct delimiter (`;`) in Excel.  
2. **Handled missing values**:  
   - `Income` column had missing values.  
   - Replaced blanks with the **median income value**.  
3. **Removed duplicates** using Excel’s “Remove Duplicates” feature.  
4. **Standardized categorical values**:  
   - Converted text columns (`marital_status`, `education`, `country`) to Capitalized.  
   - Unified categories (e.g., `married` & `together` → `married`).  
5. **Fixed date formats**:  
   - Converted `Dt_Customer` to **DD-MM-YYYY** format.  
6. **Renamed columns** for consistency:  
   - Example: `Year_Birth` → `year_birth`, `MntWines` → `mnt_wines`.  
7. **Ensured correct data types**:  
   - Numeric: `income`, purchases, accepted campaigns, recency.  
   - Date: `dt_customer`.  
   - Text: `education`, `marital_status`.  

---

## ✅ Deliverables

- `customer_personality_cleaned.csv` → Cleaned dataset.   

---

## 📊 Summary of Changes

- Missing `income` values replaced with median.   
- Standardized text values (`Marital_Status `, Capitalized).  
- Dates converted to proper format.  
- Clean, consistent column naming convention applied.  

---


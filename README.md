# Project--Sugarcane-Production
This project analyzes global sugarcane production by exploring key factors like production volume, land usage, and yield per hectare across different countries and continents. Through comprehensive Exploratory Data Analysis (EDA), we'll identify top-producing regions, relationships between variables, and visualize the distribution of production. 

# 🌾 Sugarcane Production Analysis

This project explores global sugarcane production data, including cleaning, univariate/bivariate analysis, and insights by continent.

---

## 📦 Dataset

- **Columns**: Country, Continent, Production, Acreage, Yield, Production per Person  
- **Issues**: Unwanted characters, missing values, inconsistent column names

---

## 🧹 Data Cleaning

- Removed special characters (commas, periods) from numeric fields  
- Renamed columns for consistency  
- Dropped missing values and unused columns  
- Converted numeric columns to `float`

---

## 📊 Analysis Overview

### Univariate:
- **Continent-wise count**: Africa (38), Asia (25), etc.
- **Distributions**: Production & Yield are highly skewed
- **Outliers**: Brazil, India, and China stand out in production

### Bivariate:
- **Top Acreage**: Brazil, India, China  
- **Highest Yield**: Guatemala  
- **Highest per Capita**: Paraguay  
- **Correlation**:  
  - Acreage vs Production → strong (0.997)  
  - Yield vs Production → weak (0.13)  

### Continental:
- **Top Producers**: South America, Asia, Africa  
- Fewer countries ≠ less production (Brazil dominates)

---

## 🛠️ Tools Used

- Python, Pandas, Seaborn, Matplotlib, Jupyter Notebook

---

## ✅ Key Insights

- Big land = more production  
- High efficiency ≠ high total output  
- Continental differences shaped by few dominant countries

---

## 📁 Structure

```
/data - Raw & cleaned CSV  
/notebooks - Jupyter files  
README.md - Project overview  
```

---

## 💬 Contributions Welcome!

Feel free to fork, open issues, or submit pull requests.

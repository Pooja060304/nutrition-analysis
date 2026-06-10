# Global Protein Supply & Health Analysis 🌍

## About This Project
This project analyzes global protein supply data across 170 countries to uncover 
patterns between diet, obesity, and undernourishment worldwide.

## Dataset
- **Source:** FAO Global Protein Supply Quantity Data
- **Coverage:** 170 countries
- **Features:** Protein supply from 20+ food categories, obesity rates, 
  undernourishment rates, and COVID-19 statistics

## Questions Answered

### 1. Which 10 countries get the most protein from Meat?
Findings: Argentina leads with 21.6g, followed by Mongolia (19.8g) and Samoa (19.4g). 
Western and South American countries dominate meat protein consumption.

### 2. Is there a relationship between Animal Products and Obesity?
Findings: A moderate positive correlation (r = 0.62) was found — countries with 
higher animal product protein supply tend to have higher obesity rates.

### 3. Which 10 countries have the highest Undernourishment rates?
Findings: Central African Republic (59.6%) has the highest rate, followed by 
Zimbabwe (51.3%) and Haiti (49.3%). African nations dominate this list.

## Tools Used
- Python
- Pandas (data loading, cleaning, analysis)
- Matplotlib & Seaborn (data visualization)
- Google Colab

## Key Steps
1. Loaded and explored a 170-row dataset with 32 columns
2. Cleaned missing values (dropped rows with nulls)
3. Performed exploratory data analysis (EDA)
4. Created visualizations to answer each question

## Files
- `Download.ipynb` — Full analysis notebook
- `Protein_Supply_Quantity_Data.csv` — Dataset used
- `animal_products_vs_obesity.png` — Scatter plot: Animal Products vs Obesity
- `vegetal_products_vs_obesity.png` — Scatter plot: Vegetal Products vs Obesity

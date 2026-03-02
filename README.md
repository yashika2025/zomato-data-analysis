# zomato-data-analysis
This project performs exploratory data analysis (EDA) on the Zomato restaurant dataset to uncover trends and insights about restaurant ratings, pricing, cuisine preferences, and more using Python.

The goal is to extract meaningful business insights using data cleaning, transformation, and visualization techniques.

---

## 🚀 Project Objectives

- Explore restaurant data from Zomato
- Clean and preprocess raw data
- Analyze relationships between ratings, price, and other features
- Answer key business questions using data insights
- Visualize trends to support conclusions

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---


## 🔎 Methodology

The project follows these core steps:

1️⃣ **Data Loading**  
Loaded the dataset and performed initial inspection of fields.

2️⃣ **Data Cleaning & Preprocessing**
- Removed null values
- Fixed inconsistent entries
- Converted numeric columns to proper formats
- Cleaned categorical values

3️⃣ **Exploratory Data Analysis (EDA)**
- Analyzed top-rated restaurants
- Relationship between price and rating
- Cuisine preference across cities
- Distribution of ratings

4️⃣ **Visualizations**
- Bar charts
- Pie charts
- Heatmaps
- Scatter plots

---

## 📈 Results & Key Conclusions

After analyzing the Zomato dataset, the following insights were derived:

### ⭐ Top Rated Restaurants
- Restaurants with higher ratings typically belong to categories like **Fine Dining** or **High-end Casual Dining**.
- Some smaller local restaurants also scored high but with fewer total ratings, suggesting niche customer satisfaction.

### 💰 Price vs. Rating
- There is **no strong linear correlation between high prices and high ratings**.  
  Mid-range restaurants often receive better overall ratings compared to very expensive or very cheap ones.
- Ratings tend to cluster between **3.5 and 4.5**, regardless of cost.

### 🍕 Best Cuisines by Rating
- Certain cuisines such as **Italian**, **North Indian**, and **Continental** consistently receive higher average ratings, indicating customer preference.
- Regional cuisines varied widely by city.

### 📍 City-wise Insights
- Metropolitan cities like **Delhi, Bangalore, and Mumbai** have the widest diversity of restaurants and cuisines.
- Smaller cities often have fewer listings, but some showcase high average ratings due to niche quality offerings.

### 🍽️ Rating Distribution
- Majority of restaurants fall in the **3.5–4.5 rating range**, showing general customer satisfaction.
- Very high ratings (above 4.5) are less common and often come from specialized or highly-reviewed establishments.

---

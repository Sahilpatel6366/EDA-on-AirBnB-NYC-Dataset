# 🏙️ Airbnb NYC Data Analysis – EDA Project

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the **Airbnb New York City** dataset to uncover trends, patterns, and insights about listings, pricing, availability, and customer preferences.

The goal is to understand how **location**, **property type**, and other factors influence **pricing** and **occupancy rates** across different NYC boroughs.

---

## 🛠️ Tools & Libraries Used

- **Python** – Data analysis and visualization  
- **Pandas** – Data cleaning and manipulation  
- **NumPy** – Numerical operations  
- **Matplotlib** and **Seaborn** – Data visualization  
- **Jupyter Notebook** – Interactive analysis

---

## 📂 Dataset Information

- **Dataset Name:** Airbnb NYC Listings Dataset  
- **Records:** ~48,000+ listings  
- **Features:** 16 attributes  

### 🧾 Key Columns
| Column | Description |
|---------|-------------|
| neighbourhood_group | Borough name – Manhattan, Brooklyn, Queens, Bronx, Staten Island |
| room_type | Type of listing – Entire home/apt, Private room, Shared room |
| price | Nightly price of the listing |
| availability_365 | Number of available days per year |
| number_of_reviews | Total reviews received |
| latitude, longitude | Coordinates for mapping listings |

---

## 🔍 EDA Process

### 1️⃣ Data Cleaning & Preprocessing
- Checked and handled missing values and duplicates  
- Removed outliers (extreme prices, unrealistic availability values)  
- Converted incorrect data types  

### 2️⃣ Univariate Analysis
- Price distribution  
- Frequency of listings by neighbourhood group and room type  

### 3️⃣ Bivariate & Multivariate Analysis
- Price variations by neighbourhood group and room type  
- Correlation between reviews, availability, and price  

### 4️⃣ Geospatial Analysis
- Visualized listings on NYC map using latitude and longitude  
- Identified price hotspots

---

## 📊 Key Insights

- 🏙️ **Manhattan** has the highest average prices, while **Brooklyn** offers many moderately priced listings.  
- 🏡 **Entire homes/apartments** are the most expensive, while **shared rooms** are the cheapest.  
- 💎 Certain neighbourhoods show price anomalies, indicating **premium or luxury listings**.  
- 📆 Many listings are available year-round, showing **professional hosting activity**.

---

## 📈 Visualizations Included

- Price distribution histograms  
- Room type vs price boxplots  
- Neighbourhood group comparison bar charts  
- Correlation heatmap  
- Geospatial scatter plot of listings across NYC

---

## 💡 Business Impact

| Stakeholder | Benefit |
|--------------|----------|
| **Hosts** | Price listings competitively based on neighborhood and property type |
| **Travelers** | Identify affordable areas and property types |
| **Airbnb (Platform)** | Detect unusual pricing or availability patterns |

---




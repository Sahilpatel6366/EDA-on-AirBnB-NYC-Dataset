🏙️ Airbnb NYC Data Analysis – EDA Project
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Airbnb New York City dataset to uncover key trends, patterns, and insights about listings, pricing, availability, and customer preferences.

The analysis aims to understand how location, property type, and other factors influence price and occupancy rates across different boroughs of NYC.

🛠️ Tools & Libraries Used

Python → Data analysis & visualization

Pandas → Data cleaning & manipulation

NumPy → Numerical operations

Matplotlib & Seaborn → Data visualization

Jupyter Notebook → Interactive analysis environment

📂 Dataset Information

Dataset Name: Airbnb NYC Listings Dataset
Records: ~48,000+ listings
Features: 16 attributes

🧾 Key Columns
Column	Description
neighbourhood_group	Borough name – Manhattan, Brooklyn, Queens, Bronx, Staten Island
room_type	Type of listing – Entire home/apt, Private room, Shared room
price	Nightly price of the listing
availability_365	Number of available days per year
number_of_reviews	Total number of reviews received
latitude, longitude	Coordinates for geospatial mapping
🔍 EDA Process
1️⃣ Data Cleaning & Preprocessing

Checked and handled missing values and duplicates

Removed outliers (e.g., extreme prices, unrealistic availability values)

Fixed incorrect data types

2️⃣ Univariate Analysis

Price distribution

Frequency of listings by neighbourhood group and room type

3️⃣ Bivariate & Multivariate Analysis

Price vs Neighbourhood group & Room type

Correlation between reviews, availability, and price

4️⃣ Geospatial Analysis

Visualized listings on an NYC map using latitude & longitude

Identified price hotspots and high-demand areas

📊 Key Insights

🏙️ Manhattan has the highest average prices, while Brooklyn offers many moderately priced listings.

🏡 Entire homes/apartments are the most expensive, whereas shared rooms are the cheapest.

💎 Certain neighborhoods show price anomalies, indicating premium or luxury listings.

📆 A large number of listings are available year-round, suggesting professional hosts dominate the market.

📈 Visualizations Included

📊 Price distribution histograms

📦 Room type vs price boxplots

🏘️ Neighbourhood group comparison bar charts

🔥 Correlation heatmap

🗺️ Geospatial scatter plot of listings across NYC

💡 Business Impact
Stakeholder	Benefit
Hosts	Price their listings competitively based on neighborhood & property type
Travelers	Identify affordable areas and property types
Airbnb (Platform)	Detect unusual pricing or availability patterns to ensure market balance

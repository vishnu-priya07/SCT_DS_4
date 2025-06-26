✅ Task 04: US Accidents Dataset – Geospatial & Trend Analysis
📌 Objective:
Analyze the US_Accidents_March23.csv dataset to uncover accident patterns based on location, time, and environmental conditions. The aim is to provide insights for road safety improvements.

📁 Dataset Used:
US_Accidents_March23.csv
Contains ~7.5 million accident records with 47 features like:

Time: Start_Time, End_Time

Location: City, State, Latitude, Longitude

Weather & Environment: Weather_Condition, Visibility(mi), Humidity(%), Temperature(F), Pressure(in), Wind_Speed(mph)

Traffic & Road Info: Severity, Distance(mi), Street, Side, Description

🛠️ Technologies & Libraries Used:
Python

Pandas – for data loading, preprocessing, and summarization

Matplotlib & Seaborn – for trend and category-based visualizations

Folium – for plotting accidents on interactive maps

Missingno (optional) – for missing data heatmap

🧾 Steps Followed:
1️⃣ Data Loading & Cleaning
Load only first 100k rows for performance

Drop unused columns

Check for null values

Convert date/time columns to datetime objects

2️⃣ Exploratory Data Analysis (EDA)
Severity distribution – Pie/Bar chart

Top 10 cities with most accidents

Accidents per state

Accident trend over hours of the day

Monthly/Yearly trends

3️⃣ Geospatial Analysis
Plot a sample of 1000-2000 records on a Folium map using Latitude & Longitude

Color-code markers by Severity

4️⃣ Environmental Factors
Compare accident count by:

Weather condition

Visibility

Temperature

Humidity

5️⃣ Correlation Heatmap
Analyze correlation between numerical features like Distance, Visibility, Temperature, etc.

📊 Key Insights (Example):
Most accidents occur between 7–9 AM and 4–6 PM

California, Texas, and Florida have the highest accident rates

Low visibility, rainy weather, and high humidity are associated with higher severity

Many accidents are clustered in urban zones

🗂️ Output Files:
task04.ipynb or .py

US_Accidents_March23.csv (used partially)
download csv file from below link:
https://smoosavi.org/datasets/us_accidents

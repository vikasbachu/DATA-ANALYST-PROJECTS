📊 Project Overview
This Power BI dashboard analyzes Airbnb listing performance using data sourced from Kaggle. The project integrates three datasets — Listings, Calendar, and Reviews — to deliver a holistic view of host activity, pricing trends, availability, and customer engagement across multiple cities.

🧰 Tools & Technologies
Power BI
Power Query
DAX
Kaggle (Data Source)

⚙️ Data Workflow
Combined calendar.csv, listings.csv, and reviews.csv using the id field via Power BI’s relationship model
Cleaned the data in Power Query by removing nulls, duplicates, and errors
Loaded refined data into Power BI and created calculated measures using DAX

📈 Dashboard Features
📄 Page 1: Revenue & Host Analysis
💰 Total Revenue, Average Price, Average Rating – KPI cards
📆 Date Slicer – dynamic time-based filtering
📊 Revenue by Date (Line Chart) – visualizes daily income
📍 Revenue by City (Clustered Bar Chart) – compares city-level earnings
👤 Total Hosts – displayed in KPI
📄 Page 2: Availability & Location Insights
🏅 Top 10 Hosts (Table) – based on performance metrics
📆 Availability by Year (Slicer) – filters listing availability
🗺️ Price by Location (Map Visual) – geospatial visualization of listings
📈 Average Price Trend (Line Chart) – pricing variation over time
🏠 Accommodation Type (Pie Chart) – share of room types
🌆 Total Cities – KPI card

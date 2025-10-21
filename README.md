🚍 Optimizing Public Transit Operations — MetroMove EDA

📘 Project Overview
This project performs an Exploratory Data Analysis (EDA) on MetroMove Transit Solutions' public transportation data.
The goal is to uncover insights into passenger behavior, fare trends, and operational performance to help the company make data-driven decisions that improve efficiency and customer satisfaction.

🧾 Dataset Summary
Records: ~1,000 trips
Features: Trip ID, Mode of Transport, Stations, Passenger Count, Fare Amount, Trip Duration, Date, and Day of Week
Modes: Bus, Train, Ferry, Tram
Issues handled: Missing values, inconsistent casing, and whitespace errors

🧹 Data Cleaning
Removed empty “Unnamed” columns
Filled missing values using the median
Standardized text (Bus, Train, Tram, Ferry)
Converted date/time fields to proper format

📊 Exploratory Analysis
Performed Univariate, Bivariate, and Multivariate analysis to answer:

Which transport mode has the highest usage?
How do fares vary across modes?
Which days have the highest passenger traffic?
How do trip duration and fare correlate?

🧠 Key Insights
Buses dominate in frequency but have the lowest average fare.
Trains generate higher revenue per trip but fewer journeys.
Passenger traffic peaks on Fridays and Mondays.
Ferries and trams show stronger weekend activity.
Some trips have unusually long durations, indicating potential delays or data entry errors.

💡 Recommendations
Optimize schedules for high-demand days (Fridays & Mondays).
Review ferry pricing and utilization.
Investigate long-duration trips for route delays or inconsistencies.
Maintain continuous data quality checks.

⚙️ Tools Used
Python Libraries: pandas, numpy, seaborn, matplotlib
Environment: Jupyter Notebook
Visualization Tools: Matplotlib & Seaborn

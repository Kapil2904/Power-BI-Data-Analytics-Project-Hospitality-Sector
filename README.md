# Power BI Data Analytics Project Hospitality Sector
### Dashboard Link :

## Project Overview

This project is a Data Analytics Dashboard for the Hospitality Sector, specifically analyzing OYO Rooms data using Power BI. The aim is to extract meaningful insights from raw hotel data and visualize key performance indicators (KPIs) to support decision-making in the hospitality industry. By leveraging Power Query for data cleaning, DAX for calculations, and Power BI for visualization, this dashboard provides a clear and interactive view of hotel operations and revenue trends.

## Objectives 

The primary goal of this project is to:
- Analyze and visualize key hospitality metrics to assess hotel performance.
- Develop a dynamic Power BI dashboard that enables stakeholders to monitor room availability, revenue, and bookings efficiently.
-  Provide actionable insights to help hoteliers optimize pricing, occupancy, and revenue management strategies.

## Project Structure

1. **Data Cleaning & Transformation**:
- Raw data was imported and transformed using Power Query in Power BI.
- Applied data cleaning techniques such as handling missing values, correcting inconsistent formats, and standardizing data structures.
- Used M language and Power Query transformations to filter, merge, and shape the data for analysis.
- Ensured the final dataset was structured efficiently for KPI calculations and visualization.

2. **KPI Development**:
I calculated key hospitality industry metrics using DAX in Power BI to help analyze business performance. These KPIs provide insights into revenue, occupancy, cancellations, and booking trends.

🔹 Revenue & Pricing Metrics:

- ADR (Average Daily Rate): Measures the average revenue earned per occupied room.
- RevPAR (Revenue Per Available Room): A key metric to assess hotel performance by considering both occupancy and room rates.
- Revenue: Total income generated from room bookings.
- Realisation %: Revenue realization compared to expected revenue.
  
🔹 Booking & Occupancy Metrics:

- DBRN (Daily Booked Room Nights): The total number of rooms booked per day.
- DSRN (Daily Sellable Room Nights): The number of rooms available for booking each day.
- DURN (Daily Utilized Room Nights): The number of rooms actually occupied per day.
- Total Bookings: The total number of rooms booked.
- Total Successful Bookings: The number of bookings that resulted in a stay.
- Total Capacity: The total available rooms in the hotel.
- Occupancy %: The percentage of available rooms that are occupied.
  
🔹 Booking Performance & Customer Behavior:

- Booking % by Platform: The share of bookings made through different platforms (e.g., direct, OTA, corporate).
- Booking % by Room Class: The distribution of bookings across different room types.
- Cancellation %: The percentage of bookings that were canceled.
- Total Canceled Bookings: The number of bookings that were canceled.
- No Show Rate %: The percentage of guests who booked but did not show up.
- Total No Show Bookings: The total number of no-show reservations.
- Total Checked Out: The number of guests who successfully completed their stay.

3. **Dashboard Overview**:
This Power BI Dashboard provides a comprehensive analysis of OYO Rooms data, highlighting key performance metrics and trends in the hospitality industry. The dashboard is designed to help stakeholders make data-driven decisions by visualizing revenue, occupancy, bookings, and cancellations.
![Image](https://github.com/user-attachments/assets/b94760e7-72cc-4361-bbaf-f0b7fa0ee01b)


1️⃣ KPI Cards (Top Section)
The KPI cards display essential business metrics at a glance:

Revenue: Total revenue generated (1.69bn).
RevPAR (Revenue Per Available Room): Shows revenue per available room (7337).
DSRN (Daily Sellable Room Nights): Number of rooms available for booking (2.53K).
Occupancy %: Percentage of available rooms occupied (57.8%).
ADR (Average Daily Rate): Revenue per occupied room (12.7K).
Realisation %: Percentage of revenue realization (70.1%).
These KPIs help monitor hotel performance instantly.

2️⃣ Slicers & Filters (Top Left Corner)
Filter by City: Allows users to select a specific city and analyze its performance.
Filter by Room Type: Enables filtering based on different room categories.
Filter by Date Range: Users can adjust the date range to view trends over specific time periods.
These interactive filters help focus on relevant data for better decision-making.

3️⃣ Revenue Breakdown (Pie Chart - Top Right)
Shows Revenue % by Room Category (Luxury vs. Business).
Helps understand which room categories generate the most revenue.

4️⃣ Trend Analysis (Line Chart - Top Right)
Tracks key metrics such as ADR, RevPAR, and Occupancy % over weeks (W19 - W31).
Helps identify seasonal trends and fluctuations in hotel performance.
Useful for forecasting and strategic planning.

5️⃣ Performance by Day Type (Table - Middle Left)
Weekday vs. Weekend Analysis: Compares RevPAR, ADR, Occupancy %, and Realisation % between weekdays and weekends.
Helps hoteliers adjust pricing strategies based on demand fluctuations.

6️⃣ Booking & Revenue Insights (Bottom Section - Table & Bar Chart)
Detailed Property Performance Table:
Displays Revenue, RevPAR, Occupancy %, ADR, DBRN, DSRN, DURN, Cancellation %, and Average Rating for each hotel property.
Helps identify top-performing and underperforming properties.

Realisation % vs. ADR by Booking Platform (Bar & Line Chart - Bottom Left)
Compares realisation % and ADR across different booking platforms.
Helps identify the most profitable platforms.

- Insights & Business Impact

Revenue and occupancy trends enable better pricing strategies.
Cancellation & no-show rates help in improving customer retention.
Platform-wise booking analysis helps optimize marketing spend.
Room category performance provides insights into demand and pricing adjustments.

## Findings 

 Here are the key takeaways based on the data visualization:

1️⃣ Revenue & Pricing Insights
- Total Revenue is 1.69bn, with a RevPAR of 7337 and an ADR of 12.7K.
-  Weekends generate higher revenue & occupancy rates compared to weekdays.
-   he Revenue Realisation % is 70.1%, indicating that a portion of the potential revenue is lost due to cancellations or no-shows.

🔍 Business Impact:
- Hoteliers should focus on maximizing weekend pricing strategies and introducing dynamic pricing to increase weekday occupancy.
- Improving guest experience and incentives can help increase realisation %.

2️⃣ Occupancy & Room Performance
- Overall Occupancy Rate is 57.8%, showing room for improvement.
- Luxury rooms contribute significantly to revenue, but business rooms have a higher occupancy rate.
- DSRN (Daily Sellable Room Nights) is 2.53K, meaning a large portion of rooms remain unsold.

🔍 Business Impact:
- Targeted marketing campaigns can be used to increase bookings for underperforming room types.
- Hotels should consider offering discounts on weekdays to boost occupancy rates.

3️⃣ Booking Trends & Platform Analysis
- Platform-wise analysis shows varying levels of ADR and realisation %.
- Direct bookings tend to have higher ADR, while third-party platforms contribute significantly to total bookings but at a lower revenue per room.
- Cancellations & no-show rates are high (~24.8%), impacting revenue.

🔍 Business Impact:
- Encourage direct bookings by offering exclusive discounts or loyalty programs.
- Reduce cancellations & no-shows through prepaid bookings, flexible rescheduling, and better customer communication.

4️⃣ Property-Wise Performance
- Some properties in Delhi and Mumbai generate higher revenue, but occupancy rates are not uniform across cities.
- Cancellation rates vary significantly, with some properties facing over 25% cancellations.

🔍 Business Impact:
- Properties with low occupancy but high cancellations should improve guest policies and customer engagement.
- Regional marketing efforts can be optimized based on location-based demand trends.

💡 Final Recommendations
- Optimize weekday pricing & promotions to balance occupancy levels.
- Encourage direct bookings and reduce reliance on third-party platforms.
- Improve cancellation & no-show policies to enhance revenue realization.
- Focus on high-performing locations while improving low-performing properties.

## Conclusion   

This project provided a **comprehensive learning experience** in **data analytics within the hospitality domain**, using **Power BI** to uncover valuable insights from **OYO Rooms data**. Through this analysis, I:  

- **Gained a deep understanding of the hospitality industry**, including key metrics like **RevPAR, ADR, Occupancy %, and Booking Trends**, which are crucial for hotel performance evaluation.
-  **Mastered data analysis techniques**, such as **data cleaning in Power Query**, **DAX calculations**, and **building interactive Power BI dashboards** to support decision-making.
-  **Experienced firsthand the power of data** in solving real-world business challenges, from optimizing pricing strategies to reducing cancellations and improving revenue realization.  

This project reinforced the **importance of data-driven decision-making** in any industry and strengthened my skills in **data visualization, business intelligence, and analytics**. 



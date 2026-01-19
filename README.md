# Uber-Ride-Analytics-Dashboard
Analyzed Uber ride booking data using Excel and Power BI to monitor operational performance, booking trends, revenue, vehicle contribution, cancellations, ratings, and location-based insights through data modeling, KPI tracking, and interactive dashboards.

# Project Objective
To analyze Uber ride data and uncover insights related to:
- Booking performance (completed, cancelled, incomplete)
- Revenue trends (monthly & quarterly)
- Vehicle-wise contribution
- Customer and driver behavior
- Location-based demand and distance analysis
- Ratings and service quality metrics

# Key Business Insights
- Completed bookings significantly outweigh lost bookings, indicating strong service efficiency
- Auto and Go Mini generate the highest revenue among vehicle types
- Certain pickup and drop locations consistently dominate booking volume
- Customer cancellations are higher than driver cancellations
- Average driver rating remains above 4, reflecting good service quality
- Revenue and bookings show seasonal variation across months and quarters

# Tools & Technologies
- Microsoft Excel
- Power BI
- Power Query
- DAX

# Dataset Overview
The dataset contains Uber ride booking records with operational, financial, and customer-related details.
- Rows: 150,001
- Columns: 8

# Key Columns
- Booking_ID
- Booking_Status
- Vehicle_Type
- Pickup_Location
- Drop_Location
- Booking_Value
- Ride_Distance
- Customer_Rating
- Driver_Rating
- Payment_Method
- Date

# Data Preprocessing
The dataset was preprocessed by:
- Removing irrelevant and blank columns
- Handling missing and incomplete records
- Standardizing booking status categories
- Creating calculated columns and measures using DAX
- Mapping vehicle types and booking status with custom icons

# Project Workflow
🔹 Step 1: Data Loading
Imported Excel dataset into Power BI
Verified schema and row consistency

🔹 Step 2: Data Cleaning & Transformation
Performed using Power Query:
- Null value handling
- Data type corrections
- Date hierarchy creation (Month & Quarter)
- Vehicle type and booking status mapping

🔹 Step 3: KPI & Metrics Development
Created KPIs for:
- Completed Bookings
- Lost Bookings
- Total Revenue
- Total Distance
- Average Ride Distance
- Average Customer Rating
- Average Driver Rating

🔹 Step 4: Exploratory Data Analysis
Analyzed:
- Monthly & quarterly booking trends
- Revenue contribution by vehicle type
- Cancellation reasons (customer vs driver)
- Pickup and drop location performance
- Vehicle-wise distance contribution

🔹 Step 5: Dashboard & Visualization
Created interactive Power BI dashboards using:
- KPI cards
- Line charts (monthly & quarterly trends)
- Bar charts (vehicle and revenue analysis)
- Tables for detailed ride data
- Icons and images for vehicle and booking status
- Filters with hide/show panel for better spacing
  
# Analytical Findings
- Auto vehicles contribute the highest booking volume
- Go Mini and Sedan show strong revenue performance
- Certain locations consistently dominate pickup and drop demand
- Revenue is driven by a limited set of vehicle categories
- High average driver ratings indicate reliable service quality

# Conclusion
The Uber Ride Analytics Dashboard provides a comprehensive view of operational efficiency, revenue performance, vehicle contribution, and customer behavior. Insights from this analysis help optimize fleet utilization, improve service quality, and support data-driven decision-making for business growth.

# Business Use Cases
These insights can be used to:
- Optimize vehicle deployment by demand
- Improve customer retention by reducing cancellations
- Focus revenue strategies on high-performing vehicle types
- Enhance service quality using rating analysis
- Plan operations based on location demand trends

# Contact
Email: Samikshadhawale166@gmail.com

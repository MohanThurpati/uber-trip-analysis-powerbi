# Uber Trip Analysis Dashboard | Power BI

## Project Overview

The Uber Trip Analysis Dashboard is an interactive Power BI solution developed to analyze ride bookings, revenue, trip distance, trip duration, vehicle performance, payment methods, and pickup/drop-off trends. The dashboard transforms raw trip data into meaningful business insights through interactive visualizations, enabling stakeholders to monitor operational performance and support data-driven decision-making.

---
## Business Problem

Uber generates a large volume of trip data every day, making it challenging for business stakeholders to monitor booking trends, revenue performance, vehicle utilization, customer travel behavior, and location demand.

The objective of this project is to develop an interactive Power BI dashboard that provides a centralized view of key operational metrics, enabling business users to identify trends, compare performance across multiple dimensions, and support strategic decision-making.

---
## Dataset

- Industry: Ride Sharing / Transportation
- Source: Uber Trip Dataset
- File Format: Microsoft Excel (.xlsx)
- Total Records: 103,728 Trips

### Key Columns

- Trip ID
- Pickup Time
- Drop Off Time
- Passenger Count
- Trip Distance
- Pickup Location
- Drop-off Location
- Fare Amount
- Surge Fee
- Vehicle Type
- Payment Type
---
##  Data Modeling

A star-schema data model was implemented by connecting the Uber Trip Details fact table with Calendar and Location dimension tables, enabling efficient filtering and accurate business reporting.

## Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- Interactive Slicers
- KPI Cards
- Drill-through Navigation
- Data Visualization

---
## Project Methodology

The project was completed using the following analytical workflow:

1. Data Collection
2. Data Cleaning
3. Data Transformation using Power Query
4. Data Modeling
5. DAX Measure Creation
6. KPI Development
7. Interactive Dashboard Design
8. Business Insight Generation
9. Business Recommendations

## Dashboard Preview

The report consists of three interactive pages designed to provide a comprehensive view of Uber's operational performance.

### Page 1 – Overview Analysis
Provides an executive summary of bookings, revenue, trip distance, payment methods, vehicle performance, and location analysis.
![Overview Dashboard](dashboard-overview.png)

### Page 2 – Time Analysis
Analyzes booking patterns across different hours of the day and days of the week, helping identify peak demand periods.
![Time Analysis Dashboard](dashboard-time-analysis.png)

### Page 3 – Trip Details
Displays detailed trip-level information for operational analysis and record exploration.
![Trip Details Dashboard](dashboard-trip-details.png)

----
## Key Performance Indicators (KPIs)

| KPI | Value |
|------|------:|
| Total Bookings | 103.7K |
| Total Booking Value | $1.6M |
| Average Booking Value | $15.0 |
| Total Trip Distance | 349K Miles |
| Average Trip Distance | 3 Miles |
| Average Trip Time | 16 Minutes |

---
## Dashboard Features

- Executive KPI Dashboard
- Interactive Date Filtering
- Vehicle Type Analysis
- Payment Method Analysis
- Booking Trend Analysis
- Time-based Analysis
- Pickup and Drop-off Location Analysis
- Heatmap Visualization
- Detailed Trip Table
- Interactive Navigation Buttons

---
## Key Insights

- The dashboard analyzes more than 103K completed Uber trips.
- UberX recorded the highest number of bookings among all vehicle categories.
- Uber Pay is the most frequently used payment method.
- Day trips contribute significantly more bookings than night trips.
- Booking demand varies throughout the day, with identifiable peak operating hours.
- Pickup and drop-off demand is concentrated around specific high-traffic locations.
- Average booking value remains approximately $15 per trip.
- The average trip duration is 16 minutes with an average travel distance of 3 miles.

---
## Business Recommendations

- Increase vehicle availability during peak demand hours.
- Allocate additional drivers to high-demand pickup locations.
- Optimize fleet distribution based on booking trends.
- Improve promotional strategies for underutilized vehicle categories.
- Monitor payment preferences to enhance customer convenience.
- Use trip demand analysis to improve driver scheduling and operational efficiency.

---
## Skills Demonstrated

- Data Cleaning
- Data Transformation
- Data Modeling
- DAX
- Power Query
- KPI Development
- Dashboard Design
- Interactive Reporting
- Business Intelligence
- Data Visualization
- Business Analysis
- Microsoft Power BI

---
## Project Structure

```text
Uber-Trip-Analysis-Dashboard/

│── README.md
│── Images/
      Overview Dashboard.png
      Time Analysis.png
      Details.png
│── Dataset/
       Location table.xlsx
│── Dashboard/
      Uber Trip Analysis.pbix
│── Dataset/
      Uber Trip Details.xlsx

```
## How to Use

1. Download the repository.
2. Open the `.pbix` file using Microsoft Power BI Desktop.
3. Refresh the dataset if required.
4. Navigate between the report pages using the built-in navigation buttons.
5. Apply filters such as Date, Vehicle, City, and Payment Type to perform interactive analysis.

---
## Author

**Mohan Thurpati**

Aspiring Data Analyst

### Skills

- Excel
- SQL
- Power BI
- Python

### Connect With Me

- LinkedIn: https://www.linkedin.com/in/mohanthurpati
- Portfolio: https://mohanthurpati.framer.website

---
⭐ If you found this project interesting, feel free to explore the repository and connect with me on LinkedIn.

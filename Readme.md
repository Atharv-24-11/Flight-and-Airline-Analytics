# ✈️ Flight & Airline Analytics Dashboard \| Power BI

## 📊 Project Overview

This project is an interactive **Flight & Airline Analytics Dashboard**
developed using **Microsoft Power BI**. The dashboard transforms flight,
airline, route, fare, and travel-related data into meaningful visual
insights through interactive KPIs, charts, slicers, and analytical
views.

The project is designed to explore flight operations, airline
performance, route patterns, ticket pricing, flight duration, revenue,
and travel characteristics in a single interactive reporting solution.

------------------------------------------------------------------------

## 🎯 Project Objectives

The main objective of this project is to:

-   Analyze flight activity across airlines, routes, and departure
    periods.
-   Understand ticket pricing patterns across different airlines and
    routes.
-   Compare airline performance using flight volume, revenue, pricing,
    and duration.
-   Identify frequently occurring routes and route types.
-   Analyze the relationship between ticket price and flight duration.
-   Study changes in flight activity over time.
-   Present complex flight data through an interactive and
    easy-to-understand dashboard.

------------------------------------------------------------------------

## 📑 Dashboard Pages

### 1. Flight Analytics & Insights

This page provides a high-level overview of flight operations and
pricing.

**Key KPIs:** - Total Flights - Average Flight Duration - Average Ticket
Price - Maximum Ticket Price - Minimum Ticket Price

**Key Analysis:** - Flights by departure period - Flights by airline -
Flights by source and destination - Average ticket price by airline -
Interactive source and destination filtering

------------------------------------------------------------------------

### 2. Airline & Route Analysis

This page focuses on airline performance, routes, revenue, and pricing.

**Key KPIs:** - Total Airlines - Most Expensive Airline - Cheapest
Airline - Expensive Route - Cheapest Route

**Key Analysis:** - Average ticket price by source and destination -
Total revenue by airline - Top 10 routes by flight count - Average
flight duration by airline - Flights by route type - Route and
airline-level filtering

------------------------------------------------------------------------

### 3. Fare & Travel Insights

This page focuses on fare characteristics and travel patterns.

**Key KPIs:** - Price Range - Non-Stop Flight Percentage - Average
Ticket Price - Average Number of Stops

**Key Analysis:** - Flight trends by year - Price vs. flight duration -
Average ticket price by departure period - Average ticket price by route
type - Flights by additional travel information - Airline, route type,
price range, and departure-period filtering

------------------------------------------------------------------------

## 🔍 Key Business Questions

The dashboard helps answer questions such as:

-   Which airlines operate the highest number of flights?
-   How do ticket prices vary across airlines?
-   Which airlines generate higher total revenue?
-   Which routes have the highest flight activity?
-   Which routes are relatively expensive or inexpensive?
-   How does flight duration vary between airlines?
-   How does ticket price relate to flight duration?
-   Which route types have higher average ticket prices?
-   How does flight activity change over the years?
-   What percentage of flights are non-stop?
-   How do departure periods affect ticket prices?
-   What additional travel information is associated with flight
    records?

------------------------------------------------------------------------

## 🛠️ Tools & Technologies

  -----------------------------------------------------------------------
  Tool / Skill                        Usage
  ----------------------------------- -----------------------------------
  **Microsoft Power BI**              Dashboard development and
                                      visualization

  **Power Query**                     Data cleaning and transformation

  **DAX**                             Measures, KPIs, and analytical
                                      calculations

  **Data Modelling**                  Structuring data and creating
                                      relationships

  **Data Visualization**              Charts, cards, tables, slicers, and
                                      interactive visuals

  **Business Intelligence**           Converting data into analytical
                                      insights
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## 📊 Dashboard Features

-   Interactive slicers and filters
-   KPI cards
-   Airline-wise analysis
-   Route-wise analysis
-   Source and destination analysis
-   Revenue analysis
-   Ticket price analysis
-   Flight duration analysis
-   Year-wise trend analysis
-   Route-type analysis
-   Interactive visual cross-filtering
-   Top route analysis
-   Price vs. duration analysis

------------------------------------------------------------------------

## 🧮 Data Analysis & DAX

DAX was used to create calculated measures and KPIs required for the
dashboard, including calculations related to:

-   Total flights
-   Average ticket price
-   Average flight duration
-   Minimum and maximum ticket price
-   Total revenue
-   Average stops
-   Non-stop flight percentage
-   Airline and route comparisons
-   Year-wise flight analysis

------------------------------------------------------------------------

## 📁 Suggested Repository Structure

``` text
Flight-Airline-Analytics-PowerBI/
│
├── README.md
│
├── PowerBI/
│   └── Flight_Analytics_Dashboard.pbix
│
├── Dashboard/
│   ├── Flight_Analytics and Insights.png
│   ├── Airline and Route Analysis.png
│   └── Fare and Travel Insights.png
│
└── Dataset/
    └── flight.csv
```


------------------------------------------------------------------------

## 🖼️ Dashboard Preview

### Flight Analytics & Insights

![Flight Analytics & Insights](Airline Analytics and Insights\Dashboard images\Flight Analytics.png")

### Airline & Route Analysis

![Airline & Route Analysis](Airline Analytics and Insights\Dashboard images\Airline and route.png")

### Fare & Travel Insights

![Fare & Travel Insights](Airline Analytics and Insights\Dashboard images\Fare and Travel.png")

------------------------------------------------------------------------

## 🚀 Project Workflow

``` text
Raw Flight Data
      ↓
Data Cleaning & Transformation
      ↓
Data Modelling
      ↓
DAX Measures & KPIs
      ↓
Interactive Visualizations
      ↓
Flight & Airline Insights
```

------------------------------------------------------------------------

## 📌 Key Skills Demonstrated

-   Data Cleaning
-   Data Transformation
-   Data Modelling
-   DAX
-   Power Query
-   KPI Development
-   Data Visualization
-   Interactive Dashboard Development
-   Business Intelligence
-   Analytical Thinking
-   Data Storytelling

------------------------------------------------------------------------

## Suggested cleaning:

-   No major cleaning basic cleaning Required.
-   Duration col is in hr covert it into mins also while keeping hour col as it is.
-   Based on Total_stop col create a new column Route type(0='non stop',1='1 stop',>1='Multiple stops')
-   Based on dep_time col craete a new column Departure period(Early morning,morning,Evening,Afternoon and night)



## Modelling:

-  create a calculated calendar column using date of journey column and build relationship one to many(calendar to date of journey), This will help in analysis.


## Measures needed:

-   Avg_flight_duration(hr)
-   Avg_flight_duration(min)
-   Avg_stops
-   Avg_Ticket_price
-   Cheapest_route
-   cheapest Airline
-   Expensive_route
-   Max_Ticket_price
-   Min_Ticket_price
-   non stop flight
-   non stop flight %
-   Price range
-   Total Airlines
-   Total flights 
-   Total routes


## 👨‍💻 Author

**Atharv Dhande**

Data Analyst \| Power BI \| SQL \| Python \| Data Analytics

------------------------------------------------------------------------

## 📄 License

This project is created for **learning, portfolio, and educational
purposes**.

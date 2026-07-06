# Airline Operations Dashboard

## About

The Airline Operations Dashboard is an interactive Power BI project designed to evaluate airline operational performance using historical flight data. It provides a centralized view of flight activity, cancellations, delays, and airline performance, enabling operational trends to be monitored and performance bottlenecks to be identified through an interactive dashboard.

Designed with a business-first approach, the dashboard follows a logical analytical flow—from evaluating overall operational health to identifying delay patterns and the airlines experiencing the highest departure delays.

---

## Business Objective

Airline operations generate millions of operational records, making it difficult to extract meaningful insights from raw data alone. This project transforms flight data into an interactive dashboard that helps answer key business questions:

- What is the overall operational health of the airline network?
- How does flight activity change throughout the year?
- Which airlines operate the highest number of flights?
- What are the primary contributors to operational delays?
- Which airlines experience the highest departure delays?

---

## Key Performance Indicators

- Total Flights
- Cancelled Flights
- Cancellation Rate
- Average Departure Delay
- Average Arrival Delay

---

## Dashboard Features

- Operational performance monitoring
- Monthly flight trend analysis
- Airline traffic comparison
- Delay cause analysis
- Departure delay comparison

---

## Key Insights

- **Late Aircraft (37.93%)** and **Carrier-related (36.49%)** delays together account for over **74%** of total operational delay minutes, indicating that operational factors have a substantially greater impact on delays than external factors.
- **Southwest Airlines Co.** handled the highest flight volume with **95,626 flights**, whereas **JetBlue Airways** recorded the highest average departure delay at **18.3 minutes**.
- Flight activity exhibits clear seasonal fluctuations, reflecting varying operational demand throughout the year and emphasizing the importance of capacity planning.
- **Security-related delays contributed only 0.22%** of total delay minutes, compared with **19.61%** for National Air System (NAS) delays and **5.74%** for Weather delays, indicating a minimal impact on overall airline operations.

---

## Tools & Technologies

- Power BI
- Power Query
- DAX

---

## Dataset


This project uses a subset of the **U.S. Department of Transportation (DOT) Bureau of Transportation Statistics (BTS) On-Time Performance** dataset, covering flight operations from **August 2019 to August 2023**.

The analysis is based on **500,000 flight records** selected from a significantly larger dataset. It includes airline information, flight schedules, departure and arrival performance, cancellations, taxi operations, flight distance, and operational delay categories.

The dataset was consolidated from monthly DOT On-Time Performance records and further processed through data cleaning, transformation, and variable standardization to prepare it for analysis.

**Source:** U.S. Department of Transportation (DOT), Bureau of Transportation Statistics (BTS) – On-Time Performance Reporting Carrier Data.

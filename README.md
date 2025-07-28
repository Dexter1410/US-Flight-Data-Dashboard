# US Airline Performance & Flight Delay Analysis (2015)

## Project Overview

This project provides a comprehensive analysis of the performance of US domestic commercial airlines throughout 2015. Using a dataset of over 800,000 flights, this analysis investigates trends in flight volume, departure delays, and cancellations. The ultimate goal is to present key observations and actionable insights through an interactive Power BI dashboard, highlighting the factors that impact airline reliability and operational efficiency.

## Dataset

The [dataset](https://docs.google.com/spreadsheets/d/1kll43rUiEwkIsowC1xoFVmZ_H-jLs5r9/edit?usp=sharing&ouid=108405867980293701725&rtpof=true&sd=true) contains records for more than 800,000 commercial airline flights in the US for the year 2015. Each record represents a single flight and includes detailed information such as:
*   Airline Name and Flight Number
*   Origin & Destination Airports
*   Flight Distance
*   Scheduled vs. Actual Departure and Arrival Times
*   Delay & Cancellation Data

## Key Analytical Questions

The analysis for this project seeks to answer the following key questions:

1.  How does the overall flight volume vary on a monthly basis?
2.  What percentage of flights experienced a departure delay, and what was the average duration of these delays?
3.  How does the percentage of delayed flights fluctuate throughout the year?
4.  What was the total number of cancelled flights in 2015, and what were the primary drivers for cancellation (e.g., weather, airline-related issues)?
5.  Which airlines were the most and least reliable in terms of on-time departures?

## Key Insights & Findings

The analysis of the 2015 US flight data yielded several critical insights:

*   **Stable Monthly Flight Volume**: Total flight volumes remained remarkably consistent throughout the year, predominantly hovering around the **70,000 mark**. The lowest volume was recorded in February at 68,461 flights, and the highest at 70,867, with a median of 70,414. This indicates that monthly volume variation is not a primary driver of widespread delays, pointing instead to deeper operational factors[1].

*   **Significant Departure Delays**: A substantial **39.25%** of all flights experienced a departure delay. The average duration for these delays was **33.47 minutes**, highlighting a major area for operational improvement and a significant impact on passenger experience[1].

*   **Minor Seasonal Fluctuation in Delays**: While delay rates showed some variation, they remained consistently high. They peaked in February at **39.79%** and reached their lowest point in January at **38.95%**. This suggests that despite minor seasonal shifts, the underlying causes of delays are pervasive throughout the year[1].

*   **Prevalence of Cancellations, Dominated by Weather**: In 2015, a total of **33,000 flights** were canceled. The majority of these cancellations were attributed to "Reason B" (likely weather-related), accounting for **23,000** flights. "Reason A" (6,000 cancellations), "Reason C" (4,000 cancellations), and "Reason D" (3,000 cancellations) followed, clearly indicating weather as the predominant factor for flight disruptions[1].

*   **Disparities in Airline Reliability**:
    *   **Most Reliable Airline**: **Alaska Airlines Inc.** demonstrated the highest on-time departure rate among all airlines and recorded the second-lowest rate of cancellations, making it the most reliable airline in 2015[1].
    *   **Least Reliable (On-Time Departure)**: **United Airlines Inc.** had the lowest on-time departure rate, indicating significant challenges in maintaining scheduled departures[1].
    *   **Most Unreliable (Cancellations)**: **American Eagle Airlines Inc.** exhibited the highest percentage of total flights canceled, highlighting a critical area for operational review in managing disruptions[1].

## Strategic Recommendations

Based on these findings, the following strategic actions are recommended:

1.  **Focus on Operational Root Causes**: Airlines should investigate internal operational bottlenecks (e.g., ground handling, crew scheduling) rather than focusing on monthly volume as the cause of delays[1].
2.  **Proactive Resource Planning**: During periods with historically higher delay rates, such as February, airlines should proactively allocate additional resources and implement contingency plans to mitigate disruptions[1].
3.  **Enhance Weather-Related Protocols**: Given that weather is the primary driver of cancellations, airlines should invest in enhanced weather forecasting models and more flexible scheduling to reduce its impact[1].
4.  **Benchmark Against Industry Leaders**: Airlines with lower performance metrics, like United Airlines and American Eagle Airlines, should analyze the operational practices of top performers like Alaska Airlines to identify best practices and drive internal improvements[1].

## Tools & Technologies

*   **Data Analysis & Visualization**: Power BI
*   **Project Documentation**: Microsoft Word

## How to View This Project

1.  [**Dashboard**](./Dashboard/Dashboard.md)
2.  [**Final Report**](./Final-Report/Final-Report.pdf)

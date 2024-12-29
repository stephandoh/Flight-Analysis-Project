# Flight Analysis Project

This project focuses on analyzing an airline dataset to derive valuable insights regarding flight status and air traffic patterns. The dataset includes data from multiple airlines, covering various airports, flight status (on-time, delayed, cancelled), and average delay times over a period of time. The goal is to perform in-depth analysis and visualize key trends that can help improve operational efficiency and provide better customer experiences for airlines.

## Objectives

- **Flight Status Analysis**
  - Evaluate the monthly flight status and analyze on-time, delayed, and cancelled flights.
  - Investigate the average delay time for each airline and month, focusing on patterns of delays.

- **Air Traffic Analysis**
  - Identify the best times to book a flight by analyzing air traffic data.
  - Determine peak hours when maximum flights are available and understand flight patterns throughout the week.

- **Actionable Insights**
  - Use the analysis to identify key days or times when delays are more likely, helping airlines improve their scheduling and resource allocation.
  - Provide actionable insights into when passengers can expect the best chances for on-time flights.

## Key Deliverables

- **Interactive Dashboards**
  - Create slicers for Month and Airline to filter data and present dynamic charts showcasing flight statuses by day of the week.

- **Flight Status Visualizations**
  - Display the number of on-time, delayed, and cancelled flights, along with average delay times, broken down by airline and month.

- **Air Traffic Trends**
  - Visualize the number of flights over time to identify peak flight periods and trends in delays.

## Business Value

This analysis allows airlines to make data-driven decisions about flight scheduling, improve operational efficiency, optimize resource allocation, and enhance customer satisfaction by minimizing delays during peak times. By understanding flight status trends, airlines can proactively address issues and ensure smoother operations.

<img width="821" alt="image" src="https://github.com/user-attachments/assets/e54d625e-a70d-44f7-a007-16f47ec9ee41" />

<img width="821" alt="image" src="https://github.com/user-attachments/assets/e93d804b-6832-4161-a501-354231bdc296" />

## Insights

- **Tuesday had the highest On-Time flights**, with a significant difference (18.73%) compared to Saturday, which had the lowest On-Time rate.
- Tuesday accounted for **15.07% of On-Time flights**.
- Flight status across all days showed variation, with On-Time flights ranging from 37,982 to 45,095, Flights Cancelled ranging from 1,448 to 2,112, and Flights Delayed ranging from 17,949 to 28,178.

### 2. Average Delay Time:
- The year 2009 had the highest total average delay (minutes) at 600,648, followed by 2010 at 583,667, and 2011 at 45,083.
- Delta Air Lines Inc. in 2010 contributed 7.64% of the total average delay time.
- The average delay per year ranged significantly:
  - 2009: 60,064.80 minutes
  - 2010: 58,366.70 minutes
  - 2011: 5,009.22 minutes

### 3. Air Traffic Trends:
- The number of flights showed a **261.45% increase** on Saturday, December 30, 1899, reaching 45,693 flights.
- A sharp decline in the number of flights was noted, dropping by 80.64% over 5 hours, from 36,040 flights to 8,653 flights on the same Saturday.

## Challenges and Solutions

While loading the dataset into Power BI, I encountered a data formatting issue in the 'Departure Hour' column.

<img width="1163" alt="airline data loading error " src="https://github.com/user-attachments/assets/b34dc68a-2692-4b40-8c22-d9dda5935d5d" />

### Issue:
- The 'Departure Hour' values were incorrectly formatted (e.g., "0:6:00" instead of "00:06").

<img width="1254" alt="departure hour" src="https://github.com/user-attachments/assets/beea4ca0-99a6-461a-ab86-647af1a7ec28" />

### Solution:
- Fixed the 'Departure Hour' column in Excel by replacing incorrect time values.
- Split the 'Departure Hour' column into two new columns: "Departure Time" and "Arrival Hour."
- Re-uploaded the corrected dataset into Power BI, ensuring the correct time format was applied.

<img width="1118" alt="table" src="https://github.com/user-attachments/assets/c68f2153-f995-4597-ad1d-4a672eceb9dc" />

<img width="1250" alt="two columns" src="https://github.com/user-attachments/assets/017f088d-dee4-4188-81e9-9e1de237581e" />

<img width="1039" alt="final cleaned data" src="https://github.com/user-attachments/assets/25413bf2-b23a-46e1-a939-98b03e038bf8" />

## Key Recommendations

1. **Operations Manager** should improve Saturday on-time performance by allocating more staff and backup crews.
2. **Flight Operations Manager** should increase gates and ground crew during peak hours to reduce congestion.
3. **Customer Service Manager** should notify passengers in advance about delays with real-time alerts.
4. **Airline Scheduling Manager** should hire seasonal staff and ensure equipment maintenance ahead of high-delay months.
5. **Airline Coordination Manager** should coordinate schedules with partner airlines to avoid hub congestion.

## Conclusion

This analysis provides valuable insights for airlines to optimize flight schedules, reduce delays, and enhance customer satisfaction. By addressing the identified issues and following the recommended actions, airlines can improve their operational efficiency and offer a better experience to passengers.

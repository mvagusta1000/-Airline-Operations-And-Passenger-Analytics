# -Airline-Operations-And-Passenger-Analytics

✈️ Airline Data Analysis
📌 Overview

This project analyzes airline passenger and flight data to uncover insights about age groups, flight statuses, departure trends, and cancellations/delays over time.
The analysis is performed using Python (Pandas, Matplotlib, Seaborn) in a Jupyter Notebook.

📊 Analysis Performed

Passenger Demographics

Grouped passengers by age group.

Compared distributions of flight statuses (On Time, Delayed, Cancelled) for each age group.

Visualized results with grouped bar charts.

Flight Status by Departure Date

Converted departure_date into day names (Monday, Tuesday, etc.).

Counted the number of flights per weekday.

Identified the busiest days for flights.

Monthly Flight Status Trends

Resampled data on a monthly basis using resample('M').

Plotted line charts showing how cancellations, delays, and on-time flights varied over time.

Highlighted seasonal trends.

📈 Visualizations

Grouped Bar Charts:
Compare flight statuses across passenger age groups and genders.

Weekday Flight Counts:
Distribution of departures across weekdays.

Monthly Trends:
Line charts showing trends in cancellations, delays, and on-time performance.
🚀 How to Run

Clone the repository and open the notebook:

git clone <your-repo-url>
cd airline-data-analysis
jupyter notebook "airline Data anlysis.ipynb"


Run the cells step by step to:

Clean and preprocess the data.

Perform exploratory data analysis (EDA).

Generate visualizations.

📌 Insights You Can Derive

Which age group faces the most cancellations or delays.

Which days of the week are busiest for flights.

How flight status trends change month to month (seasonal effects, peak travel times

This project analyses booking and cancellation data from OLA rides to understand patterns, trends, and potential insights that can help in operational decision-making. Using historical ride bookings, cancellations, time data, etc., the goal is to extract meaningful metrics and visualisations to inform policies, improve service, reduce cancellations, and enhance user experience.

This project analyzes the following:
•	Understand how and when cancellations happen: time of day, location, day of week etc.
•	Identify inefficiencies or patterns that might reduce revenue or customer satisfaction.
•	Provide actionable insights for stakeholders (operations team, marketing, product) to make data-driven decisions.
•	Create dashboard visualisations so that non-technical stakeholders can quickly grasp key metrics.


Data Description
What data is used:
•	Bookings.csv: Contains all the booking records, with details such as booking time, pick-up location, drop-off, fare, etc. (You might list the main columns: date/time, status, cancellation, etc.)
•	Booking-Cancellation Dashboard (OLA Booking-Cancellation Data Dashboard.pbix): Power BI dashboard file illustrating the visual insight.
•	Other supporting documentation (e.g. the PDF OLA-Data-Analyst-Project.pdf) with analysis and conclusions.
•	Also mention: number of records, time range, any data cleaning you did (removing missing values, fixing anomalies etc.)


Objectives / Research Questions
•	Here are some of the specific questions this project aims to answer:
•	What is the cancellation rate overall? How does it vary by time of day, day of week, or by location?
•	Are there certain geographies or times when cancellations spike?
•	What factors are most correlated with cancellations (e.g., waiting time, distance, fare, type of ride)?
•	How does booking volume vary over time (hour-wise, daily, monthly)?
•	Can we find trends / seasonality in ride demand?
•	Recommendations: What can Ola do to reduce cancellations or improve booking fulfilment?


Methodology
•	Initial data exploration and cleaning: checking for missing values, outliers, data types, etc.
•	Aggregation and grouping by features like date, time, location.
•	Statistical summary metrics (means, medians, distribution).
•	Visualization (charts, graphs): time series, heatmaps, bar charts etc.
•	Dashboard in Power BI to present findings.


Tools & Technologies
Programming / data tools: (if you used Python / R / SQL etc., mention libraries)
Visualization / Dashboard: Power BI (since .pbix file is included)
Data storage / processing: mention if any special steps required.

Key Findings / Insights
•	(Fill real content here; examples you might include:)
•	Cancellation rates are highest during peak traffic hours (e.g. 5–7 pm).
•	Certain pickup locations (or zones) have consistently higher cancellations.
•	Bookings just before ride types like “X” show lower fulfilment reliability.
•	Demand surges on weekends, but also higher cancellation proportion.
•	Recommendations: e.g. improve matching algorithm, provide better incentives for drivers during low supply times, send reminders to riders.

Dashboard / Visualisations
•	The OLA Booking-Cancellation Data Dashboard (.pbix file) shows interactive visuals: time series of bookings vs cancellations, location heatmaps, trends by day of week, etc.
•	Screenshots of the dashboard (if possible) to include.
•	Description of what each visual demonstrates.

How to Run / Reproduce
•	Include instructions so others can reproduce your work:
•	Download the repository.
•	Load the Bookings.csv in your analysis environment.
•	If using Python / R / etc., install dependencies (list them).
•	Run data cleaning scripts (if any).
•	Open the Power BI .pbix file to view dashboard.
•	Optionally, launch any notebooks / scripts you used.
•	You might also include sample code snippets or instructions on how to set up the environment.


Licence: State the licence under which you are releasing this project (e.g. MIT, Apache 2.0 etc.)

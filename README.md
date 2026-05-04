# Cyclistic_User_Trends
Uncovering ridership patterns to drive membership growth for Chicago’s leading bike-share service.

This is a great start. I have cleaned up the formatting and added your recent results while keeping the language grounded and direct.
Cyclistic_User_Trends

Uncovering ridership patterns to drive membership growth for Chicago’s leading bike-share service.
1. Ask

Business Task: Analyze how casual riders and annual members use bikes differently.

Goal: Design a data-backed strategy to convert casual riders into annual members.
2. Prepare

Data Source: 12 months of Cyclistic trip data.

Constraint: To protect privacy, no personal rider information (like credit card numbers) was used.
3. Process

    Tools: R (RStudio) and BigQuery.

    Scale: Successfully cleaned and merged 5,147,004 rows of data.

    Cleaning:

        Formatted timestamps into a usable date/time format.

        Removed duplicates and 29 rows with negative ride lengths.

        Handled missing values using na.omit() to ensure accurate results.

4. Analyze (The Findings)

I processed the data to find the "Big 3" differences between users:

    The "Saturday Peak": Casual riders are "Weekend Warriors." Their usage peaks on Saturdays, while annual members stay consistent throughout the work week.

    Duration Gap: Casual riders stay out twice as long. On average, they ride for ~25 minutes, compared to only ~12 minutes for members.

    The Intent: These patterns show that members use the bikes for commuting, while casual riders use them for leisure and weekend exploring.

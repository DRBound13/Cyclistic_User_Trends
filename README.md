# Cyclistic_User_Trends
Uncovering ridership patterns to drive membership growth for Chicago’s leading bike-share service.

## 1. Ask
**Business Task:** Analyze how casual riders and annual members use bikes differently.
**Goal:** Create a strategy to convert casual riders into members.

## 2. Prepare
**Data Source:** 12 months of Cyclistic trip data.
**Constraints:** No personal rider data is available.
## 3. Process
- **Tools:** R (RStudio)
- **Cleaning:** Merging 12 months of data, removing duplicates, and checking for missing values.
- **Environment:** RStudio Desktop (Posit)
- **Status:** Installing Tidyverse and initializing project directory.
- **Action:** Created `all_trips_v2` for analysis.
- **Status:** Data cleaning complete.
- Action: Identified 5,147,004 missing values.
- Action: Cleaned dataset using na.omit() to ensure analysis integrity.
- Status: Dataset is now verified and fully clean.
- **Action:** Merged 12 monthly CSV files into a single dataframe (`all_trips`).
- **Status:** Data ingestion complete; moving to data cleaning and inspection.
- **Action:** Converted `started_at` and `ended_at` columns to POSIXct (datetime) format.
- **Status:** Data formatting in progress.
- **Action:** Validated data; average ride length is 15.9 minutes.
- **Action:** Removed 29 rows with non-positive ride lengths.
- **Status:** Data cleaned; starting analysis.

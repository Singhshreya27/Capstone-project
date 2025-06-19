# Capstone-project
Capstone project focuses on analyzing and understanding patterns in aircraft crashes and air traffic passenger statistics. By integrating historical data on air crashes with passenger traffic data, the goal is to explore key trends and relationships, and prepare the data for predictive modeling.
Data Tyoes used:
1. **Numerical Data (Continuous or Discrete values):**
Used for performing mathematical operations, statistical analysis, correlation, regression, etc.
Examples:
Aboard (number of people aboard the aircraft)
Fatalities (number of fatalities in each crash)
Ground (number of people affected on ground)
Passenger Count (monthly passenger traffic)

2. **Categorical Data (Qualitative values):**
Used for grouping and classification.
Examples:
Operating Airline (name of the airline)
Location (city or country of crash)
Route (flight route)
Aircraft Type (model of aircraft)

3. **Date/Time Data:**
Used for time series analysis, trend identification, and merging datasets.
Examples:
Date (date of crash)
Year (extracted from Date column)

**Functions Used:**
**1. Handling Missing Data:**
Detecting missing values.
Filling missing values with:
Mean for numerical data.
Mode for categorical data.

**2. Data Transformation:**
Converting data types (e.g. converting Date column to date-time format).
Extracting year from date for analysis.

**3. Data Merging:**
Combining the two datasets based on a common field (Year).

**4. Exploratory Data Analysis (EDA):**
Descriptive statistics (mean, median, standard deviation).
Correlation analysis.
Grouping and aggregation.
Visualizations using plots and graphs.

**5. Scaling & Normalization:**
Standardizing numerical data for future predictive modeling.

**Observation from EDA**
**Correlation Heatmap:** Strong correlation between "Aboard" and "Fatalities." "Passenger Count" and "Adjusted Passenger Count," as well as "Activity Period" and "Year," are perfectly correlated. 
**Crashes Over Years:** Peaks in crashes observed around 1944 (likely WWII) and the late 1990s/early 2000s. 
**Top Crash Locations:** Amsterdam and Toronto have the most crashes, with several Alaskan locations also prominent. 
**Top Aircraft Types:** Douglas DC-3 is overwhelmingly the most involved aircraft type in crashes. 
**Top Airlines:** Air France, American Airlines, and KLM Royal Dutch Airlines have the highest crash counts. 
**Fatalities Distribution:** Most crashes result in few fatalities; highly fatal events are rare outliers. 
**Passenger Count vs. Fatalities:** General trend shows more fatalities with higher passenger counts, but with significant variation. 



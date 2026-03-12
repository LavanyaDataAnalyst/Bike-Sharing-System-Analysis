# 📊 Bike Sharing System Analysis
## ℹ️ Description:
* This project analyzes a Bike Sharing System dataset using Power BI to evaluate bike availability, station capacity, and service features across multiple cities.

## 📖 Table of Contents:
>* Project Overview
>* Data Source
>* Tools & Technologies
>* Data Cleaning & Preparation
>* Exploratory Data Analysis (EDA)
>* Key Insights
>* Recommendations
>* How to Use

## 📘Project Overview:
* The Power BI dashboard helps understand how efficiently the bike-sharing system operates by analyzing:
>Total bike stands, available bikes, and available bike stands
>City-wise distribution of bike stations
>Availability of banking and bonus facilities at stations
>Average bike and stand availability across cities
>Trends in bike availability over time

* The dashboard enables stakeholders to optimize bike allocation, improve station utilization, and enhance accessibility for users.

## 🗂 Data Source:
* The dataset contains information about bike sharing stations across multiple cities.

**Key fields include:**

>Station ID 
>Station Number
>Station Name
>Address
>Banking (Yes/No)
>Bonus (Yes/No)
>Status (Open/Closed)
>City
>Latitude & Longitude
>Bike Stands (Total capacity)
>Available Bike Stands
>Available Bikes
>Last Updated Date & Time
>Time Zone

* The network includes thousands of bike stands distributed across multiple cities.

## 🛠 Tools & Technologies:
* The following tools were used in the project:

**Excel**
>Data cleaning
>Sorting and filtering
>Pivot tables
>Basic analysis

**Power Query**
>Data transformation
>Data formatting and preparation

**Power BI**
>Data modeling
>Dashboard creation
>Visualization

**DAX (Data Analysis Expressions)**
>Creating measures
>Calculations and aggregated metrics

## 🧹Data Cleaning & Preparation

- Several steps were performed to ensure data quality and consistency:

**Data Cleaning**
- Renamed column headers for clarity.
- Corrected data types for columns.
- Replaced TRUE/FALSE with Yes/No in Banking and Bonus columns.
- Removed extra spaces using Trim and Clean functions.
- Fixed inconsistent values in Station Name and Address.

**Data Transformation**
- Created a Station ID by combining Station Number and City.
- Split Position field into Latitude and Longitude.
- Split Last Updated column into Date, Time, and Time Zone.
- Standardized text formatting (capitalized words).
- Split Address column using delimiters.

**Data Validation**
- Applied filters to identify missing values.
- Sorted records to verify data accuracy.

## 📊 Exploratory Data Analysis (EDA)

- Analyzed relationships between bike stands, available bikes, and available bike stands to understand station capacity and usage.
- Compared bike availability across different cities to identify cities with higher or lower bike usage.
- Evaluated the availability of banking and bonus facilities across bike stations.
- Evaluated the availability of banking and bonus facilities across bike stations.
- Conducted city-based analysis of bike stations to understand the distribution of bike-sharing networks.
- Visualized bike availability trends and station performance using Power BI charts, maps, and interactive dashboards.

![EDA Analysis](Images/EDA.png) 

>Figure: Comparison of bike availability and bike stand capacity across different cities and station categories.


## 🔍 Key Insights

Important findings from the analysis:

- Very large stations have the **highest bike and stand availability**.

- Bike availability decreases as station capacity becomes smaller.

- Low stand availability dominates (76.72%), showing **high bike usage**.

- High availability of stands is **very rare (1.68%)**.

- **Lyon and Toulouse** have the largest bike-sharing networks.

- Some cities like **Santander and Toyama** have very low bike availability.

- In most cities, available bike stands are higher than available bikes, meaning many bikes are currently in use.

- Many stations do not provide banking or bonus services, indicating limited premium features.

- Bike availability fluctuates over time depending on demand.

## 💡Recommendations

Based on the analysis, the following improvements can be suggested:

- Increase bike supply in high-demand stations with low availability.

- Expand station capacity in small stations to improve accessibility.

- Improve bike redistribution strategies to balance availability across cities.

- Add banking and bonus features to more stations to enhance user convenience.

- Monitor time-based demand trends for better operational planning.

- Focus on cities with low bike availability to improve service efficiency.

## ▶️ How to Use

- Users can interact with the dashboard using the following features:

**Slicers** – Filter data by Status, Banking, Bonus, and City.

**Timeline slicer** – Analyze trends over time.

**Charts and visuals** – Compare station capacity, availability, and city distribution.

**Map visualization** – View geographic distribution of bike stations.

**Matrix table** – View detailed city-level metrics.

**Cards/KPIs** – Quickly see totals for bikes, stands, and active stations.

- This interactive dashboard helps stakeholders analyze bike availability, monitor station performance, and support decision-making for bike-sharing operations.

## 👩‍💻 Author
 > Lavanya Madhan Raj


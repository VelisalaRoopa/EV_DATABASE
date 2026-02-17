# EV_DATABASE

A Python-based data analytics project that scrapes EV specifications, cleans real-world messy data, and performs exploratory data analysis with visualizations to compare electric vehicles based on range, efficiency, charging speed, and price.

#  Electric Vehicle Data Analysis (Web Scraping + EDA)

##  Project Overview

This project performs an end-to-end data analysis on Electric Vehicles (EVs) to help users understand how to choose the right EV based on **range, efficiency, charging performance, and cost**.

The project collects real-world EV data using web scraping and transforms messy raw data into meaningful business insights using Python and visualization techniques.

##  Objectives

* Compare EVs based on range, battery capacity, efficiency, and price
* Identify value-for-money vehicles
* Understand market trends across brands and drivetrain types
* Recommend suitable EV categories for different user needs (city, family, long trip, budget)


##  Tech Stack

* **Python**
* Pandas & NumPy (Data Processing)
* Matplotlib & Seaborn (Visualization)
* Requests & BeautifulSoup (Web Scraping)
* Jupyter Notebook


##  Data Collection

Data was scraped from an online EV database website using:

* `Requests` → to fetch web pages
* `BeautifulSoup` → to extract structured vehicle specifications

Collected attributes include:

* Brand & Model
* Battery Capacity
* Range
* Efficiency (Wh/km)
* Fast Charging Speed
* Price
* Drivetrain (FWD/RWD/AWD)
* Performance & Ratings

##  Data Cleaning & Preprocessing

Real-world data required significant preprocessing:

* Removed units and converted text → numeric values
* Standardized price formats across countries
* Handled missing values
* Renamed and simplified columns
* Dropped irrelevant features
* Created analysis-ready dataset

##  Exploratory Data Analysis

Performed:

* Univariate Analysis
* Bivariate Analysis
* Multivariate Analysis
* Correlation Analysis

Key visualizations:

* Distribution plots
* Brand comparison charts
* Range vs Battery scatter plots
* Price vs Efficiency analysis
* Heatmap correlation matrix

##  Key Insights

* Battery size strongly affects range, but efficiency determines real performance
* Most EVs fall between **350–500 km range**
* AWD vehicles generally provide higher range
* Market dominated by a few major brands
* Mid-range EVs provide the best balance between cost and performance
* Premium EVs have higher cost but not proportionally higher practical value


##  Business Recommendations

| Use Case           | Recommended Type                |
| ------------------ | ------------------------------- |
| Daily city commute | Efficient low battery EVs       |
| Budget buyers      | Affordable mid-range EVs        |
| Long trips         | High-range AWD EVs              |
| Families           | Balanced range + comfort models |
| Performance/Luxury | Premium high battery EVs        |


##  Learning Outcomes

* Handling messy real-world datasets
* Data cleaning and preprocessing techniques
* Exploratory Data Analysis (EDA)
* Data storytelling using visualization
* Converting raw data into business decisions

##  Future Improvements

* Add machine learning model for EV recommendation
* Build interactive dashboard (Power BI / Streamlit)
* Automate periodic data updates

##  Conclusion

The best EV is not necessarily the one with the biggest battery —
it is the one that balances **battery capacity, efficiency, and price**.


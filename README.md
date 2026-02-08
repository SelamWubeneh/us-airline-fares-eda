Project Title: US Airline Fares & Routes Analysis (1993–2024)

Project Overview

This project explores how airline fares in the United States have changed over time and what factors most influence ticket pricing. 
Using historical flight route and fare data from 1993 to 2024, I performed exploratory data analysis (EDA) to understand patterns related to distance, 
seasonality, passenger volume, and route characteristics. The goal of this analysis was to turn raw airline data into meaningful insights that 
explain why fares vary and how pricing behavior changes over time.



Objectives

	•	Understand the distribution and behavior of airline fares
	•	Analyze the relationship between flight distance and airfare
	•	Identify seasonal pricing patterns across quarters
	•	Examine long-term fare and passenger volume trends
	•	Explore which features most influence airline pricing decisions


Dataset

	•	Source: US Airline Flight Routes and Fares (1993–2024)
	•	Key Variables:
	•	fare – average ticket price
	•	nsmiles – flight distance (miles)
	•	passengers – passenger volume
	•	year, quarter – time indicators
	•	Route and airport identifiers

Note: The raw dataset is not included in this repository due to file size.

Analysis Approach

The analysis was conducted step by step using Python andfocused on clarity and interpretation rather than complex modeling.

1  Data Cleaning & Preparation

	•	Reviewed data types and missing values
	•	Ensured numeric features were correctly formatted
	•	Prepared variables for analysis and visualization

2 Exploratory Data Analysis
   
	•	Univariate analysis: distribution of average airfare
	•	Bivariate analysis: distance vs fare, passengers vs fare
	•	Multivariate analysis: distance, fare, and seasonality together
	•	Trend detection: long-term fare and passenger trends over time
	•	Correlation analysis: relationships among numeric features
	•	Feature exploration: identifying the most influential pricing drivers


Key Findings

	•	Flight distance is the strongest driver of airfare. Longer routes generally have higher fares due to fuel, time, and operational costs.
	•	Clear seasonal pricing patterns exist. Certain quarters consistently show higher average fares, reflecting peak travel periods.
	•	Average airfare has increased over time, indicating long-term changes in pricing behavior.
	•	Passenger volume alone does not strongly determine price. High demand does not always lead to higher fares, suggesting competitive and route-specific pricing strategies.
	•	Route characteristics matter. Even among popular routes, fare distributions vary significantly.


Business Implications

	•	Airlines can use distance and seasonality as key inputs for pricing strategies.
	•	Seasonal trends can support better capacity planning and promotions.
	•	Understanding long-term pricing trends helps with forecasting and strategic decision-making.
	•	Route-level analysis highlights the importance of competition and hub dynamics.


Limitations

	•	The dataset does not include external factors such as fuel prices, airline mergers, or macroeconomic indicators.
	•	Some carrier-specific details are not available, limiting deeper competitive analysis.


Next Steps

	•	Incorporate external data (fuel costs, inflation, economic indicators)
	•	Build predictive models to estimate airfare
	•	Expand analysis to include competitive market dynamics

Tools Used

	•	Python (Pandas, NumPy)
	•	Matplotlib & Seaborn
	•	Jupyter Notebook






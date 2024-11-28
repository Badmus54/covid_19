 INTRODUCTION:
 The COVID-19 pandemic, caused by the SARS-CoV-2 virus, has become one of the most significant public health challenges in modern history. Emerging in late 2019 in Wuhan, China, the virus quickly spread across the globe, leading to unprecedented disruptions in healthcare systems, economies, and daily life. By early 2020, the World Health Organization (WHO) declared COVID-19 a global pandemic, signaling the urgent need for coordinated international public health responses.
Objective:
	Analyze global COVID-19 data to understand trends, impacts, and public health implications.
	
	Dataset Source:
		 Kaggle: the COVID-19 Dataset (CORD-19) available on Kaggle.
		Here is the URL to the dataset:
		https://www.kaggle.com/datasets/imdevskp/corona-virus-report
 
	
Key Questions:
	What are the global trends in cases, recoveries, confirmed  and deaths?
	What insights can be used for policy-making?
![image](https://github.com/user-attachments/assets/ae58e619-950d-4cb8-848e-ca1382fb0bdb)
Description:
We have 49068 rows and 10 columns, 78 states,187 countries and 6 WHO regions covered.
The total confirmed cases are 828,508,482, Deaths: 43,384,903, Recovered:388,408,229, Active:396,715,350 the Deaths rate is 5.24% while the recovery rate is 46.88%
Americas have the highest mortality rate also the highest confirmed cases while Africa has the lowest confirmed case and also mortality case
Key Features:
Date, Country/Region, Confirmed Cases, Deaths, Recoveries, WHO Region, etc.
Dataset Limitations:
Missing data for some regions.
Reporting inconsistencies across countries.
![image](https://github.com/user-attachments/assets/69e0c2e5-9e5a-4118-9233-d88a4e0c18e5)

Exploratory Data Analysis (EDA)
Insights:
Global and regional case trends over time.
Top countries by total cases, deaths, and recoveries.
Visualizations:
Line chart of global daily cases and deaths.
Bar chart: WHO Region  with highest cases.
Heatmap: Case density by region.
![image](https://github.com/user-attachments/assets/a9ccb8a5-7da6-4183-9b5c-efac77261e69)

Predictive Modeling
Objective: Forecast future trends in cases and deaths.
Model Used:
Time Series: 
Classification: Random Forest classifier, SVM for predicting daily cases.
Evaluation Metrics:
Accuracy, F1 scores, Confusion Matrix.
![image](https://github.com/user-attachments/assets/905fc524-3dee-4649-8f84-60e8b6cec877)

 CONCLUSION :
The analysis of Covid-19 data reveals significant disparities in total deaths across. 
WHO Regions, indicating urgent healthcare needs in heavily affected areas. Countries with the highest increase in confirmed cases highlight emerging hotspots requiring immediate intervention. overall, these visualizations emphasize the need for targeted responses and international collaboration to combat the ongoing crisis
![image](https://github.com/user-attachments/assets/3dce7f40-33db-40e9-907a-c72b3044e8c8)



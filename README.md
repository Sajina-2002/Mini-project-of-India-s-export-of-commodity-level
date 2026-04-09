
INDIA’S EXPORTS AT PRINCIPLE COMMODITIES

## 📖 Table of Contents
- [Project Overview](#-project-overview)
- [Data Source](#-data-source)
- [Tools & Technologies](#-tools--technologies)
- [Data Cleaning & Preparation](#-data-cleaning--preparation)
- [Exploratory Data Analysis (EDA)](#-exploratory-data-analysis-eda)
- [Key Insights](#-key-insights)


## 📊 Project Overview
This project involves cleaning ,transforming and analysing raw data using excel and creating interactive power BI dashboard to derive meaningful business insights.
The main objective is to demonstrate data pre processing techniques using excel and interactive power BI dashboard visualization to make informed decisions.


## 🗂️ Data Source
•	Source description and timeline: Directorate general of commercial intelligence and statistics /https://indiadataportal.com//port-level-exports-and-imports/2018-2023
•	Domain: Commerce 


## 🛠️ Tools & Technologies
- **Language:** CSV
- **Database:** MS Excel
- **Visualization:** Power BI
- **Documentation:** MS Word

## 🧹 Data Cleaning & Preparation
•	Data cleaning and transformations: Removed duplicates and created (country code) calculated field for the purpose of creating fact and dimension table.
•	Fact and Dimension table: 
1.	Fact table: Year, State code, Port, Country, Commodity, Quantity, Dollar value, INR value.
2.	Dimension table:
•	State Dim (state and state code) using VLOOKUP formula.
•	Country_dim (country and country code) using LEFT formula from country table


## 🔍 Exploratory Data Analysis (EDA)
what is the overall country's performance in both quantity and value basis?
what is the overall export performance in both port and state wise?


## 💡 Key Insights
	Compared from 2022 to 2023, the performance of the Indian exports declined, indicating a slowdown in export performance.
	Possible reasons would be reduced global demand, supply chain basis, currency fluctuations, policy restrictions.
	India’s exports are dominated by bulk mineral commodities in terms of volume, but revenue is primarily driven by high-value sectors like organic chemicals and marine products.
	India’s export volume is driven by countries like China and Bangladesh, while export value is primarily driven by developed markets such as the USA and Europe.”
	India’s export quantity is concentrated in mineral-based commodities and geographically dominated by western states like Gujarat, highlighting both commodity and regional concentration.
	India’s exports are heavily concentrated in a few coastal states, with Gujarat leading in both value and quantity due to strong port infrastructure and industrial capacity.
Export performance is strongly linked to port availability, indicating that infrastructure plays a critical role in driving trade efficiency.





- Provide instructions for running the notebook or script.# Mini-project-of-India-s-export-of-commodity-level
Mini project (Excel and Power BI)

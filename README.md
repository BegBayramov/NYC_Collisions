# NYC_Collisions
🚦 NYC Traffic Accidents Analysis (R) 

📌 Project Overview

This project analyzes motor vehicle collisions reported by the New York City Police Department (NYPD) from January 2021 to April 2023 using the R programming language. Each record represents an individual traffic accident and includes information about the date, time, location, involved vehicles, victims, and contributing factors. The goal of this project is to apply data cleaning, transformation, and exploratory data analysis (EDA) in R to uncover accident patterns and risk factors.

 🗂️ Dataset Description

The dataset includes:
Accident date and time
Borough, zip code, and street name
Latitude and longitude
Number of persons injured and killed
Vehicle types involved
Contributing factors
Time period: January 2021 – April 2023 

🛠️ Tools & Libraries

R
tidyverse (dplyr, tidyr, readr)
lubridate – date and time manipulation
ggplot2 – data visualization
GitHub – project documentation  

🔍 Key Analytical Questions

This analysis answers the following questions:
What percentage of total accidents occurred each month?
Are there observable seasonal patterns?
How does accident frequency vary by day of week and hour of day?
When do accidents occur most frequently?
Which street had the highest number of reported accidents?
What percentage of all accidents does this represent?
What was the most common contributing factor overall?
How does this differ for fatal accidents? 

🧹 Data Preparation

The following steps were performed in R:
Handling missing and invalid values
Parsing date and time fields using lubridate
Extracting month, day of week, and hour
Filtering fatal vs non-fatal accidents
Aggregating accident counts by time, location, and contributing factors. 

📊 Data Visualization

The project includes the following visualizations:
Monthly distribution of accidents (% of total)
Accidents by hour of day
Accidents by day of week
Heatmap of accidents by day and hour
Top streets by accident frequency
Contributing factors for all vs fatal accidents
Visualizations were created using ggplot2. 

🧠 Key Insights

Accident frequency shows seasonal variation across months
Most accidents occur during peak traffic hours
A small number of streets account for a large proportion of accidents
Certain contributing factors are strongly associated with fatal accidents

🚀 Conclusion

This project demonstrates the use of R for real-world data analysis, including data cleaning, feature engineering, and visual storytelling.
The insights from this analysis can support better understanding of traffic safety patterns in New York City.




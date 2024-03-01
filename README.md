
###BoxRentingWeatherAnalysis

##Project Overview

This project aims to analyze the correlation between weather conditions and portable storage box rentals in Dallas. By leveraging weather data and box rental records, the goal is to uncover valuable patterns and insights. Identifying any correlation between the data and weather patterns could prove beneficial for companies' paid search campaigns, as weather may be a factor they haven't considered.

##Built with

-VS Code
-Python
-Pandas
-Excel
-Tableau

##Links
- Live Site URL:[(https://public.tableau.com/views/PortableStorageBoxRentalWeatherAnalysis2023/Dashboard1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)]

##Data Sources

Box Rental Data: The dataset includes records from a small business operating in Dallas. Originally consisting of box booking data and customer information, I modified it to show only box rental dates and box counts for specific dates.

Weather Data: Weather information includes date, temperature, and weather descriptions sourced from OpenWeatherMap's historical weather data.

##Project Walkthrough

For this project, I aimed to create an Excel file containing information from both box rental and weather data. Initially, I collected only noon rows from the weather data. However, realizing that this approach misconstrued the data, I expanded to include all hours. I set up a Python environment in VS Code, using Pandas to manipulate the data, merging relevant columns into a new Excel file. The 'groupby' method helped aggregate the data, counting daily box rentals.

Once the data analysis was complete, I uploaded the new Excel spreadsheet to Tableau, where I built a dashboard to visualize my findings.

##Results & Evaluations

The data suggests that an increase in temperature during the summer may lead to a decline in box rentals. However, other contributing factors might influence this trend. Weather descriptions showed no correlation between higher box rentals and sunny days. After analyzing the data, it became clear that a more accurate picture would emerge with over 3 years of box rental data. The storage company began operations in April 2022, and 2023 marked their first full year. Future data analysis with a more extended timeframe could provide a clearer understanding.

##Conclusion

This project served as a valuable learning experience, providing insights into data analysis from various perspectives. While mistakes were made, addressing and rectifying these issues served as an effective teacher, contributing to an enhanced understanding of data interpretation.



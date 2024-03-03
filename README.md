
### BoxRentingWeatherAnalysis

## Project Overview

This project aims to analyze the correlation between weather conditions and portable storage box rentals in Dallas. By leveraging weather data and box rental records, the goal is to uncover valuable patterns and insights. Identifying any correlation between the data and weather patterns could prove beneficial for companies' paid search campaigns, as weather may be a factor they haven't considered.

## Built with

- VS Code
- Python
- Pandas
- Excel
- Tableau

## Links
- Live Site URL: [(https://public.tableau.com/views/2023PortableStorageandWeatherAnalysis/Dashboard1?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)]

## Data Sources

Box Rental Data: The dataset includes records from a small business operating in Dallas. Originally consisting of box booking data and customer information, I modified it to show only box rental dates and box counts for specific dates.

Weather Data: Weather information includes date, temperature, and weather descriptions sourced from OpenWeatherMap's historical weather data.

## Project Walkthrough

For this project, my objective was to create an Excel file containing information from both box rental and weather data. Initially, I collected data only for noon rows from the weather dataset. However, realizing that this approach misrepresented the data, I expanded to include data for 9 am, 3 pm, and 5 pm as well. Considering that the midday average would provide a more accurate depiction of Texas summers, I set up a Python environment in VS Code, using Pandas to manipulate the data and merge relevant columns into a new Excel file. The 'groupby' method proved useful in aggregating the data and counting daily box rentals.

I also revisited the storage data after completing this project. When the dates were grouped together to count the number of box rentals in a single day, it omitted the days where zero box rentals occurred. I rectified this error, ensuring that there were 365 rows of data, one for every day of the year.

Once the data analysis was complete, I uploaded the new Excel spreadsheet to Tableau, where I built a dashboard to visualize my findings.

## Results & Evaluations

The data suggests that an increase in temperature during the summer may lead to a decline in box rentals. However, other contributing factors might influence this trend. The weather descriptions did show a higher daily box rental average for a clear day when compared to a rainy or cloudy day. However, throughout the year, there were more cloudy days, which could lead to a lower average.

After analyzing the results, it became clear that a more accurate picture would emerge with over three years of box rental data, as a longer time period could reveal a specific pattern. The storage company commenced operations in April 2022, and 2023 marked its first full year. Future data analysis with an extended timeframe could provide a clearer understanding.

## Conclusion

This project served as a valuable learning experience, providing insights into data analysis from various perspectives. While mistakes were made, addressing and rectifying these issues served as an effective teacher, contributing to an enhanced understanding of data interpretation.



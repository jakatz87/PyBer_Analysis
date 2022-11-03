# PyBer Analysis
## Project Overview
I was tasked with analyzing ride share data for the company PyBer.  Throughout the project, I created several visualizations using Matplotlib, culminating in a comparison of Monthly Ride Fare amounts by type of city that the company serves.

## Resources
**Data Sources:** city_data.csv and ride_data.csv

**Software:** Jupyter Notebook, Pandas, Matplotlib, Python 3.7.6

## Results
With Pandas, I was able to merge Data Frames from the original CSV files and create several visual displays:
- Scatter Plot comparing average fares by total number of rides per city (with a reference to city type)
![image1](https://github.com/jakatz87/PyBer_Analysis/blob/main/analysis/Fig1.png)

- Box and Whisker Plots analyzing data for the number of rides, fare amounts, and number of drivers
![image2](https://github.com/jakatz87/PyBer_Analysis/blob/main/analysis/Fig2.png)
![image3](https://github.com/jakatz87/PyBer_Analysis/blob/main/analysis/Fig3.png)
![image4](https://github.com/jakatz87/PyBer_Analysis/blob/main/analysis/Fig4.png)

- Pie Charts showing the breakdown of rides and drivers by city types
![image6](https://github.com/jakatz87/PyBer_Analysis/blob/main/analysis/Fig6.png)
![image7](https://github.com/jakatz87/PyBer_Analysis/blob/main/analysis/Fig7.png)

- A Multiple Line Plot showing the Monthly Fare Amounts by City Type from January through April.
![finalimage](https://github.com/jakatz87/PyBer_Analysis/blob/main/analysis/Fig8.png)

## Summary
Overall, the company should investigate Driver Mobility as an issue for customer access and company revenue growth.
I have three recommendations based on this analysis:
1. The Pie Charts show a potential for resource allocation to increase access to Rural cities.  It is evident the need for rides is higher than the amount of drivers available.  The company could look at solutions for driver relocation to Rural cities.  
2. The Scatter Plot and the Box and Whisker Plots show that a driver reallocation from Urban to Rural cities could possibly accomplish the goal of affordability in Rural cities, and potential increase revenues by increasing average fare amounts in Urban cities.
3. The Monthly Fare Amount Line Plot shows that a reallocation of drivers would vary from month to month, although only slightly.  For example, the Suburban fares spike at the end of April where Urban and Rural decrease, but during the month of March, the Suburban fares are lower compared to February and April.


# Data on the Move: Uber 2024 Exploratory Analysis

![Uber logo](https://cdn.mos.cms.futurecdn.net/M4hbiWhoo8n3bQQ2hKg5s3-1172-80.jpg.webp)

# Introduction
Uber is a multinational ride-hailing and technology company that connects riders and drivers through its mobile platform. Founded in 2009 and headquartered in San Francisco, Uber has expanded its services to more than 10,000 cities across over 70 countries. Through the Uber app, users can request on-demand transportation, schedule rides, or access related services such as food delivery and freight logistics.

As of 2024, Uber remains one of the largest and most recognized mobility platforms in the world, completing billions of trips annually and supporting a global network of independent driver-partners. Its extensive data on ride patterns, cancellations, and customer behavior offers valuable insight into urban mobility trends and real-time transportation demand.

This project presents an exploratory data analysis of Uber ride data from 2024, uncovering key patterns in bookings, cancellations, and daily ride trends. Using Python as the primary language—alongside powerful libraries such as Pandas for data cleaning and manipulation, and Matplotlib and Seaborn for visualization—the analysis highlights insights into rider behavior, peak demand periods, and operational efficiency across different days and months.

# Objectives

The primary objective of this project is to perform an in-depth exploratory data analysis of Uber’s 2024 ride dataset. Using Python and the Pandas library, the data was thoroughly cleaned and prepared to handle missing values, ensure accurate data types, and maintain overall quality. The analysis aims to uncover booking trends across different days, months, and times of day, as well as to investigate customer and driver cancellation behavior. Key findings are presented through clear visualizations created with Matplotlib and Seaborn, providing actionable insights into rider behavior, peak demand periods, and operational efficiency.

## Business Questions

1. What are the overall booking trends by day of the week and by month in 2024?

2. Which hours of the day experience the highest and lowest ride demand?

3. What are the most common reasons for customer and driver cancellations?

4. How do cancellations affect daily and monthly booking patterns?

5. Are there identifiable periods of peak demand that could guide driver allocation or promotional strategies?

# Tools & Technologies
1. Python – Core programming language for data cleaning, transformation, and analysis.
2. Pandas – Data wrangling and manipulation, handling missing values, and efficient group-by operations.
3. NumPy – Numerical computing and support for vectorized operations.
4. Matplotlib – Creation of static, high-quality visualizations and custom plots.
5. Seaborn – Advanced statistical graphics and aesthetically pleasing charts.
6. Jupyter Notebook – Interactive environment for code execution, analysis, and visualization.
7. Git & GitHub – Version control, project documentation, and public repository hosting.

# Data Analysis

### 1. What factors drive the month-to-month variation in Uber bookings, and how does this distribution impact overall annual performance?

![Monthly distribution plot](https://github.com/damoncaliber/Uber-2024-EDA/blob/main/images/Figure1_BPM.png)

As we can see from the graph, Uber’s monthly booking volumes display a clear uneven distribution across the year, with noticeable peaks in January and July—each exceeding roughly 12,800 rides—and dips in   February and September, which hover near 12,000. This pattern indicates that bookings are not evenly spread throughout the year but cluster around specific periods, suggesting that seasonal factors such as holidays, tourism cycles, or regional events likely contribute to the month-to-month variation and, in turn, influence total annual performance.

 Overall Stability:
 Despite the peaks and dips, monthly bookings remain within a relatively narrow band (roughly 12 000–13 000 rides), showing a steady customer base across the year.

 Dual High Points:
 The two highest months—January and July—form a roughly six-month cadence, hinting at a semi-annual rhythm in rider activity.

 Quick Rebounds:
 After each low month (February and September), bookings climb back toward the upper range within one or two months, suggesting that demand recovers quickly after slow periods.

 Balanced Mid-Year Trend:
 From March through June and again from August through December, the distribution stays close to the yearly average, reflecting a long mid-year stretch of consistent demand.



### 2. How do daily booking patterns vary across the week, and are there specific weekdays that experience higher or lower ride demand?

![daily distribution plot](https://github.com/damoncaliber/Uber-2024-EDA/blob/main/images/Figure_2_BPD.png)

As we can see from the visual, the distribution of Uber bookings is remarkably consistent across all seven days of the week, with only minor fluctuations of about 5–10 bookings. Saturday shows a slight uptick,   suggesting marginally higher weekend activity, while Thursday appears to be the lowest point, though the difference is minimal. This even spread indicates that demand for rides is steady regardless of weekday, highlighting a stable customer base that is not strongly influenced by typical weekday–weekend cycles.

Low Volatility:
The range between the highest and lowest daily booking counts is small (roughly a 2–3 % difference), indicating very low variability in demand. This stability suggests that operational resources—such as driver availability—can remain relatively constant throughout the week.

Balanced Weekday vs. Weekend Demand:
Unlike many transport services that see weekend spikes, the data shows only a slight Saturday lift and virtually no Sunday drop. This pattern points to a customer base that likely uses Uber for both commuting and leisure in roughly equal measure.

Implication for Forecasting:
Because day-to-day swings are minimal, short-term forecasting models can rely on simpler, steady-state assumptions without needing strong weekday-specific adjustments.

























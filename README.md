Project Overview: In this project, I built an interactive Power BI dashboard to analyze the performance of various apps in terms of key metrics such as ratings, reviews, installs, app size, and pricing. The goal was to visualize and compare the performance of different product categories and understand the relationship between features like app size, pricing models (free vs. paid), and performance indicators like ratings and installs.

Steps and Methodology:

Data Import & Cleaning:

Imported the dataset from Excel/CSV into Power BI.
Cleaned and transformed the data using Power Query:
Replaced missing values and handled irrelevant data.
Converted the "Installs" and "Price" columns to numerical values by removing non-numeric characters (like commas, "+" signs, and currency symbols).
Applied Trim and Replace functions to remove any junk characters.
Creating Key Measures:

Defined custom DAX measures to track key product performance metrics:
Average Rating: AvgRating = AVERAGE(YourTable[Rating])
Total Reviews: TotalReviews = SUM(YourTable[Reviews])
Total Installs: TotalInstalls = SUM(YourTable[Installs])
Additional measures for app size and app type (free vs. paid).

Building Visualizations:

Developed several key visualizations to present insights:
Rating Distribution: Bar chart showing average ratings by app category.
Reviews vs. Installs Comparison: Scatter plot to compare the number of reviews against installs for each app.
Category-Wise Performance: Stacked bar chart illustrating performance across different categories in terms of installs and reviews.
Free vs. Paid App Performance: Pie chart showing the distribution of free vs. paid apps and their performance.
App Size vs. Performance: Bubble chart analyzing the effect of app size on ratings and installs.
Last Updated Analysis: Line chart tracking performance metrics like rating changes after app updates.

Interactive Features:

Added filters and slicers for:
App Category
Price (Free/Paid)
Content Rating
Genres
Enabled users to dynamically explore data by filtering based on these fields.

Key Performance Indicators (KPIs):

Created KPI cards for:
Total Installs
Total Reviews
Average Rating

Dashboard Customization:

Ensured readability by using consistent colors for different app categories and free/paid apps.
Added descriptive titles, labels, and organized visuals for a clear layout.
Publishing:

Published the dashboard to Power BI Service, allowing stakeholders to access the interactive report.

Tools & Technologies:

Power BI for data import, cleaning, visualization, and dashboard development.
Power Query Editor for data transformation.
DAX for creating custom measures and calculations.

Key Insights:

The analysis revealed trends in the app marketplace, such as higher ratings for apps in specific categories and a clear distinction between the performance of free and paid apps. Visuals showed how app size impacts installs and ratings, and the analysis of recent updates suggested improvements in customer feedback following updates.

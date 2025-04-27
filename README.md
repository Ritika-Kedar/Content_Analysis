# Content_Analysis

Introduction:

In today's data-driven environment, understanding patterns and structures within large datasets is crucial for decision-making and trend identification.
This project focuses on performing Exploratory Data Analysis (EDA) on a dataset related to content (movies, shows, or similar media), specifically examining directors, ratings, and platform distribution.
The objective is to uncover hidden patterns, trends, and key statistics using structured dashboards and visualizations.
This report aims to explore and analyse the dataset on ott data. Let's delve into the details:

1. Data Overview:
   
•	The dataset consists of information about different streaming content data.

•	The dataset includes information related to: Content, Directors and associated metadata, Release years, Duration (in minutes), Ratings, Platform availability (e.g., Netflix, Hulu, Prime Video), The dataset allows an in-depth evaluation of director activity, content distribution, and platform dominance.


2. Data Acquisition and Preprocessing
   
The data was loaded from a CSV file using pandas. Libraries like NumPy and warnings were imported for numerical operations and handling warnings, respectively. seaborn, and matplotlib were used for data visualization.

Data cleaning steps included:

•	Handling missing values by replacing 'na' with NaN.

•	replacing zeros or invalid entries appropriately.

•	Standardizing duration and release year values.

•	Ensuring proper formatting of categorical variables (like directors and platforms).


3. Exploratory Data Analysis (EDA)
   
•	Checked column types, missing values, and summary statistics using df.info(), df.describe(), and df.isnull().sum().

•	Feature Understanding: Examined how director names, release years, and platform presence are distributed.


4. Data Description
   
•	Descriptive statistics for numerical columns such as: Content duration and Release year trends using df.describe().

•	Assessed the saturation of directors across different ratings and platforms.


5. Content Analysis
   
5.1 Director Saturation Analysis

•	Evaluated saturation levels of directors across different ratings.

•	Highlighted directors contributing to high-rated or low-rated content.

5.2 Platform Distribution

•	Visualized the spread of directors among various platforms.

•	Identified which platforms have a higher or lower concentration of specific directors.

5.3 Top Directors Analysis

•	Top 10 Most Active Directors:

o	Ranked directors based on the number of productions across all platforms.

•	Top 10 Highest Rated Directors:

o	Highlighted directors with the best average ratings.


6. Data Visualizations
   
•	Bar Charts:

o	Showing saturation of directors in different rating categories.

•	Pie Charts:

o	Depicting director distribution across platforms.

•	Top Lists:

o	Displaying the most active and highest-rated directors.

•	Line Graphs:

o	Showing trends over time.



Conclusion:

•	The content analysis revealed meaningful distribution patterns of directors across platforms and ratings.

•	 Key directors emerged as influential figures based on either their volume of productions or consistently high ratings.

•	Platform-wise comparisons showed disparities in director saturation, offering insights into strategic content creation across companies.

This report provides a comprehensive analysis of streaming content, focusing on the distribution of content across platforms, sentiment analysis, director performance, and emerging content trends. Through various analytical techniques, including data preprocessing, exploratory data analysis (EDA), and visualization, the report uncovers significant patterns that reveal insights into content popularity, director activity, and platform strategies.

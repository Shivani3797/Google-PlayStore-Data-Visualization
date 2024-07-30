# Google-PlayStore-Data-Visualization-Case-Study

This repository contains the code and analysis for the Google Play Store case study completed as part of the Executive PG AI and ML module. The goal of this case study was to use data visualization to solve business problems and understand the features that define a well-performing app.

# Problem Statement
The team at Google Play Store aims to develop a feature to boost visibility for the most promising apps. This analysis requires understanding the features that contribute to an app's success. Key questions include:

1. Does a higher size or price necessarily mean better performance?
2. Does a higher number of installs correlate with better ratings?

# Summary of Case Study

### Data Handling and Cleaning:

1. Cleaned junk records.
2. Added missing values.
3. Changed data types.
4. Removed outliers.

### Ratings Analysis:

Used a histogram to analyze ratings, which are skewed towards higher ratings.

### Category Distribution:

Created bar charts to show that most apps belong to the 'Everyone' category.

### Size and Ratings:

Used scatter plots to observe a weak trend between app size and ratings.

### Pair-Plot Insights:

Used pair plots to see multiple scatter plots, revealing weak trends between price and ratings, and inverse relationships between reviews and price.

### Content Rating Categories:

Used estimator functions along with bar plots and box plots to observe the spread of ratings across different content rating categories, with 'Everyone' having many low-rated apps.

### Heat Map:

Created a heat map comparing ratings across different reviews and content rating buckets.


# Technology Used:

1.Python 3.x
2. Libraries: seaborn, matplotlib, pandas, numpy

# Contributing:
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

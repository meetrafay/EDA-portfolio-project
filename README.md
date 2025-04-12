# EDA-portfolio-project
 The notebook concludes that by implementing the recommendations, AeroFit can refine its marketing and product strategies, leading to increased sales and customer satisfaction. Continued data analysis is crucial for ensuring the effectiveness of these strategies.


# AeroFit Treadmill Buyer Profile Analysis

## Project Overview

This project analyzes customer data to identify the characteristics of the target audience for each type of treadmill offered by AeroFit. The goal is to provide better product recommendations to new customers by understanding customer preferences and usage patterns.

## Dataset

The dataset used for this analysis contains information on individuals who purchased a treadmill from AeroFit stores during the prior three months. It includes details such as product purchased, demographics (age, gender, education, marital status), usage habits, and fitness levels.

## Analysis

The project involves the following steps:

1. **Data Exploration and Processing:** Cleaning and preparing the data for analysis, including handling missing values and duplicates.
2. **Statistical Summary:** Analyzing descriptive statistics for numerical and categorical features to understand customer demographics and product preferences.
3. **Univariate and Bivariate Analysis:** Visualizing individual features and relationships between them using histograms, box plots, and count plots.
4. **Multivariate Analysis:** Exploring interactions between multiple features and their impact on product choice using pair plots.
5. **Correlation Analysis:** Identifying correlations between numerical features using a heatmap.
6. **Outlier Detection:** Detecting potential outliers in numerical data using the IQR method.
7. **Conditional Probabilities:** Calculating the likelihood of specific customer segments purchasing certain products, based on demographics, usage, and fitness levels.
8. **Data Profiling:** Generating a comprehensive data profile report using the `ydata-profiling` library for further insights.

## Insights and Recommendations

The analysis reveals distinct customer profiles for each treadmill model, highlighting the influence of income, education, usage, and fitness levels on product choice. Key recommendations include:

- **Targeted marketing campaigns** for each product segment.
- **Product development strategies** based on customer preferences and usage patterns.
- **Pricing strategies** that consider price sensitivity of different customer segments.
- **Customer relationship management** improvements through personalized communications.
- **Further investigation** of demographic influences and usage patterns.

## Conclusion

By implementing the recommendations, AeroFit can refine its marketing and product strategies, leading to increased sales and customer satisfaction. Continued data analysis is crucial for ensuring the effectiveness of these strategies.

## Usage

To run this analysis, you will need Python 3 and the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- ydata-profiling

You can install these libraries using `pip`:

# Zomato Restaurant and Worldwide Analysis with Power BI

## Project Overview

This project involves analyzing Zomato's global restaurant data to uncover hidden trends and anomalies. Zomato, a prominent restaurant aggregator and food delivery service based in India, operates internationally, providing detailed information and customer reviews for numerous eateries. The goal is to create a comprehensive and interactive Power BI report to evaluate business performance and enable data-driven decisions.

## Objectives

1.⁠ ⁠*Comprehensive Data Overview:*
   - Display the total number of restaurants worldwide, broken down by continents, countries, and cities.
   - Provide a global view with the capability to drill down to granular data.

2.⁠ ⁠*Detailed Analysis:*
   - Identify restaurants with the highest average customer ratings.
   - Discover the restaurants with the lowest average costs.
   - Determine restaurants offering the most cuisines.

3.⁠ ⁠*Filtering and Navigation:*
   - Allow filtering by geographical dimensions (continent, country, city).
   - Filter based on services provided (e.g., online ordering, reservations).
   - Filter by average rating categories, indicated by specific colors.

4.⁠ ⁠*User Experience:*
   - Design a multi-page report with Zomato's branding, ensuring easy navigation.
   - Enable access to the report via web browsers and mobile devices.

## Data Import and Preparation

1.⁠ ⁠*Data Import:*
   - Import data from multiple Excel files, each representing different continents and associated restaurant information.

2.⁠ ⁠*Data Transformation:*
   - *City Name Corrections:* 
     - Correct city names for consistency (e.g., "Sí£o Paulo" to "São Paulo", "Cedar Rapids/Iowa City" to "Cedar Rapids", "ÛÁstanbul" to "Istanbul").
   - *Column Cleanup:*
     - Remove unused columns to streamline the data model.
   - *Data Structuring:*
     - Separate restaurant names and addresses into distinct columns.
     - Create a dedicated table listing the cuisines offered by each restaurant.
   - *Country-Code Table:*
     - Ensure the table contains unique, non-blank entries, as it serves as a dimension table.

## Data Analysis and Visualization with DAX

1.⁠ ⁠*Rating Color Column:*
   - Add a calculated column to categorize restaurants based on average ratings, using specific colors:
     - Above 4.5: Dark Green
     - 4 to 4.4: Green
     - 3.5 to 3.9: Yellow
     - 2.5 to 3.4: Orange
     - 1.8 to 2.4: Red
     - 0 to 1.7: White

2.⁠ ⁠*Key Measures:*
   - *Restaurant Count:* Number of restaurants.
   - *Average Cost:* Average cost across restaurants.
   - *Average Rating:* Average customer rating.
   - *Cuisine Count:* Number of cuisines served.

3.⁠ ⁠*Continent Classification:*
   - Create a new column in the Country Code table named "Continent" to classify countries accordingly.

## Dashboard Design and User Interface

1.⁠ ⁠*Visualizations:*
   - Utilize a variety of charts and visual elements:
     - Card visuals for key metrics (Restaurant Count, Average Cost, Average Rating).
     - Map visuals with geographic hierarchy and restaurant counts.
     - Infographic designer to showcase top restaurants by average cost and rating.
     - Slicers for filtering by rating colors, countries, and cities.
     - Grid for displaying restaurant details.
     - Gauges for displaying selected restaurant's average rating and cost.
     - Cards and grids for showing restaurant addresses and list of cuisines.

2.⁠ ⁠*Publishing and Access:*
   - Publish the Power BI report to the Power BI service, ensuring it is accessible via public URL.
   - Create a user-friendly mobile view to complement the web-based report.

## Conclusion

This project provides a detailed analysis of Zomato's global operations, offering valuable insights into restaurant performance and customer preferences. The interactive dashboard allows stakeholders to explore the data at various levels, enhancing decision-making and business strategy formulation.

## Live Dashboard Access

To explore the live dashboard I've developed, please visit the following link:

**[Click here to view the Live Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZjI5MjE0ODMtYTZkNC00MzVkLTg5ZDEtMjE0M2ViNjgxMjRkIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)**

The dashboard provides real-time insights and visualizations based on the latest data.

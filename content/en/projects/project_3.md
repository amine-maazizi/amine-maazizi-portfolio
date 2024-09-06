---
title: "TrendViz: Amazon Best Sellers Analytics Dashboard"
date: 2024-09-02
draft: false
description: "A comprehensive dashboard that automates the extraction and analysis of Amazon's best-selling electronics data, providing valuable insights through interactive visualizations and detailed reports."
cover:
    image: "images/project_3/ratings.PNG"
tags: ["Data Analysis", "Web Scraping", "Visualization", "Python", "Flask", "Plotly"]
categories: ["Projects"]
---

## Overview

**TrendViz** is an analytical dashboard designed to extract and analyze data from Amazon's best-selling electronics list. This project automates web scraping, data cleaning, and insightful visualizations, providing users with a powerful tool to explore market trends and consumer preferences. Built with a focus on accuracy, efficiency, and interactivity, TrendViz transforms raw data into actionable insights through a user-friendly web interface.

## Objectives

- **Extract**: Automate the data extraction from Amazon’s best sellers page for electronics, capturing key product information such as name, price, ratings, and review counts.
- **Clean**: Process and clean the extracted data to ensure accuracy and consistency for meaningful analysis.
- **Analyze**: Perform comprehensive analysis on various product attributes to identify trends, patterns, and correlations.
- **Visualize**: Present data insights through interactive and informative visualizations on a web-based dashboard.
- **Report**: Generate detailed reports that summarize key findings and trends, helping users make data-driven decisions.

## Gallery

Below are some screenshots showcasing the application in action:

![Top products](/images/project_3/top.PNG)
*The main dashboard showcasing top selling articles.*

![Statistics](/images/project_3/stats.PNG)
*Displays key statistics extracted from the scraped data.*

![Pricings Plot](/images/project_3/pricings.png)
*Plot showing the correlation between pricing and ratings.*

![Data](/images/project_3/data.png)
*CSV file of the scraped data.*
<!-- 

## Key Features

- **Automated Web Scraping**: Utilizes Selenium and Beautiful Soup to extract data from Amazon’s best sellers page, including product names, prices, ratings, reviews, and links.
- **Top Products Identification**: Highlights the most frequent and popular products among the best sellers.
- **Price Range Analysis**: Provides a statistical overview of product prices, including minimum, maximum, average, and median values.
- **Ratings and Reviews Insights**: Analyzes average ratings, identifies the highest and lowest rated products, and examines the distribution of review counts.
- **Correlation Analysis**: Explores relationships between product price, popularity (reviews), and ratings to uncover insights.
- **Interactive Visualizations**: Offers interactive plots and charts for an engaging and detailed exploration of data trends.
- **User-Friendly Interface**: Features a clean, modern design with an intuitive layout that enhances the user experience.
- **Web Scraping**: Efficiently extracts up-to-date data from Amazon without manual intervention, ensuring the dashboard reflects the latest market dynamics.

## Detailed Workflow

### 1. **Data Extraction**
- The system uses Selenium for automated browsing and Beautiful Soup for parsing HTML to extract product details such as names, prices, ratings, and links from Amazon’s best sellers page.

### 2. **Data Cleaning**
- A data cleaning script processes the raw data by handling missing values, standardizing formats, removing duplicates, and converting data types for accurate analysis.

### 3. **Data Analysis**
- Analyzes key metrics including top products, price range statistics, average ratings, and review counts.
- Correlates various data points, such as price vs. popularity and ratings vs. review counts, to reveal insights.

### 4. **Data Visualization**
- Utilizes Plotly.js to create interactive scatter plots, histograms, and other visual elements that allow users to explore data trends directly from the dashboard.

### 5. **Dashboard Reporting**
- Displays findings on a Flask-based web dashboard with sections dedicated to each aspect of the analysis, such as top products, price statistics, and correlation insights.
- The dashboard is designed for ease of use, allowing users to navigate through various sections and interact with the data visualizations.

### 6. **User Interaction**
- Users can explore different sections of the dashboard to view insights and trends, with features allowing them to drill down into specific data points for deeper analysis.

## Technologies Used

### Backend:
- **Python**:
  - **Selenium & Beautiful Soup**: For web scraping to collect data from Amazon.
  - **Pandas**: Handles data processing, cleaning, and analysis.
  - **Flask**: Powers the web application, serving the dashboard and handling backend logic.
  - **Jinja2**: Templating engine for rendering HTML dynamically based on data analysis results.

### Frontend:
- **Plotly.js**: Used for creating interactive data visualizations within the dashboard.
- **HTML/CSS/JavaScript**: Utilizes vanilla HTML, CSS


## Pricing and Time Estimates

For a comprehensive package including all the features and services described, the estimated total cost ranges from **$925 to $2,000**, with an approximate completion time of **5-8 weeks**, including revisions and testing.

| Service                              | Pricing                  | Time Frame  | Revisions                                      |
|--------------------------------------|--------------------------|-------------|------------------------------------------------|
| **Data Insights Automation**         | $600 - $1200 per setup   | 2-4 weeks   | Up to 2 revisions for model adjustments        |
| **Report Generation**                | $75 - $200 per setup     | 1 week      | Includes up to 2 revisions for data adjustments|
| **Web Scraping**                     | $150 - $300 per setup    | 1-2 weeks   | Up to 2 revisions for extraction parameters    |
| **Data Integration and Synchronization** | $100 - $300 per integration | 1 week | Up to 2 revisions for minor adjustments       |
| **Customization and Support**        | $50 - $100 per month     | Ongoing     | Covers routine updates and minor feature enhancements | -->

## Contact Me

[Contact Page](../../contact) — Reach out for more information or to schedule a demo.
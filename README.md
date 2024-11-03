# Automotive Market Data Scraping and Analysis

## Project Overview
This project involved scraping over 1,000 car listings from Autotrader to analyze key factors influencing mileage, pricing, and model specifications. By automating data collection and applying detailed analysis, this project provides insights for data-driven automotive market trends.

## Features
- Data Collection: Scraped 1,000+ listings for attributes such as mileage, price, make, and model.
- Data Cleaning: Standardized and cleaned the dataset, reducing noise by removing 100+ irrelevant entries, ensuring data consistency for accurate analysis.
- Exploratory Data Analysis (EDA): Visualized data to uncover patterns in car pricing and mileage, yielding insights for potential market predictions.

## Project Structure
- data_collection.py: Contains scripts to scrape data from the Autotrader website using requests and BeautifulSoup.
- data_cleaning.py: Includes functions to clean and preprocess raw data.
- analysis.ipynb: Jupyter Notebook performing EDA and visualizing key insights from the data.
   
## Insights
- Mileage vs. Price: Found that vehicles with lower mileage tend to have prices 25-40% higher than similar models with higher mileage.
- Regional Pricing Trends: Discovered 15% higher average prices in certain regions, indicating localized demand surges.
- Impact of Model and Age on Price: Identified that newer models within a popular brand range have a 20-30% premium over older models, even with similar mileage.

## Dependencies
- requests
- beautifulsoup4
- pandas
- matplotlib
- seaborn

## Results
This analysis demonstrates the impact of factors such as mileage, model, and region on car pricing, offering actionable insights for buyers, sellers, and automotive analysts. The automated scraping and data cleaning scripts reduced data collection time by 75%, ensuring rapid updates for ongoing analysis.

# Airbnb Listings Analysis in Riyadh 🏙️

## Overview

This project provides an in-depth analysis of Airbnb listings in Riyadh. The analysis includes data quality checks, feature engineering, and various insights into listings, rental types, and their relationships with price and ratings.

## Data Quality Checks 🛠️

Before performing the analysis, the following data quality checks were conducted:

- **Missing Values:** Identified and handled missing values.
- **Duplicates:** Removed duplicate entries.
- **Value Corrections:** Fixed inconsistencies in the data.

## Feature Engineering 🔧

Several new columns were created to enhance the analysis:

- **Place Type:** Extracted from the 'name' column to categorize listings.
- **Amenities:** New columns were created from 'previewAmenities' to track the presence of key amenities, including:
  - Self check-in ✔️
  - Wifi 📶
  - Kitchen 🍽️
  - Air conditioning ❄️
- **Neighborhood:** Added based on longitude and latitude columns to categorize listings by neighborhood.

## Analysis 📊

The analysis includes the following aspects:

1. **Distribution of Listings by Neighborhood:**
   - Identified that most listings are located in As Sahafa.

2. **Rental Types Distribution Across Riyadh Neighborhoods:**
   - Found that entire rental units are the most common rental type across neighborhoods.

3. **Distribution of Rental Types by Place Type:**
   - Confirmed that entire rental units remain the most prevalent type. Heatmap analysis shows no strong correlation between rental type and price or rating.

4. **Price and Rating by Neighborhood:**
   - Observed that North Riyadh has the highest prices and ratings.

5. **Impact of Amenities and Other Factors:**
   - Explored the relationship between price and rating with:
     - Amenities (Self check-in, Wifi, Kitchen)
     - Cancellation policies 📅
     - Place types 🏠

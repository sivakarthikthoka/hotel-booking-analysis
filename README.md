# hotel-booking-analysis

# Project Overview

This project analyzes an international hotel booking dataset to understand booking patterns, customer preferences, and factors that affect hotel ratings and performance. By applying Exploratory Data Analysis (EDA), visualizations, and statistical insights, the project helps identify trends in hotel bookings and provides useful insights for the hospitality industry.

# Dataset

File Name: hotels.csv

Rows: 25

Columns: 13

Key Columns:

hotel_id, hotel_name – Unique identifiers for hotels

city, country – Location details

star_rating – Hotel rating (stars)

cleanliness_base, comfort_base, facilities_base, location_base, staff_base, value_for_money_base – Rating metrics

lat, lon – Geographical location

## Step-by-Step Process

Data Loading

Load the dataset (hotels.csv) using Pandas.

Data Inspection

View dataset shape, first few rows, and column details.

Check for missing values (none found in this dataset).

Data Cleaning

Ensure correct data types.

Standardize categorical values (if needed).

Exploratory Data Analysis (EDA)

Summary statistics for numerical and categorical columns.

Visualizations:

Bookings by hotel type

Distribution of star ratings

Average rating (cleanliness, staff, etc.) comparisons

Location-based analysis (cities, countries)

Feature Engineering (Optional)

Compute overall rating score (average of different base ratings).

Extract geographical or location-based insights.

Insights

Identify top-performing hotels.

Highlight cities/countries with highest ratings.

Detect strengths/weaknesses (e.g., cleanliness vs. value for money).

Modeling (Optional Extension)

Predict hotel ratings or price trends using regression/classification models.

📊 Tools & Libraries

Python – Main language

Pandas – Data analysis

NumPy – Numerical computations

Matplotlib – Data visualization

Jupyter Notebook / VS Code – Development environment



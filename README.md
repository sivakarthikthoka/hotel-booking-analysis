# hotel-booking-analysis

Hotel Booking Analysis
📌 Project Overview

This project analyzes an international hotel booking dataset to understand booking patterns, customer preferences, and factors that affect hotel ratings and performance. By applying Exploratory Data Analysis (EDA), visualizations, and statistical insights, the project helps identify trends in hotel bookings and provides useful insights for the hospitality industry.

📂 Dataset

File Name: hotels.csv

Rows: 25

Columns: 13

Key Columns:

hotel_id, hotel_name – Unique identifiers for hotels

city, country – Location details

star_rating – Hotel rating (stars)

cleanliness_base, comfort_base, facilities_base, location_base, staff_base, value_for_money_base – Rating metrics

lat, lon – Geographical location

🔎 Step-by-Step Process

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

🚀 How to Run

Clone this repository:

git clone https://github.com/your-username/hotel-booking-analysis.git


Navigate to the project folder:

cd hotel-booking-analysis


Install required libraries:

pip install -r requirements.txt


Run the analysis notebook or script:

jupyter notebook hotel_booking_analysis.ipynb

📌 Results & Insights

No missing data in the dataset.

Hotels vary across cities and countries with different star ratings.

Key rating factors: Cleanliness, Staff, Value for Money strongly influence overall satisfaction.

Visualizations provide clear insights into hotel performance by location and features.

📖 Future Work

Add predictive models (price prediction, cancellation prediction).

Build a dashboard for interactive visualization.

Expand dataset with more rows for deeper insights.

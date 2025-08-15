# Airbnb
Data cleaning, analysis, and visualization of Airbnb listings to uncover pricing trends, occupancy patterns, and market insights
🏡 Airbnb Data Analysis Project
📌 Project Overview

This project focuses on data cleaning, exploratory data analysis (EDA), and visualization of Airbnb listings to uncover pricing trends, occupancy patterns, and market insights.
By analyzing real Airbnb dataset attributes such as location, reviews, availability, and pricing, we aim to help hosts, travelers, and analysts better understand the short-term rental market.

📂 Dataset

Source: Airbnb dataset (CSV format)

Key Columns: id, name, host_id, neighbourhood_group, neighbourhood, latitude, longitude, room_type, price, minimum_nights, number_of_reviews, last_review, reviews_per_month, availability_365

🛠️ Tools & Libraries Used

Python (Data Processing & Analysis)

Pandas, NumPy – Data manipulation

Matplotlib, Seaborn – Visualization

Scikit-learn – Data preprocessing

Jupyter Notebook – Interactive development

🔍 Key Steps in the Project

Data Loading & Inspection

Imported dataset and checked for null values, duplicates, and inconsistent formats.

Data Cleaning

Removed irrelevant columns (e.g., IDs not needed for analysis).

Handled missing values in columns like reviews_per_month and last_review.

Filtered out outliers (e.g., unrealistic prices and minimum nights).

Exploratory Data Analysis (EDA)

Visualized price distributions across different neighborhoods and room types.

Analyzed relationships between review count, availability, and pricing.

Mapped listing density using latitude & longitude.

Insights & Trends

Average prices vary significantly by neighbourhood group and room type.

Certain areas have high occupancy but low pricing—potential for pricing optimization.

Review frequency shows seasonality patterns in some regions.

📊 Visualizations Included

Price distribution plots

Neighborhood vs. price bar charts

Availability heatmaps

Review trends over time

Geographic scatter plots of listings

🚀 How to Run the Project

Clone the Repository

git clone https://github.com/your-username/airbnb-data-analysis.git
cd airbnb-data-analysis


Install Dependencies

pip install -r requirements.txt


Open Jupyter Notebook

jupyter notebook


Run the Analysis

Open Airbnb_Project.ipynb and run cells step-by-step.

📌 Possible Future Improvements

Build a price prediction model using machine learning.

Automate scraping of updated Airbnb data.

Integrate Tableau or Power BI dashboards for interactive exploration.

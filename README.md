# 📊 Hotel Bookings Analysis – GTC ML Project 1

## 🏨 Project Overview
This project explores a real-world dataset of hotel bookings to uncover patterns in customer behavior, cancellation trends, and booking characteristics. The goal is to demonstrate data cleaning, exploratory data analysis (EDA), and feature engineering using Python tools in a Google Colab environment.

## 📁 Repository Contents
- `hotel_bookings.csv` – Original dataset containing booking records
- `hotel_bookings_analysis.ipynb` – Colab notebook with code, visualizations, and insights
- `README.md` – Project documentation and summary

## 🧹 Data Cleaning Steps
The dataset was cleaned and prepared using the following steps:
- Removed duplicate records
- Converted date columns to proper datetime format
- Filled missing values in key columns (`children`, `country`)
- Created new features such as:
  - `total_stay`: total nights stayed (weekend + weekday)
  - `is_family`: boolean indicator for family bookings

## 📊 Exploratory Data Analysis
Several visualizations and summaries were created to explore the data:
- **Cancellation Rate**: Distribution of canceled vs. non-canceled bookings
- **Hotel Type**: Comparison between city and resort hotels
- **Stay Duration**: Histogram of total nights stayed
- **Family Bookings**: Analysis of bookings involving children or babies
- **Monthly Arrivals**: Seasonal trends based on arrival month

## 📈 Future Improvements
- Build a predictive model to forecast cancellations
- Analyze pricing impact on booking behavior
- Integrate external data (e.g., holidays, weather) for deeper insights

## 🛠️ Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## 🚧 Challenges Faced
- Handling missing and inconsistent data
- Understanding relationships between multiple features
- Visualizing large datasets efficiently

## 📬 Contact
For questions or suggestions, feel free to open an issue or reach out via email.


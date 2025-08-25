# Major-Project

# Hotel Booking Analysis

This project explores the dynamics of hotel reservations using a dataset inspired by the popular Hotel Booking Demand dataset (Antonio et al.). The analysis focuses on uncovering booking behaviors, pricing trends, and guest preferences to answer practical questions such as:

When are bookings typically made?

What’s the “prime time” to secure the best rates?

How does length of stay affect daily rates (ADR)?

Which factors drive special requests?

What demographic and segment patterns shape demand?

# Features

Booking Window Insights
Understand how far in advance guests tend to book, with seasonal and hotel-type variations.

Prime Time for Deals
Identify booking windows where Average Daily Rates (ADR) are more favorable.

Length of Stay vs. Price
Explore the relationship between nights stayed and ADR to spot the sweet spot for cost efficiency.

Special Requests Drivers
Analyze which factors (party size, kids, hotel type, seasonality, etc.) lead to higher special requests.

Demographics & Segments
Break down booking patterns by market segment, customer type, and country of origin.

# Outputs

Cleaned dataset with engineered features (total_nights, party_size, has_kids, etc.)

Interactive summary tables (lead times, ADR patterns, segment breakdowns)

Visualizations:

Lead-time distributions & seasonal patterns

ADR vs. length of stay

Booking arrivals by month

Median ADR by booking window

# Tech Stack

Python 3.8+

Libraries:

pandas, numpy – data wrangling

matplotlib – visualizations

scikit-learn (optional) – feature importance for special requests

# How to Run

Clone this repository:

git clone https://github.com/yourusername/hotel-booking-analysis.git
cd hotel-booking-analysis


# Install dependencies:

pip install -r requirements.txt


Add your dataset (CSV) to the project root as hotel_bookings.csv.
(Compatible with the Hotel Booking Demand dataset)

Run the analysis:

python hotel_bookings_analysis.py

# Example Insights

Median lead time across all bookings: ~90 days

Weekend stays show higher ADRs than weekday stays

Families with children/babies request ~2x more special services

Direct and corporate bookings tend to secure lower ADRs compared to OTA bookings

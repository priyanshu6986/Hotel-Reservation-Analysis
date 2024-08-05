#Hotel Reservation Analysis

##Description
This project analyzes hotel booking data to understand trends related to reservations, cancellations, and average daily rates (ADR). The dataset is sourced from hotel bookings and contains critical information that can help hotel management improve booking strategies and understand customer behavior.

##Features
Data cleaning and preprocessing, including handling missing values and irrelevant columns
Exploratory data analysis (EDA) through various visualizations using Matplotlib and Seaborn
Comparison of cancellation rates between different hotel types
Analysis of Average Daily Rates (ADR) based on reservations and cancellation statuses
Monthly breakdown of cancellations and ADR

##Dataset
The dataset hotel_bookings 2.csv includes the following columns (among others):

hotel: Type of hotel (City Hotel or Resort Hotel)
lead_time: Number of days between the booking date and the arrival date
arrival_date_year: Arrival year
adr: Average Daily Rate
is_canceled: Cancellation status (1 for canceled, 0 for not canceled)
reservation_status_date: Date of reservation status

##Requirements
To run this project, you need Python and the following libraries:

Pandas
Matplotlib
Seaborn
Jupyter Notebook (optional, for running the notebook)

You can install the required libraries using:
pip install pandas matplotlib seaborn  

##Usage
Clone the repository:

git clone https://github.com/YOUR_USERNAME/hotel-booking-analysis.git  
cd hotel-booking-analysis  
Download the dataset hotel_bookings 2.csv and place it in the project directory.

Open a Jupyter Notebook or run the script directly using Python.
Run the code to visualize hotel booking patterns and analyze various factors affecting cancellations and ADR.

##Visualizations Included
Bar chart depicting total reservations based on cancellation status.
Count plots showing cancellation status across different hotel types.
Line plots comparing average daily rates of City vs Resort hotels.
Monthly breakdown of cancellations and affecting ADR.
Pie chart showing the top 10 countries with the highest cancellation rates.

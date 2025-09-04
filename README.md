# Hospitality Data Analysis Using Python

## Project Description
This project analyzes hospitality data to uncover key trends and insights regarding hotel bookings, revenue generated and occupancy.

## Problem Statement and Objective
Atliq Grands, an Indian hotel chain with 20 years of industry experience and operations in Delhi, Mumbai, Bangalore, and Hyderabad, is facing significant challenges from competitors, leading to revenue and market share loss. To address this, Atliq Grands management has decided to onboard data analytics and implement data-informed decision making to increase revenue and market share.

## Dataset
Data sources are from the CSV files as listed below:
- dim_date.csv - File contains date information
- dim_hotels.csv - File has infornation about the properties and the types (Luxury and Business) based on the location
- dim_rooms.csv - File has information related to room class (Standard, Elite, Premium, Presidential)
- fact_aggregated_bookings.csv - File has an overview of the bookings
- fact_bookings.csv - File has detailed information on every booking at transactional level
- new_data_august.csv - August month booking data

## Steps involved to execute the Project
1. Data Loading & Exploration
2. Data Cleaning
3. Data Transformation
4. Visualization
5. Insights & Conclusions

## Tools & Libraries
- Language - Python 3.10
- Libraries - pandas, numpy, matplotlib, seaborn
- IDE - Google Colab notebook

## Key Insights
- Presidential rooms has the highest occupancy rate of **59.30%** while Premnium rooms has the lowest occupancy rate of **58.03%**
- Delhi has the highest occupancy rate at **61.61%**, followed by Hyderabad with an occupancy rate of **58.14%**. Mumbai has occupancy rate of 57.94% and Bangalore has the lowest among the listed cities, at **56.59%**.
- Average occupancy rate for hotels is higher on weekends than weekdays. The occupancy rate on weekends is about **72.39%**, while it's **50.90%** on weekdays.
- In June Delhi had the highest occupancy rate at **62.47%**, followed by Hyderabad at **58.46%**, Mumbai at **58.38%**, and Bangalore at **56.58%**.
- Mumbai generated the highest revenue, followed by Hyderabad, Bangalore, and Delhi. This indicates that Mumbai had the most profitable hotel business among these cities.
- Revenue generated is highest in the month of May, followed by July and June
- Luxury hotels generated the highest revenue, significantly more than business hotels. This suggests that luxury accommodations are more profitable
- Hotels in Delhi has the highest average rating followed by Hyderabad, Mumbai and Bangalore
- Others platform generates the largest revenue contributing to **40.9%** of the total revenue. MakeYourTrip is also a significant platform contributing to **20%** of the revenue while Direct Offline, Direct Online, Journey, Logtrip, and Tripster contribute smaller percentages to the overall revenue.
  
## How to Run
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Open `notebooks/analysis.ipynb` in Jupyter

## Limitations & Future Work
- Data from only one region; more datasets could improve generalizability.

## License
MIT

## Contact
Your Name - your.email@example.com

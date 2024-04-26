## Project Summary 
Namma Yatri Data Analysis: Optimizing Ride-Sharing Operations in Bangalore and Mysore.

## Dashboard

![WhatsApp Image 2024-04-25 at 11 49 34 PM](https://github.com/Anukriti204/Nama_Yatri_Data_Analysis/assets/159823977/aac4b2fb-6cb5-456f-9528-7a0bb6d2ca2f)
  
## Overview
Namma Yatri, a ride-sharing service similar to Ola and Uber, operates in Bangalore and Mysore. This data analysis project aims to leverage SQL and Power BI to analyse trip details, booking patterns, and fare information to enhance operational efficiency and customer experience.

## Key Objectives  
1. Data Collection and Preparation: Gather trip details and fare data from Namma Yatri's databases and preprocess it for analysis.
2. SQL Analysis: Utilize SQL queries to extract insights from trip details, including search behaviour, trip completion status, and payment methods.
3. Power BI Visualization: Create interactive dashboards to visualize booking trends, revenue patterns, and user behaviours. Highlight - peak booking hours, popular destinations, and driver earnings.

## Insights: 
1. Peak Booking & Revenue: Trips peak at 1 PM, correlating with highest revenue.
2. Popular Destination: "Madhavpura" tops search frequency.
3. Conversion Opportunity: More searches (2161) than completed trips suggest conversion enhancement potential.
4. Driver Earnings: Total driver earnings reach a significant milestone: 751K.

## Recommendations: 
1. Implement strategies to capitalize on peak booking hours and maximize revenue.
2. Optimize search functionality to increase the conversion rate from searches to completed trips.
3. Introduce incentives or improvements to enhance driver earnings and satisfaction

## Trip details sheet
1. tripid - id of the trip
2. loc_from - origin of the trip
3. searched - number of searched for particular trip (from - to)
4. searches_got_estimate - estimated cost for that particular trip
5. search_for_quotes - search for drivers
6. search_got_quotes - out of all search_for_quotes how many searches got drivers
7. customer_not_cancelled - 0 means customer has cancelled the order and 1 means customer has not cancelled the order
8. driver_not_cancelled - 0 means driver has cancelled the order and 1 means driver has not cancelled the order
9. otp_entered - 0 means otp hasn't been entered 1 means otp has been etered
10. end_ride - 0 means ride is not ended successfully 1 means ride ended successfully
Trips Sheet
11. faremethod - method of the payment 1-cash, 2-upi, 3-debit card, 4-credit card
12. fare - fare of the trip
13. loc_from - origin of the trip
14. loc_to - destination of the trip
15. driverid - which driver was assigned for the trip
16. custid - which customer was taking this trip
17. distance - total distance
18. duration - total duration taken for the trip
19. Assembly - have identified different assemblies for loc_from and loc_to

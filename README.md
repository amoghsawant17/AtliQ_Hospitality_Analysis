# Revenue Insights Hospitality - Power BI
In this impactful project, I delved into the hospitality sector, focusing on AtliQ Grands, a distinguished hotel chain. With a comprehensive analysis of their booking and capacity data, I constructed a Power BI dashboard for insightful data visualization.

- Link to [Portfolio Website](https://codebasics.io/portfolio/Amogh-Sawant)
- Link to [Live Dashboard](https://www.novypro.com/project/revenue-insights-hospitality-power-bi)

## Problem statement

Atliq Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, Atliq Grands is losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of Atliq Grands wanted to incorporate “Business and Data Intelligence” to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights.

Their revenue management team had decided to hire a 3rd party service provider to provide them with insights from their historical data.

### Task List

You are a data analyst who has been provided with sample data and a mock-up dashboard to work on the following task.

- Create the metrics according to the metric list. 
- Create a dashboard according to the mock-up provided by stakeholders. 
- Create relevant insights that are not provided in the metric list/mock-up dashboard.

## Provided Mock-up Dashboard
<p align="center">
    <img src="https://github.com/amoghsawant17/AtliQ_Hospitality_Analysis/blob/main/Snapshots/mock%20up%20dashboard_atliq%20grands.png" width="600">
</p>


## Data Model

<p align="center">
    <img src='https://github.com/amoghsawant17/AtliQ_Hospitality_Analysis/blob/main/Snapshots/snap_data_model.png' height="400">
</p>

## Home View

<p align="center">
    <img src='https://github.com/amoghsawant17/Revenue_Insights_Hospitality/blob/main/Snapshots/snap_home.png' width="600">
</p>

## Overview

<p align="center">
    <img src='https://github.com/amoghsawant17/Revenue_Insights_Hospitality/blob/main/Snapshots/snap_overall.png' width="600">
</p>

## Booking Performance View

<p align="center">
    <img src='https://github.com/amoghsawant17/Revenue_Insights_Hospitality/blob/main/Snapshots/snap_booking.png' width="600">
</p>

## Support View

<p align="center">
    <img src='https://github.com/amoghsawant17/AtliQ_Hospitality_Analysis/blob/main/Snapshots/snap_support.png' width="600">
</p>

## Feedback View

<p align="center">
    <img src='https://github.com/amoghsawant17/AtliQ_Hospitality_Analysis/blob/main/Snapshots/snap_feedback.png' width="600">
</p>

## Attribution View

<p align="center">
    <img src='https://github.com/amoghsawant17/Revenue_Insights_Hospitality/blob/main/Snapshots/snap_attribute.png' width="600">
</p>

## Things that I learned from this Project
- By referring to the different cancellation policies of different hotels, I understood that most of the hotels charge zero fees, only if the booking is canceled before three months of the arrival date. If the booking is canceled after that, the charges range from 60 to 90% of the booking cost.
- I Learned, how to use bookmarks and selection for different purposes. (Page navigation and a clear filter button in the dashboard were achieved using bookmarks and selection same as a website page navigation.
- Tried using the color palette and sticking with those colors throughout the dashboard ([Color palette link](https://colorhunt.co/palette/0766ad29adb2c5e898f3f3f3))

## Some Key Metrics
#### Week-on-Week (WoW) 
- It is a type of business metric that measures changes in a specific variable over one week compared to the previous week. It is a common way of tracking business performance over time and is particularly useful for analyzing trends and identifying areas where improvements can be made.
- Here are the metrics for which I found the WoW change %:
1. Revenue WoW change %: To get the revenue change percentage week over week.
2. Occupancy WoW change %: To get the occupancy change percentage week over week.
3. ADR WoW change %: To get the ADR (Average Daily rate) change percentage week over week.
4. RevPAR WoW change %: To get the RevPAR (Revenue Per Available Room) change percentage week over week.
5. Cancellation WoW change %: To get the Cancellation change percentage week over week.
6. DURN WoW change %: To get the DURN (Daily Utilized Room Nights) change percentage week over week.
#### ADR 
- It is the ratio of revenue to the total rooms booked or sold.
- ADR = Total Revenue/ Total rooms booked or sold
#### RevPAR
- RevPAR represents the revenue generated per available room, whether or not they are occupied. RevPAR helps hotels measure their revenue-generating performance to accurately price rooms. RevPAR can help hotels measure themselves against other properties or brands.
- RevPAR = Total Revenue/ Total Capacity
#### DSRN - Daily Sellable Room Nights
- This metric tells on average how many rooms are ready to sell for a day considering a period.
- DSRN = Total Capacity/ Number of days
#### DURN - Daily Utilized Room Nights
- This metric tells on average how many rooms are successfully utilized by customers for a day considering a period.
- DURN = Total Checked Out/ Number of days

## Some Important insights from the Dashboard
- Mumbai region has generated the highest revenue (660 Million ₹) among all regions.
- AtliQ Exotica outperforms all seven types of properties with a revenue of 316.5 Million ₹, a rating of 3.62, an occupancy rate of 56.5%, and a cancellation rate of 24.4%.
- AtliQ Blu boasts the highest occupancy rate of 61.9%.
- Week 29 recorded the highest revenue among all weeks, totaling 139.7 Million ₹.
- AtliQ suffered a revenue loss of around 295 Million ₹ due to cancellations.
- Bookings made through other modes are the highest, 40.9%, followed by MakeMyTrip, Log Trip, and Direct Online.
- Occupancy rates are higher on weekends compared to weekdays across all categories and hotels.
- The Delhi region has the highest occupancy rate (60%) and the highest average rating (3.78) among all regions.
- The Mumbai region experienced the highest revenue loss due to cancellation, totaling 114 Million ₹, while the Delhi region had the lowest, totaling 51 Million ₹.
- Revenues are higher in the luxury category, around 1040 Million ₹, compared to the business category, around 647 Million ₹.
- ADR is higher in the business category, compared to the luxury category.
- Total bookings are higher in the luxury category, compared to total bookings in the business category.
- DURN is higher in the luxury category, compared to DURN in the business category.
- Revenue loss due to cancellations is higher in the luxury category, compared to the business category.
- The Elite and Standard room classes are most preferred, attracting the highest percentage of bookings, but the Presidential and Premium room classes have generated the highest ADR and RevPAR among other room classes. 
- Revenue loss due to cancellations has decreased over three months from 102 Million ₹ in May to 95 Million ₹ in July.
- AtliQ Blu is the highest-rated (4) hotel among all hotels, and AtliQ Seasons is the lowest-rated (2.3) hotel among all hotels.
 
## Potential Decisions

1. **Cancellation Policy Optimization:** Evaluate and potentially revise the cancellation policy to reduce revenue loss. Consider implementing stricter cancellation deadlines or offering non-refundable booking options with discounts to encourage commitment.

2. **Marketing Strategy for AtliQ Blu:** Leverage AtliQ Blu's high occupancy rate as a marketing point to attract more customers. Develop targeted marketing campaigns highlighting the unique features and experiences offered at AtliQ Blu to increase bookings.

3. **Weekday Promotions:** Create targeted promotions to boost weekday bookings, as occupancy rates are higher on weekends. Offer special deals, packages, or discounts for guests booking stays from Monday to Thursday to balance occupancy throughout the week.

4. **Address AtliQ Seasons Issues:** Identify and address the issues affecting AtliQ Seasons' low rating. Conduct guest surveys, analyze feedback, and make necessary improvements in service, amenities, and overall guest experience to enhance customer satisfaction.

5. **Regional Marketing Focus:** Capitalize on the success of the Mumbai region by intensifying marketing efforts in that area. Highlight special offers, partnerships, or events that cater to the preferences and needs of the Mumbai market.

6. **Diversify Booking Channels:** Explore opportunities to diversify booking channels by expanding partnerships with various online travel agencies (OTAs) and platforms. This can help tap into different customer segments and reduce reliance on a single channel.

7. **Revise Pricing Strategy:** Analyze the Average Daily Rate (ADR) in both luxury and business categories. Consider adjusting pricing strategies, such as offering dynamic pricing, seasonal discounts, or loyalty programs, to maximize revenue without compromising occupancy rates.

8. **Room Class Optimization:** Evaluate the demand for different room classes and consider adjusting the inventory accordingly. If the Elite and Standard rooms are most preferred, ensure an adequate supply, but also focus on promoting the Presidential and Premium rooms to maximize revenue.

9. **Enhance Direct Booking Experience:** Encourage direct online bookings by improving the user experience on the hotel's website. Implement user-friendly interfaces, exclusive online offers, and loyalty programs to incentivize guests to book directly.

10. **Quality Assurance Programs:** Implement quality assurance programs across all hotels to maintain high standards of service. Regularly train and update staff, conduct audits, and invest in amenities or renovations to consistently deliver a positive guest experience, ultimately improving ratings and attracting more bookings.

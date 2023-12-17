# Hospitality Revenue Analysis

[Link to the Challenge](https://codebasics.io/challenge/codebasics-resume-project-challenge)

[Live Dashboard Link](https://app.powerbi.com/view?r=eyJrIjoiOGEwYWJiMDEtNmI0Zi00Njg3LTgyODktNDIwNmFjYjBlMTNhIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

***

## Table of Content

- [About Company](#About-Company)
- [Problem Statement](#Problem-Statement)
- [Our Goal](#Our-Goal)
- [key Metrics](#key-Metrics)
- [Data Sets](#Data-Sets)
- [Dashboard](#Dashboard)
- [Insights](#Insights)

***

## About Company:

- AtliQ Grands owns multiple five-star hotels across Four cities in India
  
     **1.Bangalore**
      
     **2.Mumbai**
      
     **3.Hyderabad**
      
     **4.Delhi**

- They have been in the hospitality industry for the past 20 years.



***

## Problem Statement:

- Atliq Grands are losing its market share and revenue in the luxury/business hotels category. 
- Due to strategic moves from other competitors and ineffective decision-making in management.
- As a strategic move, the managing director of Atliq Grands wanted to incorporate “Business and Data Intelligence” in order to regain their market share and revenue.
- However, they do not have an in-house data analytics team to provide them with these insights.
- Their revenue management team had decided to hire a 3rd party service provider to provide them insights from their historical data.

***

### My Role in this Project:

- Hi, **I’m Rajesh**, the a new data analyst at AtliQ Grand. 
- I recently joined the company and briefed about the task in the stakeholder business review meeting. 
- Today, I'm excited to discuss the role I'll be building a dashboard to address the Hospitality Revenue challenges.

***

## Our Goal

- Regain their market share in the luxury/business hotels category.
- Understanding the revenue trend by week/month/day
- To get insights where business is failing and what can be done to tackle them

***

## key Metrics

#### 1.Rev PAR = Revenue per Available rooms

#### 2.ADR = Average Daily Rate

#### 3.DBRN = Daily Booked Rooms Nights

#### 4.DSRN =Daily Sellable Rooms Nights

#### 5.DURN = Daily Utilized Rooms Nights

#### 6.Occupancy  % = Occupancy means total successful bookings happened to the total rooms available capacity.

#### 7.Realisation % =  It is nothing but the successful "checked out" percentage over all bookings happened.

*** 

## Data Sets

<details> 
<summary>
 Click here for Meta data(Details of Data Sets)

</summary>

***

This file contains all the meta information regarding the columns described in the CSV files. we have provided 5 CSV files:

**1.** [dim date](#dim-date)

**2.** [dim hotels](#dim-hotel)

**3.** [dim rooms](#dim-rooms)

**4.** [fact aggregated_bookings](#fact-aggregated-bookings)

**5.** [fact bookings](#fact-bookings)

***

## dim date:

**1. date:** This column represents the dates present in May, June and July.

**2. mmm yy:** This column represents the date in the format of mmm yy (monthname year).

**3. week no:** This column represents the unique week number for that particular date.

**4. day_type:** This column represents whether the given day is Weekend or Weekeday.

***

## dim hotels:

**1. property_id:** This column represents the Unique ID for each of the hotels.

**2. property_name:** This column represents the name of each hotel.

**3. category:** This column determines which class[Luxury, Business] a particular hotel/property belongs to. 

**4. city:** This column represents where the particular hotel/property resides in.

***

## dim rooms:

**1. room_id:** This column represents the type of room[RT1, RT2, RT3, RT4] in a hotel.

**2. room_class:** This column represents to which class[Standard, Elite, Premium, Presidential] particular room type belongs.

***


## fact aggregated bookings:

**1. property_id:** This column represents the Unique ID for each of the hotels.

**2. check_in_date:** This column represents all the check_in_dates of the customers.

**3. room_category:** This column represents the type of room[RT1, RT2, RT3, RT4] in a hotel.

**4. successful_bookings:** This column represents all the successful room bookings that happen for a particular room type in that hotel on that particular date.

**5. capacity:** This column represents the maximum count of rooms available for a particular room type in that hotel on that particular date.

***

## fact bookings:
**1. booking_id:** This column represents the Unique Booking ID for each customer when they booked their rooms.

**2. property_id:** This column represents the Unique ID for each of the hotels

**3. booking_date:** This column represents the date on which the customer booked their rooms.

**4. check_in_date:** This column represents the date on which the customer check-in(entered) at the hotel.

**5. check_out_date:** This column represents the date on which the customer check-out(left) of the hotel.

**6. no_guests:** This column represents the number of guests who stayed in a particular room in that hotel.

**7. room_category:** This column represents the type of room[RT1, RT2, RT3, RT4] in a hotel.

**8. booking_platform:** This column represents in which way the customer booked his room.

**9. ratings_given:** This column represents the ratings given by the customer for hotel services.

**10. booking_status:** This column represents whether the customer cancelled his booking[Cancelled], successfully stayed in the hotel[Checked Out] or booked his room but not stayed in the hotel[No show].

**11. revenue_generated:** This column represents the amount of money generated by the hotel from a particular customer.

**12. revenue_realized:** This column represents the final amount of money that goes to the hotel based on booking status. If the booking status is cancelled, then 40% of the revenue generated is deducted and the remaining is refunded to the customer. If the booking status is Checked Out/No show, then full revenue generated will goes to hotels.



</details> 

***


## Dashboard:

<img width="800" alt="image" 
  src="https://github.com/rajeshkumar1312/Hospitality-Revenue-Analysis/blob/main/report/Hospitality%20challenge%20by%20codebasics-sep_page-0001.jpg"> 

***

### Learned things from this Project

- I learned about telling data-driven stories with this beautiful dashboard.

- Understanding the business requirements based on the data.

- Understanding the use of charts and developing DAX measured.

- Researching on and comprehending domain-related basics.

- Visualization methods to enhance report creation.

***

## Insights:

### Realisation and ADR by platform 


<img width="600" alt="image" 
  src="https://github.com/rajeshkumar1312/Hospitality-Revenue-Analysis/blob/main/report/Realisation%20and%20ADR%20by%20Platfrom.png"> 

  
- The realization rates across these platforms are quite consistent, showing that they convert bookings into revenue at similar rates, around 70%. However, the Average Daily Rates (ADR) vary slightly, with Direct Offline and Others having the highest ADR at $12,794.
- Focusing on improving conversion rates might be beneficial for platforms like Tripster and Others, while high ADR platforms should aim for competitive pricing alongside achieving better conversion rates.

***

### % Revenue by category

<img width="600" alt="image" 
  src="https://github.com/rajeshkumar1312/Hospitality-Revenue-Analysis/blob/main/report/%25%20Revenue%20by%20Category.png"> 

- The luxury category generates 61.62% of the total revenue, while the business category contributes 38.38%. This suggests a higher customer preference for luxury experiences, showing a stronger demand for upscale amenities. 
- Despite contributing a substantial share, the business category indicates a slightly lower preference compared to luxury offerings in the hospitality

***

### Trend by Key Metrics(RevPAR, ADR, Occupancy%)

<img width="700" alt="image" 
  src="https://github.com/rajeshkumar1312/Hospitality-Revenue-Analysis/blob/main/report/Trend%20by%20Key%20Metrics.png"> 

- **RevPAR Trend:** Fluctuates across weeks, peaking at W19, W20, W24, W27, W28, W29 indicating higher revenue per available room.

- **ADR Stability:** ADR remains steady around 12,700 with minor fluctuations.

- **Occupancy Pattern:** Shows recurring peaks and valleys, correlating with RevPAR peaks, suggesting a link between higher room occupancy and increased revenue.

- **Overall:** Stable ADR, periodic peaks in RevPAR and occupancy rates, hinting at a connection between higher rates, occupancy, and revenue per room.

***

###  Properties by Key Metrics 


<img width="750" alt="image" 
  src="https://github.com/rajeshkumar1312/Hospitality-Revenue-Analysis/blob/main/report/Property%20by%20key%20metrics.png"> 


- Mumbai leads in revenue at $661M, followed by Bangalore ($415M), Hyderabad ($321M), and Delhi ($291M).
- AtliQ Exotica outperforms with $316M revenue, 3.62 rating, 57% occupancy, 24.4% cancellation, and 23,162 bookings.
- Atliq Grands in Delhi has lower revenue but a high rating. Atliq Palace in Hyderabad generates comparatively less revenue.
- AtliQ Exotica is a revenue powerhouse, but attention to its cancellation rate might enhance its profitability.
- Atliq Grands in Delhi excels in guest satisfaction despite lower revenue, and exploring ways to improve revenue at Atliq Palace in Hyderabad could be advantageous for its performance. 
- Overall, a focus on maximizing revenue while maintaining guest satisfaction stands as a key consideration across these properties.





## THANK YOU



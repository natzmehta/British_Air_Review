# British Airways Review Analysis

**Background & Overview**

British Airways Review Analysis, is a comprehensive customer experience evaluation project that analyzes customer feedback and ratings across multiple service touchpoints through the airline's digital platforms.

The company has accumulated significant customer feedback data covering various aspects including cabin service, ground operations, onboard amenities, and overall satisfaction ratings that were previously underutilized. This dashboard thoroughly analyzes and synthesizes this data to uncover critical insights to enhance British Airways' service delivery and customer experience.

Insights and recommendations are provided on the following key areas:
* Customer Satisfaction Analysis: Evaluation of historical rating patterns, both globally and by region, focusing on Overall Rating, Service Elements, and Aircraft Performance
* Fleet Performance: An analysis of British Airways' various aircraft types, understanding their impact on customer satisfaction and service delivery
* Service Element Success: An assessment of key service components including cabin staff, entertainment, food & beverages, and ground service
  
The analysis is based on customer review data from March 2016 to October 2023, focusing on region & aircraft fleet.


**Data Structure Overview**

British Airways' review database structure consists of the following key tables with a total of 1323 customer reviews: 

Main Tables - 

1. ba_reviews1
     - header
     - author
     - date
     - place
     - content
     - aircraft
     - traveller_type
     - seat_type
     - route
     - date_flown
     - recommended
     - trip_verified
     - rating	Overall
     - rating	seat_comfort
     - cabin_staff_service
     - food_beverages
     - ground_service
     - value_for_money
     - entertainment
  
2. Countries
    - Country
    - Code
    - Continent
    - Region

Before beginning the analysis, several quality control measures were implemented, details can be found in the 'ba_reviews1' Excel file


**Executive Summary**

Overview of Findings:

After peaking in 2020, the company’s overall rating has since seen a drastic drop with most significant drop in 2023. From the ratings perspective, the drop can be attributed to a massive drop average entertainment ratings by 72% in the following year while most other ratings seem inline with previous years. Overall, the drop in ratings cannot be attributed to a single region or aircraft type and the drop in ratings almost seems to be across the board.

While we did a decline in rating post 2020, which can be attributed to the pandemic time; we would ideally expect normalcy in ratings around 2022 & entire 2023.

Below is the overview page from the Tableau dashboard with a deeper analysis included in the report.


Insights Deep Dive:

Core Service Trends:

* If we look at the core service KPIs - overall rating, cabin service, and ground service we see that the company reached the highest overall rating in 2020 (18% growth YoY). With the COVID-19 pandemic there was a significant shift in consumer behavior with more focus on health and protection protocols and increase demand for flexibility which resulted in a slight boost in cabin service ratings (6%)

* The overall rating hit an all time low of 1.0 in December 2020 and has recovered slightly since. However, the rating still remains % lower compared to previous years. 

* Despite the downward trend in overall rating, the average ground service rating seeing a significant upside for 12 consecutive months beginning 3Q23 majorly due the aircraft A321 in the Americas


Fleet Performance:

* In terms of region, the Boeing (avg. rating: 2.5)  aircraft have outperformed the Airbus in terms of overall rating across Europe while we see a reverse trend in North America with airbus having an average rating of 3.1

* In Europe, Boeing 747 has the highest overall rating which can be associated with cabin service & ground service

* While in the Americas, A319 (avg rating: 4.5) outperforms all other fleet services due to a higher average rating to cabin service & value for money


Product Experience:

* The average ratings for seat comfort & food & beverages seems inline with the previous years suggesting the airline has maintained its quality in these two categories

* The average entertainment rating has seen a drastic drop YoY starting Q1 2017 . Te drop seems mainly across the Airbus fleet services with most customers rating a -1. This confirms the hypothesis that -1 isn’t a rating but it relates to the unavailability of an onboard entertainment system since the Airbus services - A319, A320, A321 are short range flights as compared to a Boeing. 


**Recommendations**

* Even though Airbus are short haul flights, it’s important to consider they make up of a majority of revenue for North America. Therefore, we should look at other alternatives of entertainment for the traveler like partnering with a mobile network for free wifi or magazines

* Ground Service for Airbus have historically outperformed Boeing, we should do a deep dive analysis into ground service for major markets of the Airbus including North America and utilize and implement similar ideas to the ground service across Europe through training programs

* Though Europe & North America make up for most of the revenue by region, considering expanding fleet services into more promising markets like Asia and South America

* Continue to push forward the loyalty program - realign benefits with the current consumer demographics. Focus on targeting and personalizing the airline experience for previous customers and utilize previous rating  data to increase marketing efforts when customers choose to fly with us again

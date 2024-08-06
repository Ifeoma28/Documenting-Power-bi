# Open AirBnB


## Table of Contents
- [Project Overview](#ProjectOverview)
- [Data Sources](#DataSources)
- [Reccommendation](#Recommendation)

### Project Overview

This data analysis project aims to provide insights into AirBnB apartments, their hosts listings, effect of reviews and availabilty 365 on the revenue hosts make from AirBnB.By analyzing various aspects of the data, we seek to identify neighborhoods with high revenue,neighborhood groups with top hosts(earners),average satisfaction rate of guests in apartments in New York.

### Data Sources
Open AirBnB data gotten from [Kaggle](https://www.kaggle.com/arianazmoudeh) containing detailed information about apartment listings in New York.

### Tools used
- Excel - for data cleaning
- Power bi - for analyzing and designing dashboard

### Data Cleaning/Preparation
In the initial data preparation phase, we performed the following tasks;
1. Data loading and Inspection
2. Handling missing values
3. Data cleaning and formatting
4. Removal of duplicate rows

### Exploratory Data Analysis
EDA involved exploring the data to answer key questions. I noticed that the service fee was 20% of the room fee. I noticed apartments in some neighborhood groups had more minimum nights than others. I calculated the Revenue each host makes by multiplying the number of minimum nights with the price of the room and subtracting the service fee.
- I began to ask some questions? who are the busiest hosts?
- which neighborhood groups have more availability 365.
- How has the price of apartments been since their construction year?
- Which neighborhood do hosts make less money?
-  Are there any reasons behind this?

### Data Analysis
I created wonderful visualizations on power bi . Firstly i checked the number of neighborhoods we have using the count distinct function on Excel and also the number of neighborhood groups available. Then i calculated the number of available accomodations . i did a barchart to show us which neighborhood group has the highest accomodation. Also to show us the different room types. I looked into the review rate number column.They were ranked from 1 to 5. I noticed that more than 50% of apartments had a 3.0 rating. Also a line chart to show us the price of apartment listings from the beginning of the construction year to 2022. I looked into the different cancellation policy each room has. The prices of apartment listings in the different neighborhood groups. I removed the house rules column because it had a lot of missing values and i didnt want to add bias to my data.

### Findings
There were more accommodations in Manhattan and Brooklyn neighborhood groups with Manhattan having the highest prices. I noticed we had four room types; entire room/apt,private room, shared room and hotel room, with entire room being the highest.Manhattan group had the highest revenue. I did a pie chart to show us the population of top hosts in different neighborhood groups.I noticed Brooklyn had more top earners than Manhattan. So i checked the number of reviews and their availability 365. There was a strong correlation with the no of reviews and availability 365. Manhattan has more availability 365 than Brooklyn owing to the higher no of accommodations but Brooklyn gets more reviews than Manhattan. This shows us that guests tend to enjoy apartments  in Brooklyn than Manhattan despite the prices of houses in Manhattan being higher. Thats why three of our top hosts are from Brooklyn. The median review rate number is 3.0 giving us the general satisfaction rating. Neighborhood groups other than Manhattan and Brooklyn had low revenue even with the low prices owing to low availability 365 ,low calculated host listings and low reviews.
With Power bi , i designed a dashboard showing the no of hosts, calculated host listings, number of reviews and average satisfaction rate.

### Recommendations
- Apartments in Brooklyn need more host listings and availability 365.
- This would help to boost revenue since guests already gives a lot of reviews showing they enjoy their stay there. So increased visibility and instant bookable would increase revenue.
- Apartments in Bronx,Staten Island and Queens need to reduce their service fees, because even with the low prices, guests dont like to stay there. Although this can be attributed  to the low availability 365 and host listings.
- They may be other factors affecting the low number of reviews monthly and while the property is rarely available like poor maintenance and hospitality rate.
- Most guests dont like to use property that has been rarely used and has a low number of reviews even with the low price.
- Apartments in Manhattan should strive for quality experience for their guests to boost their reviews too.

### Limitations
- This data dosent talk about the house rules of apartment listings. I removed the house rules column.
- it dosent talk about the maintenace rate of the apartment listings.
- it is strictly about apartment listings from 2000 construction year to 2022 construction year.










   


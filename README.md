# Open AirBnB


## Table of Contents
- [Project Overview](#ProjectOverview)
- [Data Sources](#DataSources)
- [Reccommendation](#Recommendation)

### Project Overview

This data analysis project aims to provide insights into AirBnB apartments, their hosts listings, effect of reviews and availabilty 365 on the revenue hosts make from AirBnB.By analyzing various aspects of the data, we seek to identify neighborhoods with high revenue,neighborhood groups with top hosts(earners),average satisfaction rate of guests in apartments in New York.
![Dashboard]![AIRBNB DASHBOARD](https://github.com/user-attachments/assets/08a81728-3eed-48ec-bbdd-8774efd32d5f)
 


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
EDA involved exploring the data to answer key questions. I noticed that the service fee was 20% of the room fee. I noticed apartments in some neighborhood groups had more minimum nights than others. I calculated the Revenue each host makes by multiplying the number of minimum nights with the price of the room and subtracting the service fee. I changed the number of reviews column to whole number.
- I began to ask some questions? who are the busiest hosts? [Top 5 Hosts]![Top 5 hosts](https://github.com/user-attachments/assets/1d888008-c34a-4214-b44b-6a17290a6d0d)
- which neighborhood groups have more availability 365. [Availability365]![availability 2](https://github.com/user-attachments/assets/cfcd497a-bb4b-42d5-86e1-b7ccdf62a41f)
- How has the price of apartments been since their construction year?[charts]![chart](https://github.com/user-attachments/assets/876e30f8-9d8b-41ea-80e0-a69bf9d654df)
- Which neighborhood do hosts make less money?![revenue by neighborhood group](https://github.com/user-attachments/assets/ffeb52e7-758b-424c-a577-43a87fc755ac)

-  Are there any reasons behind this?



   
### Data Analysis
- I created wonderful visualizations on Power BI. 
- Firstly I checked the number of neighborhoods we have using the count distinct function on Excel and also the number of neighborhood groups available. Then I calculated the number of available accommodations. 
- I did a bar chart to show us which neighborhood group has the highest accommodation. Also to show us the different room types. I looked into the review rate number column. They were ranked from 1 to 5. I noticed that more than 50% of apartments had a 3.0 rating. - - Also, a line chart to show us the price of apartment listings from the beginning of the construction year to 2022. 
- I looked into the different cancellation policies each room has. The prices of apartment listings in the different neighborhood groups. 
- I removed the house rules column because it had a lot of missing values and I didn't want to add bias to my data.

### Findings 
- Manhattan and Brooklyn had the most accommodations, with Manhattan having higher prices.  
- The highest revenue came from Manhattan, but Brooklyn had more top earners despite its lower prices.  
- I analyzed room types, with entire apartments being the most expensive.  
- A pie chart revealed that Brooklyn had more top hosts than Manhattan.  
- There was a strong correlation between reviews and availability, with Manhattan offering more 365-day availability but Brooklyn receiving more reviews.  
- This indicates that guests prefer Brooklyn's apartments.  
- Neighborhoods outside Manhattan and Brooklyn had lower revenue due to fewer accommodations, lower availability, and fewer reviews.  
- I created a Power BI dashboard displaying hosts, listings, reviews, and satisfaction rates.

### Recommendations
- Apartments in Brooklyn need more host listings and availability 365.
- This would help to boost revenue since guests already gives a lot of reviews showing they enjoy their stay there. So increased visibility and instant bookable would increase revenue.
- Apartments in Bronx,Staten Island and Queens need to reduce their service fees, because even with the low prices, guests dont like to stay there. Although this can be attributed  to the low availability 365 and host listings.
- They may be other factors affecting the low number of reviews monthly and while the property is rarely available like poor maintenance and hospitality rate.
- Most guests dont like to use property that has been rarely used and has a low number of reviews even with the low price.
- Apartments in Manhattan should strive for quality experience for their guests to boost their reviews too.

### Limitations
- This data dosent talk about the house rules of apartment listings because i removed the house rules column.
- it dosent talk about the maintenace rate of the apartment listings.
- it is strictly about apartment listings from 2000 construction year to 2022 construction year.










   

